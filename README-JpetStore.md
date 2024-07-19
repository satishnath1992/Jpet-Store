
# Jpet Store

<img width="944" alt="Title Image" src="https://github.com/user-attachments/assets/f9e0553b-1c3c-49f9-bf7e-5b5b28a1467c">

Jpet Store is an online websitr in the US. Where people can shop their favouritre pets in the website from comfort of their home and the pets will be delivered to their adresses.
There are 5 different category of pets are available in the website like Fish,Dogs,Reptiles,Cats and Birds.




## About the Project



There is a requirement to test the performance of latest build the of this application to check the readiness of the application before deploying it to to production.
## Features

This application is based on 5 Modules.Each module carries a specific type of Pet.Below are the 5 modules
- Fish
- Dogs
- Reptiles
- Cats
- Birds


## Pre-Requisites

- Need to download Jmeter 

- Java 8 or above should be installed in the laptop or desktop.


## Application URL

Link to Website

https://jpetstore.aspectran.com/
## Instruction to Run the Test

- Copy the repository to your local system.

- You will find the test scripts in "Scripts" folder.

- And the Load test scenario in "Scenario" folder.

- You will find the required test data in "Test Data" folder.

- If you want to run any single module script alone then open the scripts from the "Scripts" folder.

- You need to set the test data Filename location in the "CSV Data Set Config" element in the script.The default location was set according to my convinience.You can set yours and run the script.

- If you want to run the Load Test.You need to open the "JpetStore_Scenario_LoadTest.jmx" in the "Scenario" folder.

- You need to set the test data Filename location in the "CSV Data Set Config" element in each of the 5 modules script of the scenario.

- Once you have done with the set up.You can run the test.


## Running Tests

To run the tests in Non-GUI mode,run the following command

```bash
  jmeter -n -t [jmx file] -l [results file] -e -o [Path to web report folder]
```



# Hi, I'm Satish! 👋




If you like my work.Give me a Thumbs Up.

Thanks
