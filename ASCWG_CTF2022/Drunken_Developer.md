# Challenge Title: Drunken Developer 

## Level: Warm up

## Point: 100

## Description
Developer have to disable his personal things
 
Flag must start with ASCWG❴...answer❵


[Link](http://104.154.142.159:5454/)

## Solution

1) I viewed the website and the source page.

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/developer/login.png)

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/developer/source.png)

When I saw the source page, I noticed that the admin forgot his email and that he was using a temporary email.
Which makes it easier to try to make an email similar to that so that any message you receive will be sent to the hacker.

2) I searched for vistaemail.com and found that site that helps generate an email similar to an admin to receive the same emails.

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/developer/tempmail.png)

3) Create same email form from this site (temporary mail id).

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/developer/2022-createmail.png)

4) The first thing you do is reset the password by sending the administrator's email, you will receive a message on the fake email.

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/developer/reset1.png)

5) Now check my email box.

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/developer/receivemail.png)

6) Once you click here, go to the set password page and set a new password.

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/developer/setnewpass.png)

7) I went to the login page and enter the email and the new password that you entered on the password-setting page, and then I found the flag.

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/developer/flag.png)

