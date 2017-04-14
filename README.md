# JavaMailSender
Sending a mail using Java mail

Sometimes the following error comes.
Exception in thread "main" javax.mail.AuthenticationFailedException:
....
....
534 5.7.14  https://support.google.com/mail/answer/78754 129sm4440754pgj.23 - gsmtp

	at com.sun.mail.smtp.SMTPTransport$Authenticator.authenticate(SMTPTransport.java:826)
	at com.sun.mail.smtp.SMTPTransport.authenticate(SMTPTransport.java:761)
	at com.sun.mail.smtp.SMTPTransport.protocolConnect(SMTPTransport.java:685)
	at javax.mail.Service.connect(Service.java:295)
	at javax.mail.Service.connect(Service.java:176)
	at com.codili.JavaEmail.sendEmail(JavaEmail.java:66)
	at com.codili.JavaEmail.main(JavaEmail.java:24)

Solution:
---
http://stackoverflow.com/a/32303988/2293534
