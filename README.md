# st - simple terminal
st is a [simple terminal](https://st.suckless.org/) emulator for X which sucks less.
This version is patched with the following features:
* Transparency
* Clipboard
* Scrollback using Alt+k,j and mouse wheel
* You can copy urls by typing Alt+l


# Requirements
In order to build this version of st you need to install Xlib header files.


# Installation
Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

    make clean install

# Credits
Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

