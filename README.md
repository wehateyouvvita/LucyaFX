# LucyaFX
LucyaFX is a fixed version of the original Lucya, a recreation of the current Lucya.

# Setup:

Install the Python 3.11.2 from the link below.

https://www.python.org/downloads/

**Make sure to install PATH. (Click the checkbox after starting the installer.)**

-------------------------------------------------------------------------------

Download and install XAMPP from ApacheFriends, link below.

https://www.apachefriends.org

Once downloaded, locate the "Apache" section and click "httpd.conf".

![image](https://user-images.githubusercontent.com/98233732/225140539-c2dff9de-da76-4515-ad78-56c4b40f5251.png)

Inside the file, press CNTRL+F, and search for "Listen 80"

![image](https://user-images.githubusercontent.com/98233732/225141488-c92c474d-bfd9-4c87-8829-47686af2bc79.png)

Once the string has been located, change the number to anything that you want, I chose 1337.

![image](https://user-images.githubusercontent.com/98233732/225141703-50181f5c-6a3c-4149-a8cb-76ae6c25444c.png)






Install the libraries: pip install -r requirements.txt
Setup a MYSQL database with the Lucya.sql file
Configure main.py to connect to your MYSQL database
Run the website: python3 main.py
