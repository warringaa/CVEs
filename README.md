The following is a list of my collected CVE's

## Glory Systems, RBW-100
The Glory RBW-100 banknote recycling system controls cash and removes the need for manual note handling. I've found two vulnerabilities in the Font Circle Controller management interface that can lead to a reverse root-shell:
* [CVE-2019-10479](https://github.com/warringaa/CVEs/tree/master/CVE-2019-10479/README.md) - Default hardcoded credentials
* [CVE-2019-10478](https://github.com/warringaa/CVEs/tree/master/CVE-2019-10478/README.md) - Arbitrary file upload
<img src="https://www.glory-global.com/-/media/GloryGlobal/Images/Product-and-Service/rbw100oem-hero-680x970-desktop.jpg?h=485&la=en-US&w=340&hash=47E7639F6120688E65216CDA6A1C6288BD86DD5F" width="150">

See a POC, combining these two vulnerabilities in action: https://youtu.be/MSKDfLpPOLw
