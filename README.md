# JMeter API & Performance Testing
## Description
This repository hosts JMeter test plans for two different API scenarios. The Booking API (booking.jmx) is intended for performance testing, including load testing and stress testing, to analyze the system's reliability and capacity.
## Prerequisites
- Apache JMeter for performance and functional testing
- Java (JDK 17) for running JMeter and tests
## How to run this project
- git clone https://github.com/rifat1896129/API_Load_Test_using_Jmeter.git 
- cd API_Load_Test_using_Jmeter 
## Running the Booking API Test (Performance Test)
### Procedures
- Open booking.jmx in JMeter.
- Run tests for 5, 10, and 20 minutes.
- Review the HTML report for the results.
- If the load test is successful, gradually increase the number of users to identify the bottleneck (stress test).
- Generate an HTML report and save results in API_load_and_Stress_test.xlsx.
## Results & Reports

#### For 5 min
![5](https://github.com/user-attachments/assets/8bfbaa95-d4d4-4a2d-8c62-de5aa55125b7)
![5_1](https://github.com/user-attachments/assets/f95830a9-0f4d-458d-b592-04278f9cfa2d)

#### For 10 min
![10](https://github.com/user-attachments/assets/4fdecd50-a89c-4b0d-9ace-39f902ecbf33)
![10_1](https://github.com/user-attachments/assets/7deab87b-ac6e-436d-a241-0e831927161a)

#### For 20 min
![20](https://github.com/user-attachments/assets/418d05f7-f7cb-410d-8dc0-2fc7d946af0c)
![20_1](https://github.com/user-attachments/assets/4b0bcd31-a5d7-4ab6-9e7f-ee6ab8016900)

#### Load API Result
![load](https://github.com/user-attachments/assets/12fcf5b3-07d7-49e9-a9d2-519b6f0d059a)
#### Stress Test Result
![Stress_test](https://github.com/user-attachments/assets/110966d3-84c2-44c5-b6c2-e168e8f143be)




