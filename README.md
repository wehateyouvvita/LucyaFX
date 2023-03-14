# LucyaFX
LucyaFX is a fixed version of the original Lucya, a recreation of the current Lucya.

# Setup:

Install the Python 3.11.2 from the link [here](https://www.python.org/downloads/).

**Make sure to install PATH. (Click the checkbox after starting the installer.)**

![image](https://user-images.githubusercontent.com/98233732/225142849-303e312e-7c21-4789-a976-8318574ce1b5.png)

After this, continue with the installation like normal.

-------------------------------------------------------------------------------

Download and install XAMPP from ApacheFriends, at [this](https://www.apachefriends.org) link.

Once downloaded, locate the "Apache" section and click "httpd.conf".

![image](https://user-images.githubusercontent.com/98233732/225140539-c2dff9de-da76-4515-ad78-56c4b40f5251.png)

Inside the file, press CNTRL+F, and search for ```Listen 80```

![image](https://user-images.githubusercontent.com/98233732/225141488-c92c474d-bfd9-4c87-8829-47686af2bc79.png)

Once the string has been located, change the number to anything that you want, I chose 1337.

![image](https://user-images.githubusercontent.com/98233732/225141703-50181f5c-6a3c-4149-a8cb-76ae6c25444c.png)

Now save the changes and close the window.

-------------------------------------------------------------------------------

Now, open RUN. You can do this by either right clicking the start button, and then run, or just searching it up in Windows Search.

![image](https://user-images.githubusercontent.com/98233732/225143627-a56cf3fe-859f-43a6-980d-687dd6b0ff53.png)

Input ```C:\Windows\System32\drivers\etc``` into the window.

![image](https://user-images.githubusercontent.com/98233732/225143802-18cac579-39f5-42bf-a55a-af7bb7934035.png)

Click "OK".

It will take you to a window that looks like this. 

![image](https://user-images.githubusercontent.com/98233732/225144070-7f690a36-b1f3-45d6-bb3a-11826e0c18ed.png)

Copy the file location for the "hosts" file and then open Notepad as administrator.

![image](https://user-images.githubusercontent.com/98233732/225144397-2030ebb6-04e4-4fbe-87ce-cd29d7ec76c2.png)

Press "File > Open" and paste in the location.

![image](https://user-images.githubusercontent.com/98233732/225144715-c61b7858-9114-4801-a71b-bc8788b6e765.png)

Once the file is open, add your localhost domain like this:

```127.0.0.1   roblox.local roblox.test ```

![image](https://user-images.githubusercontent.com/98233732/225144883-584ffa44-5ce9-4bf5-88df-9aeacd77adea.png)

You may name the domains anything. I just named them ROBLOX for the purpose of this website. Make sure they are either ".local" or ".test" though.

After this, make sure to save the notes file via "File > Save".

Once all of this is done, feel free to close all windows apart from XAMPP.

-------------------------------------------------------------------------------

Now, download all the files from this repository and extract them to a folder located on the desktop.

![image](https://user-images.githubusercontent.com/98233732/225146605-958885db-80a2-4b96-8050-f92e9d64cbd4.png)

Press the bar at the top showing the file location and type in ```cmd ```

![image](https://user-images.githubusercontent.com/98233732/225146786-574c3dc3-9d21-4605-9940-11e9db38a347.png)

Next, install the libraries and dependencies by typing ```
pip install -r requirements.txt ```

If any problems occur, make sure to install the latest versions of the packages, and you can do this via finding tutorials online. I will not go over that in this README.

-------------------------------------------------------------------------------

Next, open XAMPP again.

Start Apache and MySQL by clicking the "Start" button. You can't miss it...

![image](https://user-images.githubusercontent.com/98233732/225148551-d1d4e94e-b006-45bd-8ce8-44346b36b6ab.png)

Make sure they are running, and then click "Admin" on the MySQL row.

![image](https://user-images.githubusercontent.com/98233732/225148639-0b702b8c-0513-4df6-94ae-0d3ef56628cd.png)




Setup a MYSQL database with the Lucya.sql file
Configure main.py to connect to your MYSQL database
Run the website: python3 main.py
