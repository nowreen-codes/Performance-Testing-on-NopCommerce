# Performance-Testing-on-NopCommerce
### Overview
This project focuses on conducting performance testing for the [NopCommerce](https://test460.nop-station.com/en/) platform to assess its performance under different load conditions. The main goal is to identify any potential bottlenecks and ensure the application’s ability to scale and perform reliably under varying levels of demand.

### Objectives

Load Testing: Test the application’s performance under expected user loads.



Stress Testing: Determine how the application holds up when subjected to extreme conditions.



Scalability Analysis: Evaluate the platform’s ability to handle increasing user demand.



Resource Utilization Monitoring: Monitor key resources such as CPU and memory to identify any inefficiencies during testing.



### Tools and Technologies

[Apache Maven](https://maven.apache.org/download.cgi): Manages dependencies and automates the build process.



[Apache JMeter](https://jmeter.apache.org/download_jmeter.cgi): Used for designing and running performance test plans.



[Java](https://www.oracle.com/bd/java/technologies/downloads/): Required for running JMeter.



### Test Plan
The performance testing will cover the following areas:



###### User Registration: 
Simulate multiple users registering simultaneously to test system response.
###### Product Search and Browsing:
Measure response times when searching for products and browsing categories.
###### Add to Cart and Checkout: 
Test how the system performs during the checkout process with many concurrent users.

### Installation


Download the JDK from the official link if it’s not already installed.
To check if Java is installed, run the following command in your command prompt:
###### java -v
Apache Maven Installation:

Download and install the "binary zip archive" version of Apache Maven.
To confirm if Maven is installed, run the following command in the command prompt:
###### mvn -v
JMeter Installation:

Download the zip file for JMeter from the official link and install it.
To verify if JMeter is installed, run the following command in your command prompt:
###### jmeter -v
Clone the Repository:

Clone the repository using Git with the following command:
###### git clone https://github.com/nowreen-codes/Web-Automation-On-NopCommerce-Using-Playwright.git
Then navigate to the project directory:
###### cd Performance-Testing-on-NopCommerce
Web Recording and Proxy Server Setup:

To record web actions with JMeter, you need to install a proxy server.
Go to the bin folder of the JMeter installation and double-click on ApacheJMeterTemporaryRootCA. Install it, then upload it to your desired browser.



### Output:


#### View Results Tree



The "View Results Tree" listener displays test results in a tree format. It provides detailed information for each individual request made during the test, including response data, status (pass/fail), response time, and more. This feature is especially useful for debugging, as it allows you to pinpoint which requests may have failed or taken longer than expected and also the results tree to see if the test was successful or not. For example, if the response time code is 200, it means everything worked as expected. 

<img width="753" alt="View Results Tree" src="https://github.com/user-attachments/assets/9d63acd4-7f9d-4fe8-a45d-4e147f0210a0" />






Summary Report
The Summary Report listener offers a high-level overview of the test results, usually presented in a tabular format. It summarizes key performance metrics, including average response time, throughput, error rate, and the total number of requests processed. This report is perfect for quickly evaluating the overall performance of the system and identifying any major issues at a glance.






![Summary Report](https://github.com/user-attachments/assets/77e1a0e7-a972-4cd6-b788-ddc884c5b1b2)


## Contributing
Contributions are welcome! Follow these steps:


1. Fork the repository.


2. Create a new feature branch: git checkout -b feature/YourFeature

3. Commit your changes: git commit -m 'Add YourFeature'

4. Push to the branch: git push origin feature/YourFeature

5. Open a pull request.

## Contact
Your Name - [Linkdin](www.linkedin.com/in/nowreen-islam) 


## Reference


1. Target Website for Testing: [NopCommerce](https://test460.nop-station.com/en/)
2. JMeter User Manual: [Jmeter](https://jmeter.apache.org/usermanual/index.html)
