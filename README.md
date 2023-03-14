# LucyaFX
LucyaFX is a fixed version of the original Lucya, a recreation of the current Lucya.

# Setup:

Install the Python 3.11.2 from the link below.

https://www.python.org/downloads/

**Make sure to install PATH. (Click the checkbox after starting the installer.)**

![image](https://user-images.githubusercontent.com/98233732/225142849-303e312e-7c21-4789-a976-8318574ce1b5.png)

After this, continue with the installation like normal.

-------------------------------------------------------------------------------

Download and install XAMPP from ApacheFriends, link below.

https://www.apachefriends.org

Once downloaded, locate the "Apache" section and click "httpd.conf".

![image](https://user-images.githubusercontent.com/98233732/225140539-c2dff9de-da76-4515-ad78-56c4b40f5251.png)

Inside the file, press CNTRL+F, and search for "Listen 80"

![image](https://user-images.githubusercontent.com/98233732/225141488-c92c474d-bfd9-4c87-8829-47686af2bc79.png)

Once the string has been located, change the number to anything that you want, I chose 1337.

![image](https://user-images.githubusercontent.com/98233732/225141703-50181f5c-6a3c-4149-a8cb-76ae6c25444c.png)

Now save the changes and close the window.

-------------------------------------------------------------------------------

Now, open RUN. You can do this by either right clicking the start button, and then run, or just searching it up in Windows Search.

![image](https://user-images.githubusercontent.com/98233732/225143627-a56cf3fe-859f-43a6-980d-687dd6b0ff53.png)

Input "C:\Windows\System32\drivers\etc" into the window.

![image](https://user-images.githubusercontent.com/98233732/225143802-18cac579-39f5-42bf-a55a-af7bb7934035.png)

Click "OK".

It will take you to a window that looks like this. 

![image](https://user-images.githubusercontent.com/98233732/225144070-7f690a36-b1f3-45d6-bb3a-11826e0c18ed.png)

Copy the file location for the "hosts" file and then open Notepad as administrator.

![image](https://user-images.githubusercontent.com/98233732/225144397-2030ebb6-04e4-4fbe-87ce-cd29d7ec76c2.png)

Press "File > Open" and paste in the location.

![image](https://user-images.githubusercontent.com/98233732/225144715-c61b7858-9114-4801-a71b-bc8788b6e765.png)

Once the file is open, add your localhost domain like this:

127.0.0.1   roblox.local roblox.test

![image](https://user-images.githubusercontent.com/98233732/225144883-584ffa44-5ce9-4bf5-88df-9aeacd77adea.png)

You may name the domains anything. I just named them ROBLOX for the purpose of this website. Make sure they are either ".local" or ".test" though.

After this, make sure to save the notes file via "File > Save".



Install the libraries: pip install -r requirements.txt
Setup a MYSQL database with the Lucya.sql file
Configure main.py to connect to your MYSQL database
Run the website: python3 main.py
