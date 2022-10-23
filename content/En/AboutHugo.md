
WHAT IS HUGO?
===
Hugo is a static site generator

Installation Hugo on Windows
===
To install the latest version of Hugo on Windows, the first thing we must do is go to the following link.

LINK TO DOWNLOAD PAGE
===
https://github.com/gohugoio/hugo/releases

When we open the link we will download the latest version that has a name similar to hugo_extended_x.x.x_windows-amd64.zip .

We will extract the zip and move the Hugo.exe file to the path C:\Hugo\bin which we will create.

go to control panel--> system properties--> and click on environment variables

In the list that will show us we will look for the PATH variable, and at the end of it we will add ';C:\Hugo\bin', With this restarting the system we will have hugo installed and we will be able to start it.

Installation Hugo on Linux
===
We check if we have snap installed

```snap version```
This should give us a response like the following:

```snap 2.55.3+22.04
snapd 2.55.3+22.04
series 16
ubuntu 22.04
kernel 5.15.0-48-generic
```
If we get something like the above it will mean that we have it installed and we can continue
Install the hugo-extended package
Using the Snap manager we are going to install the hugo-extended package.

```snap install hugo --channel=extended```
