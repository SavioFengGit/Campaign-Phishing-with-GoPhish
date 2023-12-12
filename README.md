# Campaign-Phishing-with-GoPhish
I show the important steps required to perform a campaign phishing. <br>
# Introduction of the tool
## GoPhish
GoPhish is an open-source tool that helps you test the vulnerability of your organization to phishing attacks.<br> 
Phishing is a type of cyberattack that tries to trick people into revealing sensitive information or installing malicious software by sending them deceptive emails. <br>
GoPhish allows you to create realistic phishing campaigns, send them to your employees or clients, and track the results in real time. You can also use GoPhish to train your staff on how to recognize and avoid phishing emails. <br>
GoPhish is designed for businesses and penetration testers who want to improve their security awareness and prevent data breaches.<br>
<br>
GoPhish makes you launch a Campaign in 3 steps:<br>
- Set Templates & Targets
- Launch the Campaign
- Track Results
<br>

## Campaign Phishing with GoPhish <br>
Remember to save all the settings at every step.<br>
1) Start the gophish server<br>
2) Go to the URL and log in with the credentials<br>
3) Set a New profile like the screenshot<br>
4) Send a test email and check in your mailbox, u should to receive the test email<br>
5) Set a New landing page (specify the page where they will be redirect when click your link, in my case localhost:8080), active the capture of sumbitted data and passwords<br>
6) Set a New template, click on Import Email and paste the code of the email template (download a email template or create a custom)<br>
7) Set a New Group with importing a file.csv<br>
8) Set a New Campaign and Launch it<br>
