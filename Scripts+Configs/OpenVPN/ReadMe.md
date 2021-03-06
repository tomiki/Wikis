###Information Directory###
---
######Client.ovpn######
- OpenVPN client config
  - If utilized on Android, `pkcs12 vpn-client1.p12` can be removed (line 54), as Android will import the SSL/TLS cert into it's keychain

######OpenVPN-Server.conf######
- OpenVPN server config for OpenWrt
  - Will need to be modified slightly for other Linux/BSD distros:
    - `option` isn't utilized & should be removed
    - `_` should be changed to `-`

---

######OpenSSL#######
  * **Guides**
    * [Documents](https://www.openssl.org/docs/|OpenSSL)
    * [HowTo](https://www.openssl.org/docs/HOWTO/|OpenSSL)
    * [Man Page](https://www.openssl.org/docs/apps/openssl.html|OpenSSL)

  * **Info**
    * [Deploying a VPN with PKI on GNU/Linux](http://archive.oreilly.com/pub/a/security/2004/10/21/vpns_and_pki.html?page=1)

######OpenVPN######
  * **Android**
    * [OpenVPN on Android](https://docs.openvpn.net/docs/openvpn-connect/openvpn-connect-android-faq.html)
    * [Remove "Your Network Could be Monitored" Toast](http://forum.xda-developers.com/google-nexus-5/help/howto-install-custom-cert-network-t2533550)
    * [Trust CA cert's Root Certificate](http://wiki.cacert.org/FAQ/ImportRootCert#Android_Phones)

  * **Forum**
    * [OpenVPN Forum](https://forums.openvpn.net/)

  * **Guides**
    * [OpenVPN HowTo](https://openvpn.net/index.php/open-source/documentation/howto.html)
    * [OpenVPN Man Page](https://community.openvpn.net/openvpn/wiki/Openvpn23ManPage)

  * **Tuning**
    * [Buffer Tuning](http://winaero.com/blog/speed-up-openvpn-and-get-faster-speed-over-its-channel/)
    * [MTU Tuning](https://community.openvpn.net/openvpn/wiki/Gigabit_Networks_Linux)
