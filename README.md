tabbed - generic tabbed interface
=================================
tabbed is a simple tabbed X window container.

Requirements
------------
In order to build tabbed you need the Xlib header files

Installation
------------
Edit config.mk to match your local setup (tabbed is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install tabbed
(if necessary as root):

    make clean install

Running tabbed
--------------
See the man page for details.
If using elh-dwm and elh-st, hitting Super + Enter will automatically opened a tabbed st.

Changes from stock
------------------
1. Ctrl + Enter will open a new tab
2. Ctrl + Comma/Period navigates tabs
3. Ctrl + Q will close a tab 
4. Ctrl + j/k will "rotate" tabs
