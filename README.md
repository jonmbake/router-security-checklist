# Router Security Checklist

A checklist to ensure you have the most secure router possible. Inspiration from [RouterSecurity.org](http://routersecurity.org/)'s [Router Security Checklist](http://routersecurity.org/checklist.php).

## Buying a Router

- [ ] **Buy a business-class router**
> "When you buy a consumer router you are buying the hardware. The software is provided as cheaply as possible. When you buy a business class router you are buying the software." - http://routersecurity.org/. 

## Router Administration 

- [ ] **Change the Default Password!** It is typically *username/password*: admin/admin, and accessed through a [Standard IP Address](http://www.techspot.com/guides/287-default-router-ip-addresses/).  If a bad actor gets access to your router, they could login and change whatever.
- [ ] **Limit Access to Ethernet Only** If your router supports it, having to plugin an ethernet cable to edit router configs is a **huge** security boost. This also includes any Smartphone Apps. Seriously, you should have to physically plug in an ethernet cable to edit access your router administration.
- [ ] **Require HTTPS** The router administration console is accessed over HTTP/S. Most routers have the option of forcing HTTPS. Take advantage.
- [ ] **Check for Firmware Updates Every 3 Months** If the router manufacturer offers a security/patch email list, sign up.
- [ ] **Ensure router does not have any unpatched vulnerabilities** If it does, buy another router.

## Disable Insecure Services

- [ ] **[WPS](https://en.wikipedia.org/wiki/Wi-Fi_Protected_Setup)**
- [ ] **[UPnP](https://en.wikipedia.org/wiki/Universal_Plug_and_Play)**
- [ ] **[HNAP](http://routersecurity.org/hnap.php)**
- [ ] **[DDNS](https://en.wikipedia.org/wiki/Dynamic_DNS) (if not needed)**

## WiFi Configuration

- [ ] **Change the Default Password!** Make it a [strong password](http://passwordsgenerator.net/). Most routers allow **unlimited** password tries. `A weak password + a determined bad actor = guaranteed access to your router`. Update the strong password to another strong password every 3 months.
- [ ] **Use the Most Secure Password Encryption Available** According to the following order from most secure to least:
  - *WPA2*
  - *WPA/WPA2*
  - *WPA*
  - *WEP*
  - *No Encryption* (Obviously, no)
  
## Limit Access

- [ ] **Enable any built-in firewall**
- [ ] **Limit Port Access** 
- [ ] **Enable [Mac Address Filtering](https://en.wikipedia.org/wiki/MAC_filtering)**


