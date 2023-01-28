# Dmoney API Jmeter

## Technology and Tool Used
- Apache JMeter
- Java

## Requests
1. Login to user
2. Create a new agent
3. Give balance to the newly created agent from system
4. Create a customer
5. Search the newly created user by phone number
6. Deposit balance to the customer from the agent
7. Withdraw some money from the agent
8. Delete the user

## How to run this project
- clone this project
- copy the DmoneyAPI.jmx file into bin folder of installed location of Jmeter
- open the DmoneyAPI.jmx file with jemeter & run the project
- to Generate report on the command prompt, delete the already copied .csv file and Report folder from the project if u or create a Report Folder
- hit the following command:

```ruby
jmeter -n -t DmoneyAPI.jmx -l dmoneyAPI.csv -e -o Reports
```

## Prerequisite
- Jmeter and Java must be installed

## Generated Html Report
![jmeter1](https://user-images.githubusercontent.com/58912515/215279120-4eb97d74-059d-487e-917b-30caa4733596.png)
![jmeter2](https://user-images.githubusercontent.com/58912515/215279126-6b785914-7bc6-4889-acc9-42058f7ac4b0.png)

## Summary Report
![jmeter3](https://user-images.githubusercontent.com/58912515/215279129-7c02ad6c-1bb2-472c-9da5-af57c280adb6.png)

