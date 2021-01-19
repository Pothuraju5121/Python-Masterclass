How to Install Python on Windows
There are three installation methods on Windows:

1. The Microsoft Store: The most straightforward installation method on Windows involves installing from the Microsoft Store app. This is recommended for beginner Python users looking for an easy-to-set-up interactive experience.
2. The full installer: This approach involves downloading Python directly from the [Python.org website.](https://www.python.org/) This is recommended for intermediate and advanced developers who need more control during the setup process.
3. Windows Subsystem for Linux: The WSL allows you to run a Linux environment directly in Windows. You can learn how to enable the WSL by reading the [Windows Subsystem for Linux Installation Guide for Windows 10.](https://docs.microsoft.com/en-us/windows/wsl/install-win10)

In this section, you’ll learn how to check which version of Python, if any, is installed on your Windows computer. You’ll also learn which of the three installation methods you should use.

In this section, we’ll focus on only the first two options, which are the most popular installation methods in a Windows environment.

Limitations of the Microsoft Store Package
The official Python documentation has this to say about the Microsoft Store package:
> The Microsoft Store package is an easily installable Python interpreter that is intended mainly for interactive use, for example, by students.

The key takeaway here is that the Microsoft Store package is “intended mainly for interactive use.” That is, the Microsoft Store package is designed to be used by students and people learning to use Python for the first time.

In addition to targeting beginning Pythonistas, the Microsoft Store package has limitations that make it ill-suited for a professional development environment. In particular, it does not have full write access to shared locations such as TEMP or the registry.

How to Install From the Microsoft Store
If you’re new to Python and looking to get started quickly, then the Microsoft Store package is the best way to get up and running without any fuss. You can install from the Microsoft Store in two steps.

Step 1: Open the Python App Page in the Microsoft Store
Open the Microsoft Store app and search for Python.

You’ll likely see multiple versions that you can choose to install:
![alt text](https://robocrop.realpython.net/?url=https%3A//files.realpython.com/media/Screen_Shot_2020-07-16_at_11.06.17_AM.4b41c401c5aa.png&w=512&sig=060909237a3b606788920f0a2d4d43ec06698113)

Select Python 3.8, or the highest version number you see available in the app, to open the installation page.

Step 2: Install the Python App
After you’ve selected the version to be installed, follow these steps to complete the installation:

1. Click Get.

2. Wait for the application to download. When it’s finished downloading, the Get button will be replaced with a button that says Install on my devices.

3. Click Install on my devices and select the devices on which you’d like to complete the installation.

4. Click Install Now and then OK to start the installation.

5. If the installation was successful, then you’ll see the message “This product is installed” at the top of the Microsoft Store page.

Now, you will have access to Pyhton, including pip and IDLE.

How to Install From the Full Installer
For professional developers who need a full-featured Python development environment, installing from the full installer is the right choice. It offers more customization and control over the installation than installing from the Microsoft Store.

You can install from the full installer in two steps.

Step 1: Download the Full Installer
Follow these steps to download the full installer:

1. Open a browser window and navigate to the Python.org [Downloads page for Windows.](https://www.python.org/downloads/windows/)

2. Under the “Python Releases for Windows” heading, click the link for the Latest Python 3 Release - Python 3.x.x. As of this writing, the latest version was Python 3.8.4.

3. Scroll to the bottom and select either Windows x86-64 executable installer for 64-bit or Windows x86 executable installer for 32-bit.

When the installer is finished downloading, move on to the next step.

Step 2: Run the Installer
Once you’ve chosen and downloaded an installer, run it by double-clicking on the downloaded file. A dialog box like the one below will appear:
![alt text](https://robocrop.realpython.net/?url=https%3A//files.realpython.com/media/Screen_Shot_2020-07-16_at_11.19.15_AM.6e62bfc6eede.png&w=640&sig=fa226c3bdd5950cf543a309a47e89789e9a19a9f)

There are four things to notice about this dialog box:

1. The default install path is in the [AppData/ directory] of the current Windows user.

2. The Customize installation button can be used to customize the installation location and which additional features get installed, including pip and IDLE.

3. The Install launcher for all users (recommended) checkbox is checked default. This means every user on the machine will have access to the [py.exe launcher.] You can uncheck this box to restrict Python to the current Windows user.

4. The Add Python 3.8 to PATH checkbox is unchecked by default. There are several reasons that you might not want Python on PATH, so make sure you understand the implications before you check this box.

The full installer gives you total control over the installation process.

Customize the installation to meet your needs using the options available on the dialog box. Then click Install Now. That’s all there is to it!

Now, you have the latest version of Python 3 on your Windows machine.

How to Check Your Python Version on Windows
To check if you already have Python on your Windows machine, first open a command-line application, such as Terminal.
> Tip: Here’s how you open PowerShell:

> Press the Win key.

> Type PowerShell.

> Press Enter.

> Alternatively, you can right-click the Start button and select Windows PowerShell or Windows PowerShell (Admin).

With the command line open, type in the following command and press Enter:

> C:\> python --version
> Python 3.8.4
