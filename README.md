# Phishing Analysis

## Phishing Case

Your colleagues have provided you with emails in `.eml` format. These `.eml` files are individual email files stored in **Multipurpose Internet Mail Extensions (MIME)** format. To scan `.eml` emails, you can use tools such as email clients (Outlook, Thunderbird, etc.), email viewing applications, or specialized tools like email scanners.

---

## Steps to Analyze an `.eml` File

1. **Open the `.eml` File**  
   - Use an email client or email viewing application to open the `.eml` file.  
   - Alternatively, open the `.eml` file with a text editor to view its source code.

2. **Inspect Email Headers**  
   - Check the headers to identify details such as the sender, recipient, date, and subject.  
   - Look for additional information like mail servers involved in the transmission of the message.

3. **Analyze Email Content**  
   - Examine the email content for signs of phishing, such as suspicious links or requests for sensitive data.

4. **Check Attachments**  
   - Inspect attachments for malicious files, such as those containing macros or scripts.

5. **Use Email Analysis Tools**  
   - Utilize tools to extract additional information from the email, such as IP addresses of email servers or other headers.

---

## Report Requirements

In your analysis report, answer the following questions:

1. **What is the email's timestamp?**  
2. **Who is the email from?**  
3. **What is the sender's email address?**  
4. **What email address will receive a reply to this email?**  
5. **What brand was this email tailored to impersonate?**  
6. **What is the originating IP?** (Defang the IP address.)  
7. **What do you think will be a domain of interest?** (Defang the domain.)  
8. **What is the shortened URL?** (Defang the URL.)  
9. **Do you think this is a phishing email?**  

---

## Note

When analyzing `.eml` files, always prioritize security by working in a controlled environment. Do not interact with suspicious links or attachments unless they are opened in a sandboxed environment.
