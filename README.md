# Phishing Analysis Blue Team Project

![](https://github.com/prakharvr02/Phishing-Analysis/blob/main/Phishing%20Analysis%20Images/1.webp)

# Phishing Analysis 2 Scenario
Put your phishing analysis skills to the test by triaging and collecting information about a recent phishing campaign.

![](https://github.com/prakharvr02/Phishing-Analysis/blob/main/Phishing%20Analysis%20Images/2.webp)

# Analysis Tools
We are going to use Thunderbird as our email client and to retrieve the email artifacts we will be using a text editor called Sublime Text.

1.Text Editor(Sublime Text)

2. Mozilla Thunderbird

3. CyberChef

To solve the Phishing Analysis 2 challenge we need to download the Phishing email and enter the password to access the files.

![](https://github.com/prakharvr02/Phishing-Analysis/blob/main/Phishing%20Analysis%20Images/3.webp)

# 1. What is the sending email address? (1 point)
When we open the email in Sublime Text, we can search for “From” using the Find tool (CTRL+F).

![](https://github.com/prakharvr02/Phishing-Analysis/blob/main/Phishing%20Analysis%20Images/4.webp)

Answer: amazon@zyevantoby.cn

# 2. What is the recipient email address? (1 point)

Using Sublime Text, we can search for “To” using the Find tool (CTRL+F).

![](https://github.com/prakharvr02/Phishing-Analysis/blob/main/Phishing%20Analysis%20Images/5.webp)

Answer: saintington73@outlook.com

# 3. What is the subject line of the email? (1 point)

For this question, we’ll search for the “Subject” field.

![](https://github.com/prakharvr02/Phishing-Analysis/blob/main/Phishing%20Analysis%20Images/6.webp)

Answer: Your Account has been locked

# 4. What company is the attacker trying to imitate? (1 point)

Based on the “from” address we can see the attacker is impersonating Amazon.

![](https://github.com/prakharvr02/Phishing-Analysis/blob/main/Phishing%20Analysis%20Images/7.webp)

Answer: Amazon

# 5. What is the date and time the email was sent? (As copied from a text editor) (1 point)

For this question, we’ll search for the “Date” field.

![](https://github.com/prakharvr02/Phishing-Analysis/blob/main/Phishing%20Analysis%20Images/8.webp)

Answer: Wed, 14 Jul 2021 01:40:32 +0900

6. What is the URL of the main call-to-action button? (1 point)

To get the hyperlinked malicious url from the Pishing email we need to right-click it and select “Copy Link Location” carefully. Kindly note there is a risk involved when using this method because you might open the malicious link accidentally. Alternatively, you can use a text editor.

![](https://github.com/prakharvr02/Phishing-Analysis/blob/main/Phishing%20Analysis%20Images/9.webp)

Answer: https://emea01.safelinks.protection.outlook.com/?url=https%3A%2F%2Famaozn.zzyuchengzhika.cn%2F%3Fmailtoken%3Dsaintington73%40outlook.com&data=04%7C01%7C%7C70072381ba6e49d1d12d08d94632811e%7C84df9e7fe9f640afb435aaaaaaaaaaaa%7C1%7C0%7C637618004988892053%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C1000&sdata=oPvTW08ASiViZTLfMECsvwDvguT6ODYKPQZNK3203m0%3D&reserved=0

# 7. Look at the URL using URL2PNG. What is the first sentence (heading) displayed on this site? (regardless of whether you think the site is malicious or not) (1 point)

![](https://github.com/prakharvr02/Phishing-Analysis/blob/main/Phishing%20Analysis%20Images/10.webp)

Answer: This web page could not be loaded.

# 8. When looking at the main body content in a text editor, what encoding scheme is used? (1 point)

For this question, we’ll search for the “Encoding” field.

![](https://github.com/prakharvr02/Phishing-Analysis/blob/main/Phishing%20Analysis%20Images/11.webp)

Answer: Base64

# 9. What is the URL used to retrieve the company’s logo in the email? (1 point)

For this question, we will copy the Base64 content and paste it into CyberChef for analysis as shown below.

![](https://github.com/prakharvr02/Phishing-Analysis/blob/main/Phishing%20Analysis%20Images/12.webp)

We will search for the “http” field in the Output section of CyberChef.

![](https://github.com/prakharvr02/Phishing-Analysis/blob/main/Phishing%20Analysis%20Images/13.webp)

Answer: https://images.squarespace-cdn.com/content/52e2b6d3e4b06446e8bf13ed/1500584238342-OX2L298XVSKF8AO6I3SV/amazon-logo?format=750w&amp;content-type=image%2Fpng

# 10. For some unknown reason one of the URLs contains a Facebook profile URL. What is the username (not necessarily the display name) of this account, based on the URL? (1 point)

For this question, We will search for the “facebook” field in the Output section of CyberChef.

![](https://github.com/prakharvr02/Phishing-Analysis/blob/main/Phishing%20Analysis%20Images/14.webp)

Answer: amir.boyka.7

