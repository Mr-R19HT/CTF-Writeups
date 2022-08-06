# Challenge Title:  Evil Volunteer 

## Level: Medium

## Point: 600

## Description
The fox is guarding the hen house

Flag must start with ASCWG❴...answer❵

[Link](http://104.154.142.159:60002/index.php)

## Solution

1) I viewed the website and the source page but the source page was normal.

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/evil/website.png)

2) I registered a name and password, and then I logged in. The first time I entered, I noticed that it was asking me to upload a file, so I think it was a file upload vulnerbility.

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/evil/fileupload.png)

3) Now take a look at the source page, I noticed the file format that the site accepts.

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/evil/source.png)

4) I inserted the payload in the image to load cmd to get me talking to the website to get the flag. I used exiftool to achieve this.

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/evil/exiftool.png)

5) Change extention

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/evil/change%20extention.png)


6) I uploaded the file and intercepted it by burp and then using a repeater.

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/evil/upload.png)

uploaded successfully.

7) I rendered the image and ignore the handle in the url to see the response unencoded and then do ls for the content of the list.

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/evil/cmd.png)

8) I read flag.php .

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/evil/cat.png)

9) I viewed source page to get the flag.

![alt text](https://github.com/Mr-R19HT/CTF-Writeups/blob/main/ASCWG_CTF2022/images/evil/flag.png)








