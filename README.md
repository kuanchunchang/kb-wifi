# Learning WiFi

## Terminology and Concept

**WiFi**

**Wi-Fi** or **WiFi** is a technology that allows electronic devices to connect to a wireless LAN (WLAN) network, mainly using the 2.4 gigahertz (12 cm) UHF and 5 gigahertz (6 cm) SHF ISM radio bands. A WLAN is usually password protected, but may be open, which allows any device within its range to access the resources of the WLAN network.

The Wi-Fi Alliance defines Wi-Fi as any "wireless local area network" (WLAN) product based on the Institute of Electrical and Electronics Engineers' (IEEE) 802.11 standards. However, the term "Wi-Fi" is used in general English as a synonym for "WLAN" since most modern WLANs are based on these standards. "Wi-Fi" is a trademark of the Wi-Fi Alliance. The "Wi-Fi Certified" trademark can only be used by Wi-Fi products that successfully complete Wi-Fi Alliance interoperability certification testing.

> https://en.wikipedia.org/wiki/Wi-Fi

**WLAN**

A **Wireless Local Area Network (WLAN)** is a wireless computer network that links two or more devices using a wireless distribution method (often spread-spectrum or OFDM radio) within a limited area such as a home, school, computer laboratory, or office building. This gives users the ability to move around within a local coverage area and still be connected to the network, and can provide a connection to the wider Internet. Most modern WLANs are based on IEEE 802.11 standards, marketed under the Wi-Fi brand name.

> https://en.wikipedia.org/wiki/Wireless_LAN

**Station**

In IEEE 802.11 (Wi-Fi) terminology, a **station (STA)** is a device that has the capability to use the 802.11 protocol.
For example, a station may be a laptop, a desktop PC, PDA, access point or Wi-Fi phone. An STA may be fixed, mobile or
portable. Generally in wireless networking terminology, a station, wireless client and node are often used
interchangeably, with no strict distinction existing between these terms. With a station also being referred as
transmitter or receiver based on its transmission characteristics.

IEEE 802.11-2007 formally defines station as:

*Any device that contains an IEEE 802.11-conformant media access control (MAC) and physical layer (PHY) interface to the wireless medium (WM).*

> https://en.wikipedia.org/wiki/Station_(networking)

**AP**

In computer networking, a **Wireless Access Point (WAP)** is a networking hardware device that allows a Wi-Fi compliant
device to connect to a wired network. The WAP usually connects to a router (via a wired network) as a standalone device,
but it can also be an integral component of the router itself.

A WAP is differentiated from a hotspot, which is the physical location where Wi-Fi access to a WLAN is available.

> https://en.wikipedia.org/wiki/Wireless_access_point

**Router**

A **router** is a networking device that forwards data packets between computer networks. Routers perform the "traffic directing" functions on the Internet. A data packet is typically forwarded from one router to another through the networks that constitute the internetwork until it reaches its destination node.

A router is connected to two or more data lines from different networks (as opposed to a network switch, which connects data lines from one single network). When a data packet comes in on one of the lines, the router reads the address information in the packet to determine its ultimate destination. Then, using information in its routing table or routing policy, it directs the packet to the next network on its journey. This creates an overlay internetwork.

> https://en.wikipedia.org/wiki/Router_(computing)

**Hotspot**

A **hotspot** is a physical location where people may obtain Internet access, typically using Wi-Fi technology, via a wireless local area network (WLAN) using a router connected to an internet service provider.

> https://en.wikipedia.org/wiki/Hotspot_(Wi-Fi)

**BSS**

The **Basic Service Set (BSS)** is a set of all stations that can communicate with each other at PHY layer. Every BSS has an identification (ID) called the BSSID, which is the MAC address of the access point servicing the BSS.

The basic service set (BSS) provides the basic building-block of an 802.11 wireless LAN. In infrastructure mode, a single access point (AP) together with all associated stations (STAs) is called a BSS; not to be confused with the coverage of an access point, known as the basic service area (BSA). The access point acts as a master to control the stations within that BSS; the simplest BSS consists of one access point and one station.

**ESS**

An **Extended Service Set (ESS)** is a set of two or more interconnected wireless BSSs that share the same SSID (network name), security credentials and integrated (providing translation between 802.3 and 802.11 frames) wired local area networks that appear as a single BSS to the logical link control layer at any station associated with one of those BSSs which facilitates mobile IP and fast secure roaming applications; the BSSs may work on the same channel, or work on different channels to boost aggregate throughput.

Access points in an ESS are connected by a distribution system. Each ESS has an ID called the SSID which is a 32-byte (maximum) character string.

![Wireless Lan Architecture](http://what-when-how.com/wp-content/uploads/2012/03/tmp15B103_thumb.jpg)

> http://what-when-how.com/roaming-in-wireless-networks/wlan-overview-roamingcurrent-and-future-enhancements/

**SSID**

Each BSS or ESS is identified by a **service set identifier (SSID)** - a series of 0 to 32 octets. It is used as an identifier for a wireless LAN, and is intended to be unique for a particular area. Since this identifier must often be entered into devices manually by a human user, it is often a human-readable string and thus commonly called the "network name"

**IEEE 802.11**

**IEEE 802.11** is a set of media access control (MAC) and physical layer (PHY) specifications for implementing wireless local area network (WLAN) computer communication in the 900 MHz and 2.4, 3.6, 5, and 60 GHz frequency bands.

> https://en.wikipedia.org/wiki/IEEE_802.11

## Reference
- http://standards.ieee.org/getieee802/download/802.11-2007.pdf
