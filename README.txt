1.	Login to slack workplace and create a new channel SNOW.
https://app.slack.com/client/TMRC6BZPW/C0188DCGTQB 
2.	From the homepage of Slack, go to API, create an APP, give name SNOW.
https://api.slack.com/ 
3.	Turn-on incoming Webhook.
4.	Add your channel to the Webhook and allow it. It will give a webhook url.
5.	Move to REST Message in SNOW instance.
6.	Create a Rest message, give the endpoint. Save
7.	Click on default GET and make it POST. Paste below sample message to request body ?              {"text":"${msg}"}
8.	Right click on the banner and click on “auto-generate variable”
9.	Enter the text value at the bottom.
10.	Click on test and a message will be delivered.
11.	 Create a business rule on the incident table. (Insert, advance ticked)
12.	 Go to POST Method of previous REST Message, pick the template js code from hyperlink.
Paste below in business rule.
