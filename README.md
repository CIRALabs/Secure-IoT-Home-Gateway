# Secure Home Gateway (SHG)

## CIRA Labs Project information: https://cira.ca/cira-secure-home-gateway

## Our GOAL: To develop running code!

_CircleID article: https://www.circleid.com/posts/20190305_an_update_from_cira_on_iot_security/_

Here you will find the latest PowerPoint presentations (also in PDF) for the SHG.  CIRA and other members of the community are developing a secure home gateway prototype with the primary objective of securely provisioning IoT devices based on their MUD profile along with other cool stuff.

_The prototype code is available here: https://github.com/CIRALabs_

For many internet organizations, one of the highest ranking risk for internet organization are large-scale DDoS attack originating from IoT devices.  One of the mitigation mechanisms for this risk is to prevent weaponization of IoT devices.  IoT devices are weaponized when vulnerabilities are exposed or accessible to bad actors on the internet.  Protecting IoT devices at the edge with security access controls is another layer of security (because you can’t have too many layers of security). The security access controls are aimed at protecting the IoT devices from the internet, and to protect the internet from IoT devices.  

It is worthwhile noting that there is no (AFAIK) mechanism available today to implement enterprise type security controls into a home gateway.  

### Nobody should think of connecting a 'dumb' IoT device directly on the internet, and with IPv6, this is just going to get worse, so now is the time to fix this.

The project team is currently developing a prototype / proof of concept / running code.  The team is also documenting the requirement for a next generation secure home gateway and a home registry solution that with security controls can protect IoT devices and the internet from each other.  The project is an innovative IoT initiative to develop a solution for a secure home networks and a trust framework for its connected devices based on domain names and DNSSEC.

The ultimate goal of this project is to develop open standards with IETF & ISO/IEC and to develop open source openWRT code that can be freely used to next generation secure home gateways.

Remotely accessing the home network is another aspect we're looking at in defining security access controls for an IoT device, we want to develop security access control rules to allow for example your mobile to access the camera in your fridge.  To do this we need to provision a domain name for the gateway to which a vpn connection can be established and enable the connectivity between the mobile and fridge.  The domain provisioning story in the slide deck is tuned to CIRA and .CA, but is meant to be adapted by all ccTLD on the planet.  A framework for ccTLD to provision domains to secure home gateways.

_MUD Related links: http://www.sandelman.ca/SSW/ietf/mud-links/

_Latest SGH presentations at RIPE77: https://ripe77.ripe.net/archives/video/2309/

_A recorded demo: https://www.youtube.com/watch?v=LauvEBa4Z4s&feature=youtu.be
