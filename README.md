# jmeter-load-testing-of-dummy-customer-api

## Following API Used in this project

customer-test-api.herokuapp.com/customer/api/v1/login
customer-test-api.herokuapp.com/customer/api/v1/list
customer-test-api.herokuapp.com/customer/api/v1/get/101
customer-test-api.herokuapp.com/customer/api/v1/create

## How to run this file

1) clone this repo
2) open cmd or git bash from downloaded folder
3) run following command to generate report file along with log's csv file

<pre>
jmeter -n -t demo_customer_api_load_test.jmx -l log.csv -e -o Reports
</pre>

##Report file's screenshot

![image](https://user-images.githubusercontent.com/20879031/147299250-7b85d93b-b155-4951-9ed1-850050151600.png)

