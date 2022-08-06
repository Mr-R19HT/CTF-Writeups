# Challenge Title:  Evil Volunteer 

## Level: Medium

## Description
The fox is guarding the hen house

Flag must start with ASCWG❴...answer❵

[Link](http://104.154.142.159:60002/index.php)

## Solution

1) I show website and view source page but source page is normal

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/evil/website.png)

2) regsiter and login when do that, i notice to upload file now i think file upload vulnerability

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/evil/fileupload.png)

3) now show source page for last page, i show accept-files

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/evil/source.png)

4) i insert payload in image to upload cmd to make me talk with website to get the flag. i used exiftool to make that

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/evil/exiftool.png)

5) change extention

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/evil/change%20extention.png)


6) upload file and intercept that by burp then use repeater

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/evil/upload.png)

upload is success

7) view image and ignore handle in url to show response without encode then make ls to list content

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/evil/cmd.png)

8) read flag.php

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/evil/cat.png)

9) view source page to get the flag

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/evil/flag.png)








