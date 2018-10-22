Predicting stock prices from Yahoo stock screener using scikit-learn and sending the predicitons via smtplib to a phone number. 

Imports needed:

1. [numpy](https://pypi.org/project/numpy/)
2. datetime
3. smtplib
4. time
5. [selenium](https://pypi.org/project/selenium/)
6. [sklearn](https://pypi.org/project/scikit-learn/)
7. [iexfinance](https://pypi.org/project/iexfinance/)


You will also need to download the chromedriver so selenium can work properly. It can be downloaded [here](https://sites.google.com/a/chromium.org/chromedriver/) and then place the path to the driver in the code:

    driver = webdriver.Chrome('PATH TO CHROME DRIVER')

In order to send the SMS message of the prediction you will need to enter your email username and password along with the number you wish to send the predictions to. Here are some popular domain's for phone carriers:

- AT&T: number@txt.att.net (SMS), number@mms.att.net (MMS)
- T-Mobile: number@tmomail.net (SMS & MMS)
- Verizon: number@vtext.com (SMS), number@vzwpix.com (MMS)
- Sprint: number@messaging.sprintpcs.com (SMS), number@pm.sprint.com (MMS)
- Virgin Mobile: number@vmobl.com (SMS), number@vmpix.com (MMS)

A full list of domains for phone carriers can be found [here](https://20somethingfinance.com/how-to-send-text-messages-sms-via-email-for-free/)
