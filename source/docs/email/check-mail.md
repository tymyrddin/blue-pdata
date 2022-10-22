# Detecting fake emails and phishing

## Fake emails

* View the header info. Pay attention to the email address of a sender. It may imitate a legitimate sender. With only few characters altered or omitted, cybercriminals will often use an email address that closely resembles one from a reputable source.
* Look closely at the content:
  * Hover your cursor over any links in the body of an email. Links not matching the text that appears raise a red flag. So does the use of URL shortening services. Email clients can be viewed in simple text instead of html, so one never forgets to do this. 
  * Poor grammar and sentence structure, misspellings, and inconsistent formatting can be other indicators of a possible phishing attempt.
  * An unsolicited email requesting a user download and open an attachment is a common delivery mechanism for malware, even when it seems to come from a friend, or an employeur. 
  * A false sense of urgency or importance to help persuade a user to download or open an attachment without examining it first, completes this picture. Do not.
* Verify message source.
* Check the reply email.
* Reply and wait for the result.

## Phishing

* Be wary of emails asking for confidential information.
* Don't get pressured into providing sensitive information. Phishers like to use all kinds of social engineering. Learn what you can about it.
* Check a website's privacy policy, especially whether it will or will not sell its mailing list. If so, do not register.
* Watch out for generic-looking requests for information.
* Never submit confidential information via forms embedded within email messages.
* Never use links in an email to connect to a website unless you are absolutely sure they are authentic.

## View header information
To view the header information of an email message, select the message, then click on some menu to view all headers. 
* The `Return-path` is allegedly the e-mail address of the sender, although that is not a reliable method for identifying the sender because most adversaries use any return e-mail address that they can find on for the purpose created lists.
* The `Received` line is a bit more reliable, because that contains the IP address of the location from where the message was sent. That is, of course, unless an adversary hacked into an e-mail server or is using a relay server to disguise the true source of the message.
