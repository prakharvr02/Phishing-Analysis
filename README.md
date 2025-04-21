# Phishing Analysis: Blue Team Project

![](https://github.com/prakharvr02/Phishing-Analysis/blob/main/Phishing%20Analysis%20Images/1.webp)

## Phishing Analysis Scenario  
Test your phishing analysis skills by triaging and investigating a recent phishing campaign.

![](https://github.com/prakharvr02/Phishing-Analysis/blob/main/Phishing%20Analysis%20Images/2.webp)

## Analysis Tools  
We will use the following tools:  
1. **Text Editor** (Sublime Text)  
2. **Mozilla Thunderbird** (Email client)  
3. **CyberChef** (Data decoding tool)  

To begin the challenge:  
1. Download the phishing email  
2. Enter the password to access the files  

![](https://github.com/prakharvr02/Phishing-Analysis/blob/main/Phishing%20Analysis%20Images/3.webp)

---

### 1. What is the sender's email address? (1 point)  
**Steps:**  
- Open the email in Sublime Text  
- Search for `From` using `CTRL+F`  

![](https://github.com/prakharvr02/Phishing-Analysis/blob/main/Phishing%20Analysis%20Images/4.webp)  

**Answer:** `amazon@zyevantoby.cn`  

---

### 2. What is the recipient's email address? (1 point)  
**Steps:**  
- Search for `To` in Sublime Text  

![](https://github.com/prakharvr02/Phishing-Analysis/blob/main/Phishing%20Analysis%20Images/5.webp)  

**Answer:** `saintington73@outlook.com`  

---

### 3. What is the subject line of the email? (1 point)  
**Steps:**  
- Search for the `Subject` field  

![](https://github.com/prakharvr02/Phishing-Analysis/blob/main/Phishing%20Analysis%20Images/6.webp)  

**Answer:** `Your Account has been locked`  

---

### 4. Which company is the attacker impersonating? (1 point)  
**Analysis:**  
The sender's address suggests the attacker is pretending to be Amazon.  

![](https://github.com/prakharvr02/Phishing-Analysis/blob/main/Phishing%20Analysis%20Images/7.webp)  

**Answer:** `Amazon`  

---

### 5. What is the date and time the email was sent? (Copy directly from the text editor) (1 point)  
**Steps:**  
- Search for the `Date` field  

![](https://github.com/prakharvr02/Phishing-Analysis/blob/main/Phishing%20Analysis%20Images/8.webp)  

**Answer:** `Wed, 14 Jul 2021 01:40:32 +0900`  

---

### 6. What is the URL of the main call-to-action button? (1 point)  
**Warning:** Exercise caution - this may be a malicious link  

**Steps:**  
- Right-click the button and select **Copy Link Location**  
- Alternatively, inspect the email source in Sublime Text  

![](https://github.com/prakharvr02/Phishing-Analysis/blob/main/Phishing%20Analysis%20Images/9.webp)  

**Answer:**  
```
https://emea01.safelinks.protection.outlook.com/?url=https%3A%2F%2Famaozn.zzyuchengzhika.cn%2F%3Fmailtoken%3Dsaintington73%40outlook.com&data=04%7C01%7C%7C70072381ba6e49d1d12d08d94632811e%7C84df9e7fe9f640afb435aaaaaaaaaaaa%7C1%7C0%7C637618004988892053%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C1000&sdata=oPvTW08ASiViZTLfMECsvwDvguT6ODYKPQZNK3203m0%3D&reserved=0
```


---

### 7. What is the first sentence (heading) displayed when viewing the URL with URL2PNG? (1 point)  

![](https://github.com/prakharvr02/Phishing-Analysis/blob/main/Phishing%20Analysis%20Images/10.webp)  

**Answer:** `This web page could not be loaded.`  

---

### 8. What encoding scheme is used in the main body content? (1 point)  
**Steps:**  
- Search for the `Content-Transfer-Encoding` field  

![](https://github.com/prakharvr02/Phishing-Analysis/blob/main/Phishing%20Analysis%20Images/11.webp)  

**Answer:** `Base64`  

---

### 9. What is the URL used to retrieve the company's logo in the email? (1 point)  
**Steps:**  
1. Copy the Base64 content  
2. Decode it in CyberChef  
3. Search for `http` in the output  

![](https://github.com/prakharvr02/Phishing-Analysis/blob/main/Phishing%20Analysis%20Images/12.webp)  
![](https://github.com/prakharvr02/Phishing-Analysis/blob/main/Phishing%20Analysis%20Images/13.webp)  

**Answer:**  
```
https://images.squarespace-cdn.com/content/52e2b6d3e4b06446e8bf13ed/1500584238342-OX2L298XVSKF8AO6I3SV/amazon-logo?format=750w&content-type=image%2Fpng
```


---

### 10. What Facebook username appears in one of the URLs? (1 point)  
**Steps:**  
- Search for `facebook` in the CyberChef output  

![](https://github.com/prakharvr02/Phishing-Analysis/blob/main/Phishing%20Analysis%20Images/14.webp)  

**Answer:** `amir.boyka.7`  
