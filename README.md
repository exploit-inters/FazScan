# FazScan
![Version](https://img.shields.io/badge/FazScan-v1.1-brightgreen.svg) ![Language](https://img.shields.io/badge/Language-English-blue.svg) ![Status](https://img.shields.io/badge/Release-Stable-important.svg) ![License](https://img.shields.io/badge/License-Apache%202.0-brightgreen.svg) ![Compatibility](https://img.shields.io/badge/Compatible%20OS-Linux%2FWindows%2FAndroid-brightgreen.svg)

![FazScan](https://github.com/Anon6372098/FazScan/blob/master/img/fazscanv1.1-2-2.png)

FazScan is a Perl program to do some vulnerability scanning and pentesting. This program has 16 ultimate options.

## FazScan, Program for Vulnerability Scanner and Pentester

#### Options Available : 
  ##### 1. SQL Injection Pentester
  ##### 2. Common SQLi Vulnerability Scanner
  ##### 3. Advanced SQLi Vulnerability Scanner
  ##### 4. Common Web Vulnerability Scanner `Updated 31/03/2019`
  ##### 5. Automated CMS Detector `Update's New Feature`
  ##### 6. Web CMS WordPress Vulnerability Scanner `Updated 31/03/2019`
  ##### 7. Web CMS Magento Vulnerability Scanner
  ##### 8. Web CMS Joomla Vulnerability Scanner
  ##### 9. Web CMS Lokomedia Vulnerability Scanner
  ##### 10. Web CMS Drupal Vulnerability Scanner + Shell Uploader `Updated 31/03/2019`
  ##### 11. Dork Scanner `Update's New Feature`
  ##### 12. Automated Open Port Scanner
  ##### 13. Denial of Service Attack
  ##### 14. Admin Page Detector (7475 Pages Will be Scanned)
  ##### 15. About the Programmer
  ##### 16. Exit the Program

### How to Run ?

Follow the Instructions (You can use your own way too) :

### Kali Linux (Terminal Kali Linux)

- apt-get update
- apt-get install perl
- apt-get install clang
- apt-get install gcc
- apt-get install make
- cpan `If you're first in Perl. If you're asked for an option, just type like the recomendation (ex : [local::lib], just type local::lib then enter). If stuck, exit the terminal, open the terminal (or CTRL-C) and continue to the next step`
- apt-get install liblwp-protocol-https-perl
- apt-get install git
- git clone https://github.com/Anon6372098/FazScan
- cd FazScan
- sh installpm.sh
- cpan install -fi LWP::UserAgent
- perl fazscan.pl

or

- sudo apt-get update
- sudo apt-get install perl
- sudo apt-get install clang
- sudo apt-get install gcc
- sudo apt-get install make
- sudo cpan `If you're first in Perl. If you're asked for an option, just type like the recomendation (ex : [local::lib], just type local::lib then enter). If stuck, exit the terminal, open the terminal (or CTRL-C) and continue to the next step`
- sudo apt-get install liblwp-protocol-https-perl
- sudo apt-get install git
- git clone https://github.com/Anon6372098/FazScan
- cd FazScan
- sh installpms.sh
- sudo cpan install -fi LWP::UserAgent
- perl fazscan.pl

### Windows (CMDer)

- install package manager chocolatey first on PowerShell as Admin 

" Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1')) "

- choco install perl
- choco install llvm
- choco install make
- cpan `If you're first in Perl. If you're asked for an option, just type like the recomendation (ex : [local::lib], just type local::lib then enter). If stuck, exit the terminal, open the terminal (or CTRL-C) and continue to the next step`
- choco install git
- git clone https://github.com/Anon6372098/FazScan
- cd FazScan
- sh installpm.sh
- cpan install -fi LWP::UserAgent
- perl fazscan.pl

### Android (Termux)

- pkg update && pkg upgrade
- pkg install perl
- pkg install clang
- pkg install make
- cpan `If you're first in Perl. If you're asked for an option, just type like the recomendation (ex : [local::lib], just type local::lib then enter). If stuck, exit the terminal and continue to the next step`
- pkg install git
- git clone https://github.com/Anon6372098/FazScan
- cd FazScan
- sh installpm.sh
- cpan install -fi LWP::UserAgent
- perl fazscan.pl

### License

Apache 2.0 Licensed

![License_img](https://github.com/Anon6372098/FazScan/blob/master/img/FazScan_License.png)
