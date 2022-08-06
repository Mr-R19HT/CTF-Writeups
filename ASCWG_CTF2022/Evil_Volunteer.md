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


