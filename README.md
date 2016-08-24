#Pikapy - Mass Pokemon Go Account Creator and ToS verifier
==============================================================


Description
-----------
Automatically creates Pokemon Trainer Club accounts, and reads the ToS making them usable after the recent Niantic patch.
Text files will be created in your current directory.

Far more superior fork of this (Has 2captcha support, and email verification, and is under active development):         

    https://github.com/sriyegna/pikaptcha

Requires pgoapi:
    
    pip install git+https://github.com/keyphact/pgoapi.git


Installation
------------
**Windows users**

Video guide:

https://www.youtube.com/watch?v=_wM6OX4GdNM

Install all the necessary prerequisites as listed here:

http://pgm.readthedocs.io/en/develop/basic-install/windows.html

You will also need to download the chromedriver.exe:

http://chromedriver.storage.googleapis.com/2.23/chromedriver_win32.zip

Unzip and paste the chromedriver.exe file in "C:\Python27\Scripts" Folder.

Finally, open up your command prompt and paste this command:

    pip install git+https://github.com/skvvv/pikapy

If you are still having troubles, you can join us at discord channel https://discord.gg/cnTmt

**Linux users/OSX**

(OSX prerequisites)Selenium support:

    brew install chromedriver
(Ubuntu and variants prerequisites)

    sudo apt-get install chromium-browser


(Everyone from this point)
From your terminal run::

    pip install git+https://github.com/skvvv/pikapy

If you have both python2 and python3 installed::

    pip2 install git+https://github.com/skvvv/pikapy

If given permission errors::

    sudo pip2 install git+https://github.com/skvvv/pikapy

Updating to the latest version
------------------------------

    pip install --upgrade git+https://github.com/skvvv/pikapy

Uninstalling
------------

    pip uninstall pikapy

Usage
-----
**Command line interface:**

After installing the package run 'pikapy' from the terminal to create a new accounts.
Optional parameters include *--username*, *--password*, *--email*, *--count*
Use *--help* for command line interface help.

usernames.txt file is created in the current working directory.

Example 1 (Create entirely random new account)::

    ~pikapy
    Created new account:
      Username:  traynagmoh
      Password:  rossstrubhep
      Email   :  fantsniskflast@gastsnub.com
      
Example 2 (Create 2 accounts with the same password)::

    ~pikapy -p password -c 2
    Created new account:
      Username:  trodbectflik
      Password:  password
      Email   :  prepsteptcruct@gastsnub.com
    Created new account:
      Username:  truzplospduv
      Password:  password
      Email   :  linkslampnob@gastsnub.com
      
Example 3 (Create a new account with specified parameters)::

    ~pikapy --username=mycustomusername --password=hunter2 --email=verifiable@lackmail.ru
    Created new account:
      Username:  mycusttruzplospduv:trodbectflikomusername
      Password:  hunter2
      Email   :  verifiable@lackmail.ru

Example 4 (Create a new account with mail using "plus trick")::

    ~pikapy -m myemail+@gmail.com
    Created new account:
      Username:  wongblofttez
      Password:  password
      Email   :  myemail+swuchdranflost@gmail.com
