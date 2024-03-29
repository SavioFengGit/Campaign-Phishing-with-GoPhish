# Campaign-Phishing-with-GoPhish
This is an example of how to assess employee readiness for social engineering with the tool Gophish.<br>
I show only the important steps required to perform a campaign phishing. <br>
# Introduction of the tool
## GoPhish
GoPhish is an open-source tool that helps you test the vulnerability of your organization to phishing attacks.<br> 
Phishing is a type of cyberattack that tries to trick people into revealing sensitive information or installing malicious software by sending them deceptive emails. <br>
GoPhish allows you to create realistic phishing campaigns, send them to your employees or clients, and track the results in real time. You can also use GoPhish to train your staff on how to recognize and avoid phishing emails. <br>
GoPhish is designed for businesses and penetration testers who want to improve their security awareness and prevent data breaches.<br>
<br>
GoPhish makes you launch a Campaign in 3 steps:<br>
- Set Profiles, Landing pages, Templates & Targets
- Launch the Campaign Phishing
- Track Results


## Campaign Phishing with GoPhish <br>
Remember to save all the settings at every step.<br>
1. **Start the gophish server**.<br>
2. **Go to the URL and log in with the credentials**.<br><br>
<img src="login_panel.png" width=70% height="auto"><br>
3. **Set a New profile**. <br>
<img src="new_profile.png" width=50% height="auto"><br><br>
4. **Send a test email and check in your mailbox, you should receive the test email**.<br>
<img src="test_box.png" width=70% height="auto"><br><br>
5. **Set a New landing page, specify the page on import site, it's the page where they will be redirect when someone click your link, in my case localhost:8080, and remember to active the capture of submitted data and passwords**.<br>
<img src="new_landing_page.png" width=40% height="auto"> <img src="import_site.png" width=50% height="auto"><br><br>
6. **Set a New template, click on Import Email and paste the code of the email template (download an email template or create a custom one), this is a very important step, because you need to use hard social engineering for bait the target, don't worry to spend a lot of time to custom the email**.<br>
<img src="fake_email.png" width=50% height="auto"><br><br>
7. **Set a New Group with importing a file.csv, here it's where you set the targets, an example can be the employees of the company**.<br>
<img src="new_group.png" width=50% height="auto"><br><br>
**Example file CSV**. <br>
<img src="file_csv.png" width=30% height="auto"><br><br>
8. **Set a New Campaign and Launch it**.<br>
<img src="new_campaign.png" width=50% height="auto"><br><br>

 - **This screenshot is an example of the email that they will receive. If they will click on Reset Password, they will be redirect into localhost:8080 where there is my fake reset password page.** <br>
<img src="phishing_email.png" width=70% height="auto"><br>



#Author
<b>Xiao Li Savio Feng</b>
