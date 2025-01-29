# Performance-Testing-on-NopCommerce
### Overview
This project focuses on conducting performance testing for the [NopCommerce](https://test460.nop-station.com/en/) platform to assess its performance under different load conditions. The main goal is to identify any potential bottlenecks and ensure the application’s ability to scale and perform reliably under varying levels of demand.

### Objectives

- Load Testing: Test the application’s performance under expected user loads.



- Stress Testing: Determine how the application holds up when subjected to extreme conditions.



- Scalability Analysis: Evaluate the platform’s ability to handle increasing user demand.



- Resource Utilization Monitoring: Monitor key resources such as CPU and memory to identify any inefficiencies during testing.



### Tools and Technologies

- [Apache Maven](https://maven.apache.org/download.cgi): Manages dependencies and automates the build process.



- [Apache JMeter](https://jmeter.apache.org/download_jmeter.cgi): Used for designing and running performance test plans.



- [Java](https://www.oracle.com/bd/java/technologies/downloads/): Required for running JMeter.



### Test Plan
The performance testing will cover the following areas:



- ##### User Registration: 
Simulate multiple users registering simultaneously to test system response.
- ##### Product Search and Browsing:
Measure response times when searching for products and browsing categories.
- ##### Add to Cart and Checkout: 
Test how the system performs during the checkout process with many concurrent users.

### Installation

1. Java JDK Installation:



Download the JDK from the official link if it’s not already installed.
To check if Java is installed, run the following command in your command prompt:
```bash
java -v
```

2. Apache Maven Installation:

Download and install the "binary zip archive" version of Apache Maven.
To confirm if Maven is installed, run the following command in the command prompt:
```bash
mvn -v
```


3. JMeter Installation:

Download the zip file for JMeter from the official link and install it.
To verify if JMeter is installed, run the following command in your command prompt:
```bash
 jmeter -v
```
4. Clone the Repository:

- Clone the repository using Git with the following command:

```bash
 git clone https://github.com/nowreen-codes/Performance-Testing-on-NopCommerce.git

```

- Then navigate to the project directory:


```bash
cd Performance-Testing-on-NopCommerce
```


5. Web Recording and Proxy Server Setup:

To record web actions with JMeter, you need to install a proxy server. Go to the bin folder of the JMeter installation and double-click on ApacheJMeterTemporaryRootCA. Install it, then upload it to your desired browser.



### How to make a project:


- #### Plan the Test
Firstly, Plan about our test. 


<img width="749" alt="Test Plan" src="https://github.com/user-attachments/assets/7fd9efb2-ac33-4bc6-afc7-b7a9a1d7190c" />




- #### Decide on the Number of Users 
  Determine how many users we’ll simulate for the test. That means how many people can access the website at the same time. Here, I test for 5 users. 



<img width="751" alt="ThreadGroup" src="https://github.com/user-attachments/assets/332e9cbc-cc83-49a9-9fe5-76dfd4566c09" />





- #### Write and Run Test Cases 
  Next, write the test cases based on our plan and run them to simulate real user activity on the website. 




<img width="753" alt="Write_And_Run_Test_Cases" src="https://github.com/user-attachments/assets/2020fdd4-bc0d-4e9c-9c64-9f1de38b2f83" />




### Output



- #### View Results Tree



The "View Results Tree" listener displays test results in a tree format. It provides detailed information for each individual request made during the test, including response data, status (pass/fail), response time, and more. This feature is especially useful for debugging, as it allows you to pinpoint which requests may have failed or taken longer than expected and also the results tree to see if the test was successful or not. For example, if the response time code is 200, it means everything worked as expected. 

<img width="753" alt="View Results Tree" src="https://github.com/user-attachments/assets/9d63acd4-7f9d-4fe8-a45d-4e147f0210a0" />









- #### Summary Report



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
Nowreen Islam - [Linkdin](https://www.linkedin.com/in/nowreen-islam/) 


## Reference


1. Target Website for Testing: [NopCommerce](https://test460.nop-station.com/en/)
2. JMeter User Manual: [Jmeter](https://jmeter.apache.org/usermanual/index.html)



## Mentor
Md. Al Foysal Rabbi - [LinkedIn](https://www.linkedin.com/in/foysal-rabbi-362039165/)

Designation: SQA Engineer II

Brain Station 23
