### What is it?

**cool-odd** is a Python implementaton of email autmation integrated with chatgpt using imap (Internet Mail Access Protocol) and email module. Where you'll be able to select few particular mail address from which you can choose the read the unseen mails and from that body part chatgpt will write blog/news/post as per your requirements. 

<br>

  
<p><pre align="center">
<strong>Watch a video demo : </strong> <a href="https://www.youtube.com/channel/UCX7oe66V8zyFpAJyMfPL9VA">​YouTube​</a></pre></p>

<br>

### Requirements 

- [x] 2-step verification in google account (target email) - [Link](https://myaccount.google.com/signinoptions/two-step-verification/enroll-welcome)
- [x] share the `app password` (for google's security reasons) 
- [x] turn on 'status : IMAP' from mail settings under : `Forwarding and POP/IMAP` - [Link](https://mail.google.com/mail/u/0/#settings/fwdandpop)

### Features

- ✒️ automating blogs/news writing as soon as you get an mail
- ⭐ ask chatbot to do custom work on the bases of the mail
- 📟 complete access to your mail and automate (title, body, time, sender, number of sender)
- ⚙️ fully customized attributes depending on the requirements

### Input Attributes 

- **how_many :** how many unseen mails you want to check (default : 10)
- **maxtoken :** what is the maximum number of charecters you want in your blog (default : 200 characters)
- **what_to_ask :** what do you want to ask chatgpt to do (default : write an blog about)
- **num_target :** number of targeted emails (default : None)
