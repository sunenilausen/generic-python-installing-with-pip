If Python 3 or IDLE isnt installed on you computer, follow the instructions below for your operating system.

### Microsoft Windows

On Microsoft Windows, your first step is to open up your web browser and navigate to [www.python.org/downloads.](https://www.python.org/downloads)

On the web page that opens up you will see a button to install the latest version of Python 3. Clicking this button will download an executable file. Click on the `.exe` file to run it. 

![Python Install Dialogue Box](images/windows_install_python.png)

In the dialogue box that opens up, it is important to check the box to **Add Python 3 to PATH**. Then you can go ahead and click **Install Now**. The setup process will take a little bit of time.

Once the setup is complete, click on **Done** and then you can close your web browser. Clicking in the start menu you should now be able to find **IDLE** which is a fairly good interactive development environment for new beginners to use with Python.

### Apple MacOS

To install Python on MacOS, you will first need to install Xcode. Open up your **App Store** and search for **Xcode**, and then when you find the application, install it to your computer, which will take a few minutes.

Once Xcode has been installed, open up a web browser and navigate to [brew.sh](https://brew.sh), which is the homepage of **Homebrew**, which is a MacOS package manager, allowing you to install a lot of different applications.

To install Homebrew, copy the script that is on the homepage:

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Then open up a **Terminal**, and past in the copied text and then press **Enter**. This will start the installation process for Homebrew, and you may be prompted at various times for confirmations and your password.

Once Homebrew has installed, in the terminal you now type:

```
brew install python3
```

Which will install Python 3 to your system.

If you now have a look at your **Applications** you might find that Python 3 is not there, or there maybe a large question mark over the icon. To make sure that you can access Python 3 IDLE from your apps, go back to the Terminal and type:

```
brew linkapps
```

Now navigating to your Apps or searching for IDLE, and you'll find that **IDLE 3** should be there.

## Linux (Debian based distributions)

Most distributions of Linux come with Python 3 already installed, however you might not have IDLE installed, using `apt` you can check whether they are installed and install if them if they aren't 

Open up a terminal and type:

```
sudo apt update
sudo apt install python3 idle3
```

This will install IDLE into you Apps, and you should be able to search for it in your Application menu.