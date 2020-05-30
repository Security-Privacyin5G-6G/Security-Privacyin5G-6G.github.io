---
layout: publication
title: "Securing commercial wifi-based uavs from common security attacks"
authors: M. Hooper, Y. Tian, R. Zhou, B. Cao, A. P. Lauf, L. Watkins, W. H. Robinson, W. Alexis
conference: 2016 IEEE Military Communications Conference
year: 2016
bibkey: hooper2016securing
additional_links:
   - {name: "IEEE Link", url: "https://ieeexplore.ieee.org/abstract/document/7795496/"}
   - {name: "PDF Link", url: "https://www.researchgate.net/profile/Lanier_Watkins2/publication/305096894_Securing_Commercial_WiFi-Based_UAVs_From_Common_Security_Attacks/links/5a0b4d64458515e482749208/Securing-Commercial-WiFi-Based-UAVs-From-Common-Security-Attacks.pdf"}
tags: ["6G Applications", "Connected Robotics and Autonomous Systems"]
---
We posit that commercial Wi-Fi-based unmanned
aerial vehicles (UAV) are vulnerable to common and basic
security attacks, capable by beginner to intermediate hackers.
We do this by demonstrating that the standard ARDiscovery
Connection process and the Wi-Fi access point used in the Parrot
Bebop UAV are exploitable such that the UAV’s ability to fly can
be disrupted mid-flight by a remote attacker. We believe that
these vulnerabilities are systemic in Wi-Fi-based Parrot UAVs.
Our approach observed the normal operation (i.e., ARDiscovery
Connection process over Wi-Fi) of the Parrot Bebop UAV. We
then used a fuzzing technique to discover that the Parrot Bebop
UAV is vulnerable to basic denial of service (DoS) and bufferoverflow attacks during its ARDiscovery Connection process.
The exploitation of these vulnerabilities could result in
catastrophic and immediate disabling of the UAV’s rotors midflight. Also, we discovered that the Parrot Bebop UAV is
vulnerable to a basic ARP (Address Resolution Protocol) Cache
Poisoning attack, which can disconnect the primary mobile
device user and in most cases cause the UAV to land or return
home.
Based on the literature and our own penetration testing, we
assert that Wi-Fi-based commercial UAVs require a
comprehensive security framework that utilizes a defense-indepth approach. This approach would likely mitigate security
risks associated with the three zero-day vulnerabilities described
in this paper as well as other vulnerabilities reported in the
literature. This framework will be effective for Parrot Wi-Fibased commercial UAVs and likely others with similar platforms. 