# Challenge Title:  Konan 

## Level: Easy

## Point: 300

## Description
change yourself

Flag must start with ASCWG❴...answer❵

[Link](http://34.68.152.81:60003/)

## Solution

1) I saw the website and tried to enter with the highest privildge.

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/otp/login.png)

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/otp/phase1.png)

i intercept request by burp

2) once forward the request, i go to otp code page.

OTP means One Time Password: it’s a temporary, secure PIN-code sent to you via SMS or e-mail that is valid only for one session. Smart-ID uses OTPs during registration and account renewal to confirm your contact information.

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/otp/otpcode.png)

3) intercept otp page request and forward it to see response 

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/otp/phase2.png)

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/otp/intercept%20response.png)

do intercept response

4) change response and forward 

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/otp/change%20response.png)

5) bingooo i get the flag

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/otp/flag.png)


