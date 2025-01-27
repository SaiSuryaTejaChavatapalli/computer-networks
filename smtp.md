# SMTP:

⇒ For executing the functionality of email, SMTP (Simple Mail Transfer protocol) is used.

⇒ One more protocol named POP3 is used in combination with SMTP, one is used to send emails another is used to receive emails.

⇒ SMTP also used TCP protocol from transport layer.

⇒ Connection for SMTP is setup on PORT 25.

⇒ Mail clients give the actual UI for end users to send and receive emails Ex: Gmail, Outlook.

### How SMTP Works?

⇒ When an email is sent, it is sent to the senders SMTP server using SMTP protocol.

( Also the SMTP server is configured in the mail clients)

⇒ The SMTP Server places the email on a message queue.

⇒ Then SMTP Server initiates a connection with receivers SMTP server and conducts an initial SMTP handshake.

⇒ Then finally it sends the email to recipients SMTP Server.

⇒ The email is downloads from receivers SMTP server and client shows the mail.

SMTP→ Push Protocol (Send the email)

POP3 → Pull Protocol (Download the email)

⇒ If recipients SMTP server is offline, the sender SMTP server tries again and again after some delta time (minutes), If there is a set threshold after which it stops sending the email and marks it not delivered.

![image.png](attachment:cb8f25ee-0ea5-4fda-8358-7b691da80dbf:image.png)

.
