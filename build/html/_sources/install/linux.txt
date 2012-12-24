Linux
=====

Linux needs no introduction. It is the most popular Unix based Operating System out there. Following are descriptions about installing Xfce on some of the major `Linux Distributions <http://en.wikipedia.org/wiki/Linux_distribution>`_.


Ubuntu
------

To test out Xfce in Ubuntu you can use `Xubuntu <http://xubuntu.org/getxubuntu/>`_.

Alternatively, you can download Ubuntu from `Ubuntu.com <http://www.ubuntu.com/download>`_ and type the following command into terminal

.. code-block:: none

   sudo apt-get install xubuntu-desktop

If you want to use *stock* Xfce (which is highly recommended), you can use the following description.

Installing Xfce on Ubuntu 12.04 LTS involves three main steps :

1. Opening up terminal

* Click on the dash icon

.. figure:: ../_static/images/ubuntu_install/1_click_on_dash_icon.png
   :alt: Click on Dash Icon
   :align: center 

   Click on the dash icon

* Now search for the terminal software. Click on the terminal icon to open the terminal application.

.. figure:: ../_static/images/ubuntu_install/2_search_for_terminal_and_select_terminal_application.png
   :alt: Search for terminal application software
   :align: center 

   Search and find the terminal application

2. Entering the command to install Xfce

Once the terminal application opens up you need to enter the following command to install Xfce:

.. code-block:: none

   sudo apt-get install xfce4 xfce4-goodies

You may be prompted to enter your pasword and authenticate your install.


.. figure:: ../_static/images/ubuntu_install/3_command_xfce_install.png
   :alt: Type in command to install Xfce
   :align: center 

   Enter the command to install Xfce


You will need to be connected to the Internet to begin the installation. Once you authenticate, Ubuntu will begin downloading and installing Xfce on your computer.

.. figure:: ../_static/images/ubuntu_install/4_downloading_xfce_hddtemp.png
   :alt: Downloading and installing Xfce
   :align: center 

   Downloading and installing Xfce

On Ubuntu 12.04 LTS, you may be prompted to answer a question about hddtemp during installation. Please do not worry about this and press ENTER to select the default "No" option.

3. Logging out, selecting and logging into Xfce

* Now, if you want to use your brand new Xfce installation, please log out.

.. figure:: ../_static/images/ubuntu_install/5_logout.png
   :alt: Logout
   :align: center  

   Logout

* Click on the Ubuntu icon.

.. figure:: ../_static/images/ubuntu_install/6_click_on_ubuntu_icon.png
   :alt: Click on Ubuntu icon
   :align: center  

   Click on Ubuntu Icon

* Click on Xfce Session

.. figure:: ../_static/images/ubuntu_install/7_click_on_xfce_session.png
   :alt: Select Xfce Session
   :align: center  

   Click on Xfce Session Icon

* Enter your password and log into Xfce

.. figure:: ../_static/images/ubuntu_install/8_sign_into_xfce.png
   :alt: Login
   :align: center  

   Log into Xfce

* When logging in, select "Use Default Configuration" to get the standard Xfce desktop.

.. figure:: ../_static/images/ubuntu_install/9_click_on_use_default_config.png
   :alt: Default Xfce configuration
   :align: center  

   Xfce Desktop.


Voila! You have entered the default Xfce desktop.

.. WARNING::
   Do not worry about the somewhat unnerving look of the default install. We will be looking into it in a few minutes. By default, the Xfce installation in Ubuntu has a nasty `bug <https://bugs.launchpad.net/ubuntu/+source/xfce4/+bug/1050012>`_ causing it to fall back on default GTK3 theme. You can work around it by entering the following command into terminal: "cp -fdr /usr/share/themes/Radiance/gtk-3.0 ~/.config/gtk-3.0/"

Fedora
------


