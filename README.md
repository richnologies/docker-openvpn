![License MIT](https://img.shields.io/badge/license-MIT-blue.svg)
# OpenVPN for Docker

This Docker image is a fork from Kyle Manna.

The only difference between this image and the original is that we drop the TLS auth key from HMAC security. The reason for that choice is that we are working on a project with modems [Teltonika RUT500](http://www.teltonika.lt/en/pages/view/?id=1031) and they had support for OpenVPN, but not for TLS.

The modifications is pretty simple, but just in case, here it is our humble contribution.

For help about how to use it, please refer to the original image which is very well documented.

#### Original Image Links

* Docker Registry @ [kylemanna/openvpn](https://hub.docker.com/r/kylemanna/openvpn/)
* GitHub @ [kylemanna/docker-openvpn](https://github.com/kylemanna/docker-openvpn)
