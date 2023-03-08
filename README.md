# JMeter
Recording performance test script using blazemeter plugin on Chrome browser.

This repo is a performance testing project to test the https://blazedemo.com/index.php website by reserving and making payment to a flight. The steps is as below:

1. Navigate to BlazeDemo website
2. Choose Departure City & Destination City > Click [Find Flights]
3. Choose flight No 43
4. Input the required details > Click [Purchase Flight]

I have also integrate this jmx script with a csv data file so that JMeter may run through multiple iterations to test out all the combinations of Departure City & Destination City when reserving for the flight.
