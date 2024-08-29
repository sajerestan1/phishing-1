# phishing-1



## Project Report: Analysis of Phishing Email Techniques


### Introduction

Phishing emails are a common vector for cyber attacks, leveraging various social engineering tactics to deceive recipients into divulging sensitive information or executing malicious actions. This report analyzes a series of phishing email samples, highlighting the techniques used and providing insights into how these methods exploit human psychology to achieve their objectives.

### Phishing Email Samples and Techniques

#### Sample 1: Spoofed Email Address, URL Shortening, and HTML Impersonation

![image](https://github.com/user-attachments/assets/f918db87-0bc3-4749-bfb2-f93132c2663d)

![image](https://github.com/user-attachments/assets/5f87eaf8-f056-4816-a02b-a304ad77fa84)

![image](https://github.com/user-attachments/assets/fc448fa2-a4ca-425b-959e-a4b71d7ec0f2)

![image](https://github.com/user-attachments/assets/a8b381cb-82f2-47d6-96d4-65b8e42d96d8)

![image](https://github.com/user-attachments/assets/c1a4cddc-5ec4-4ea1-8ae2-9d84913f9ab6)

  #### Techniques:
  
  Spoofed Email Address: The sender's details appeared as service@paypal.com, but the actual email address was gibberish@sultanbogor.com, indicating a spoofed email.
  URL Shortening Services: The email contained shortened URLs, making it difficult for the recipient to verify the destination.
  HTML to Impersonate a Legitimate Brand: The email body was designed to look like a legitimate communication from PayPal, complete with branding and formatting.

  #### Observations:
  
  The email was designed to prompt the recipient to click on a "Cancel the order" button, playing on their fear of unauthorized transactions.
  Analysis of the raw HTML source revealed that the shortened URL redirected to an unexpected destination, which could lead to a phishing site or a malicious download.

### Sample 2: Spoofed Email Address, Pixel Tracking, and Link Manipulation

![image](https://github.com/user-attachments/assets/0826010b-26d4-4734-b009-7186317fe7f1)

![image](https://github.com/user-attachments/assets/c668ed25-31d6-41bd-a468-8817c3a8e204)

 #### Techniques:
 
  Spoofed Email Address: The email was crafted to appear as though it was sent from a legitimate mail distribution center.
  Pixel Tracking: An image named "Tracking.png" was embedded in the email, used for tracking whether the email was opened.
  Link Manipulation: The link in the email body appeared to relate to a tracking number but was actually pointing to a malicious domain.

 #### Observations:
 
  Yahoo's email client blocked the images from loading, which prevented the tracking pixel from functioning.
  The link was disabled, preventing a simple hover-over check to reveal the true destination, emphasizing the need to inspect raw HTML source code for verification.

Sample 3: Urgency, HTML Impersonation, Link Manipulation, and Credential Harvesting

![image](https://github.com/user-attachments/assets/c8d04ac8-7724-46a3-b43e-35972fa9e78e)

![image](https://github.com/user-attachments/assets/75c9f7d3-d941-49bb-8653-387b5619cee6)

![image](https://github.com/user-attachments/assets/4794b28e-2c2a-43f3-aa85-f6a5b5b8ce26)

![image](https://github.com/user-attachments/assets/506ed62e-9cf5-4ba6-880c-df6a6a43e1b5)

![image](https://github.com/user-attachments/assets/89784135-10c6-44ce-9b83-ef3e7cd9086a)

  #### Techniques:
  
  Urgency: The email introduced a sense of urgency by stating that a fax document was set to expire the same day.
  HTML to Impersonate a Legitimate Brand: The email redirected the recipient to a page designed to look like OneDrive and then to another page mimicking Adobe.
  Link Manipulation: The URLs in the email body were unrelated to Microsoft or Adobe, despite appearances.
  Credential Harvesting: The email prompted the victim to enter credentials to access the fake fax document, which would be harvested by the attackers.

  #### Observations:
  
  The recipient was led through a series of fake login pages, each designed to look legitimate but with URLs that were clearly not associated with the actual brands.
  Grammatical errors in the fake pages and URL inconsistencies were key indicators of the phishing attempt.

### Sample 4: Spoofed Email Address, Urgency, HTML Impersonation, and Attachments

  #### Techniques:

  ![image](https://github.com/user-attachments/assets/8d5b5e09-796a-4f13-aea3-696007a4b651)

![image](https://github.com/user-attachments/assets/e8f53c77-d55e-4de5-9c7d-67a6f912f30c)

![image](https://github.com/user-attachments/assets/1f5de888-4afe-4817-8100-581701d57d2a)


  Spoofed Email Address: The email was made to appear as though it was from Netflix Billing, but the sender's address was "z99@musacombi.online."
  
  Urgency: The email claimed that the recipient's account was suspended, urging immediate action.
  HTML to Impersonate a Legitimate Brand: The email body was formatted to look like a Netflix communication.
  Attachments: The email included a PDF attachment, which contained an embedded link for updating payment information.

#### Observations:

  The attachment's link pointed to a suspicious website, not related to Netflix, suggesting that it was designed to harvest payment credentials.
  The email also contained an unusual phone number and inconsistent spellings of the word "Netflix," which are red flags for phishing.

### Sample 5: Spoofed Email Address, BCCed Recipient, Urgency, and Attachments

  #### Techniques:

  ![image](https://github.com/user-attachments/assets/9328cf18-c5a4-4c45-820c-4a7018fd4531)

![image](https://github.com/user-attachments/assets/811d8813-3e47-4911-9d37-75bd55a580a6)

![image](https://github.com/user-attachments/assets/07a74c6d-3615-4814-bb85-6e364471727d)

  Spoofed Email Address: The email appeared to be from Apple Support, but the sender’s address was "gibberish@sumpremed.com."
  Recipient is BCCed: The email was BCCed to the recipient, making it difficult to trace and adding to its suspicious nature.
  
  Urgency: The email demanded immediate action, playing on the fear of account issues.
  Attachments: The email contained a .DOT file, a Microsoft Word template, which opened to reveal what appeared to be an App Store receipt with embedded links.

  #### Observations:
  
  The .DOT file contained a large image resembling an App Store receipt, with links that included keywords related to Apple but pointed to non-Apple domains.
  The blank email body and unusual file type were clear indicators of a phishing attempt.

Sample 6: Spoofed Email Address, HTML Impersonation, and Attachments

![image](https://github.com/user-attachments/assets/f844d116-dc9b-4c66-8b1d-56e4f89c2e85)

![image](https://github.com/user-attachments/assets/e6756bda-67b2-4347-ad8b-173a088caf6a)

![image](https://github.com/user-attachments/assets/d5625b5a-cef2-4bf6-b589-f09a1c0c8124)

![image](https://github.com/user-attachments/assets/f221f43a-6c7f-4d8c-93bd-d366aabbcbb8)

![image](https://github.com/user-attachments/assets/aa388419-cc16-4248-878c-9a3e5a816583)

![image](https://github.com/user-attachments/assets/a98cef21-0688-481c-ae12-c2c174edeebb)


  #### Techniques:
        
  Spoofed Email Address: The email claimed to be from DHL but came from an unrelated sender address.
  HTML to Impersonate a Legitimate Brand: The email body was designed to mimic DHL’s branding, with a subject line suggesting a package shipment.
  Attachments: The email contained an Excel document as an attachment, which ran a payload upon opening.

  #### Observations:
  
  The email lacked a valid destination URL for the web page link, making the attachment the primary interaction point.
  Opening the attachment triggered a payload that resulted in an error message, which could potentially indicate a failed malware execution.


### Benefits and Experience Gained

#### Increased Awareness of Phishing Techniques

Through the analysis of these phishing emails, I have gained a deeper understanding of the various tactics used by cybercriminals to deceive victims. This includes recognizing the signs of spoofed email addresses, the use of urgency to pressure recipients, and how HTML can be manipulated to mimic legitimate brands.

#### Improved Ability to Detect Malicious Content

The project has enhanced my ability to detect malicious content in emails, particularly in identifying manipulated links, embedded tracking pixels, and suspicious attachments. By examining the raw HTML source code, I have learned to uncover hidden red flags that may not be immediately visible.

#### Practical Experience in Phishing Analysis

This project provided practical experience in analyzing real-world phishing scenarios, improving my skills in identifying and documenting phishing techniques. I also gained experience in understanding how different elements of a phishing email work together to create a convincing attack.

#### Enhanced Reporting Skills

Documenting the findings from this analysis has improved my ability to create detailed and informative reports, which is a critical skill in cybersecurity. I learned how to structure and present the information in a way that is both comprehensive and accessible, ensuring that key insights are communicated effectively.

#### Preparedness for Future Cybersecurity Challenges

The experience gained from this project has better prepared me to face future cybersecurity challenges, particularly those related to phishing and social engineering attacks. By understanding the tactics used by attackers, I am now more equipped to anticipate and respond to similar threats in a professional setting.

This report not only consolidates the key observations and techniques used in the phishing emails but also reflects on the valuable experience and knowledge gained throughout the project. This will serve as a strong foundation for continued growth in cybersecurity and a reference for future analysis and awareness efforts.


### Conclusion

The phishing email samples analyzed in this report demonstrate the wide variety of techniques attackers use to deceive recipients. From spoofed email addresses to cleverly crafted HTML designed to mimic legitimate brands, these emails exploit trust and urgency to manipulate victims into compromising their security. Awareness and training are essential in recognizing and avoiding these threats, as phishing remains a prevalent and evolving danger in the digital landscape.
