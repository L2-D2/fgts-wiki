### Broadcomm 4300 Series (BCM43XX)

The b43 cards are a quite common laptop (and less common desktop) WiFi card without 100% kernel support in the 3.13 [[Linux Kernel|Linux]] found in [[Linux Mint]] 17.1.

To install the proper driver for these cards you will want to use the `firmware-b43-installer` package. Ideally you would have a wired internet connection and can have [[Apt|Aptitude]] install the package with 

```
$ sudo apt update
$ sudo apt install firmware-b43-installer
```

Without a wired connection you will need to obtain the `firmware-b43-install.deb` file that probably exists somewhere on the [[Internet]]. Be sure to use discretion when [[downloading]] installer files from the Internet.