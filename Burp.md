# Setting up Burpsuite

Kali Linux comes with burpsuite but in case you dont have it installed, feel free to download it from here: https://portswigger.net/burp/communitydownload

Once burpsuite is installed follow the following steps to congifure proxy and start capturing the request.

1. Start Burpsuite
2. Go to firefox and download this extension: https://addons.mozilla.org/en-US/firefox/addon/foxyproxy-standard/

![image](https://github.com/0xParth/API_Labs/assets/86850255/8acecaf0-546c-43ca-b107-209c33be384e)

3. Click on foxyproxy, go to option, click on add and enter following details. Click on save.
![image](https://github.com/0xParth/API_Labs/assets/86850255/78713645-18ba-4d15-979b-716cebc721cb)

4. Click on foxyproxy icon again and select burpsuite.

![image](https://github.com/0xParth/API_Labs/assets/86850255/f15637fa-20b3-4d07-a82e-148e9d52b892)

# Adding ceritificate to Browser

1. With burpsuite open, visit http://burp in your browser.
![image](https://github.com/0xParth/API_Labs/assets/86850255/dcf2ba74-5abb-4a5d-9340-482d61aebec9)

2. Click on CA Certificate and download the cer file.
3. Once downloaded, open firefox settings and search "certi" in search box. Click on "View Certificate".
4. Click on import button to import certificate you downloaded. Make sure to check 2 boxes.
![image](https://github.com/0xParth/API_Labs/assets/86850255/a639f31f-c822-4c64-a4c4-7ec1a02db1a6)

5. Click on ok and you are good to go.

# Capturing first request
1. Go to burpuite, click on Proxy tab and turn on the intercept.
2. Visit any link of your choice in your browser and check burpsuite again. You will see the captured request.
![image](https://github.com/0xParth/API_Labs/assets/86850255/47421078-05f1-40b8-b244-43355b7db1b7)
