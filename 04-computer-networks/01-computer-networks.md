# Computer Networks

## <i class="fa-solid fa-person-chalkboard" aria-hidden="true"></i> Lecture

<table>
 <tr><td>
<img src="https://elearn.southampton.ac.uk/wp-content/blogs.dir/sites/64/2021/04/PanPan.png" alt="Panopto logo" width="50"/></td>
<td><a href="https://notredame.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=18ec9cd0-b880-4987-814b-aef5000b3f73">Computer Networks</a></td>
  </tr>
  </table>

## <i class="fa-solid fa-key" aria-hidden="true"></i> Key Concepts

```{image} ../images/ch4/LAN_WAN.svg
:alt: LAN diagram
:width: 500px
:align: center
```

```{admonition} Local Area Network (LAN)
:class: tip, dropdown
"A local area network (LAN) is a computer network that interconnects computers within a limited area such as a residence, school, laboratory, university campus or office building. By contrast, a wide area network (WAN) not only covers a larger geographic distance, but also generally involves leased telecommunication circuits. Ethernet and Wi-Fi are the two most common technologies in use for local area networks" ([Wikipedia](https://en.wikipedia.org/wiki/Local_area_network))
```

```{image} ../images/ch4/1973_Ether.png
:alt: Historical ethernet diagram
:width: 500px
:align: center
```

```{admonition} Ethernet
:class: tip, dropdown
"Ethernet is a family of wired computer networking technologies commonly used in local area networks (LAN), metropolitan area networks (MAN) and wide area networks (WAN). It was commercially introduced in 1980 and first standardized in 1983" ([Wikipedia](https://en.wikipedia.org/wiki/Ethernet))
```

```{admonition} Media Access Control (MAC) Address
:class: tip, dropdown
"A media access control address (MAC address) is a unique identifier assigned to a network interface controller (NIC) for use as a network address in communications within a network segment. This use is common in...networking technologies, including Ethernet, Wi-Fi, and Bluetooth...As typically represented, MAC addresses are recognizable as six groups of two hexadecimal digits, separated by hyphens, colons, or without a separator" ([Wikipedia](https://en.wikipedia.org/wiki/MAC_address))
```

```{admonition} Routing/Routers
:class: tip, dropdown
"A router is a networking device that forwards data packets between computer networks. Routers perform the traffic directing functions on the Internet. Data sent through the internet, such as a web page or email, is in the form of data packets. A packet is typically forwarded from one router to another router through the networks that constitute an internetwork (e.g. the Internet) until it reaches its destination node" ([Wikipedia](https://en.wikipedia.org/wiki/Router_(computing)))
```

```{admonition} Hops
:class: tip, dropdown
"In wired computer networking, including the Internet, a hop occurs when a packet is passed from one network segment to the next. Data packets pass through routers as they travel between source and destination. The hop count refers to the number of network devices through which data passes from source to destination" ([Wikipedia](https://en.wikipedia.org/wiki/Hop_(networking)))
```

```{image} ../images/ch4/Packet_Switching_Diagram.png
:alt: Packet switching diagram
:width: 500px
:align: center
```

```{admonition} Packet Switching
:class: tip, dropdown
"Packet switching is a method of grouping data that is transmitted over a digital network into packets. Packets are made of a header and a payload. Data in the header are used by networking hardware to direct the packet to its destination where the payload is extracted and used by application software. Packet switching is the primary basis for data communications in computer networks worldwide" ([Wikipedia](https://en.wikipedia.org/wiki/Packet_switching))
```

```{image} ../images/ch4/Packet_Diagram.png
:alt: Packet Diagram
:width: 500px
:align: center
```

```{admonition} Network Packet
:class: tip, dropdown
"A network packet is a formatted unit of data carried by a packet-switched network. A packet consists of control information and user data, which is also known as the payload. Control information provides data for delivering the payload, for example: source and destination network addresses, error detection codes, and sequencing information. Typically, control information is found in packet headers and trailers" ([Wikipedia](https://en.wikipedia.org/wiki/Network_packet))
```

```{admonition} Internet Protocol (IP)
"The Internet protocol suite is the conceptual model and set of communications protocols used in the Internet and similar computer networks. It is commonly known as TCP/IP because the foundational protocols in the suite are the Transmission Control Protocol (TCP) and the Internet Protocol (IP). The Internet protocol suite provides end-to-end data communication specifying how data should be packetized, addressed, transmitted, routed, and received. This functionality is organized into four abstraction layers, which classify all related protocols according to the scope of networking involved. From lowest to highest, the layers are the link layer, containing communication methods for data that remains within a single network segment (link); the internet layer, providing internetworking between independent networks; the transport layer, handling host-to-host communication; and the application layer, providing process-to-process data exchange for applications" ([Wikipedia](https://en.wikipedia.org/wiki/Internet_protocol_suite))
```

```{admonition} Internet Protocol (IP) Address
:class: tip, dropdown
"An Internet Protocol address (IP address) is a numerical label such as 192.0.2.1 that is connected to a computer network that uses the Internet Protocol for communication. An IP address serves two main functions: network interface identification and location addressing" ([Wikipedia](https://en.wikipedia.org/wiki/IP_address))
```

```{admonition} ARPANET
:class: tip, dropdown
"The Advanced Research Projects Agency Network (ARPANET) was the first wide-area packet-switched network with distributed control and one of the first networks to implement the TCP/IP protocol suite. Both technologies became the technical foundation of the Internet. The ARPANET was established by the Advanced Research Projects Agency (ARPA) of the United States Department of Defense" ([Wikipedia](https://en.wikipedia.org/wiki/ARPANET))
```

```{admonition} Internet of Things
:class: tip, dropdown
"The Internet of things (IoT) describes physical objects (or groups of such objects) with sensors, processing ability, software, and other technologies that connect and exchange data with other devices and systems over the Internet or other communications networks" ([Wikipedia](https://en.wikipedia.org/wiki/Internet_of_things))
```

## <i class="fa-solid fa-clipboard-check" aria-hidden="true"></i> Comprehension Check

<table>
 <tr><td>
<img src="https://github.com/kwaldenphd/internet/blob/main/images/clipboard.png?raw=true" alt="Clipboard icon" width="50"/></td>
  <td><a href="https://docs.google.com/forms/d/e/1FAIpQLSexiph4YBLk_cvOK6dt0C_4qfiFZ0RfvxUYJFWFdL83msZo_g/viewform?usp=sf_link">Computer Networks Comprehension Check</a></td>
  </tr>
  </table>

## <i class="fa-solid fa-clipboard-question" aria-hidden="true"></i> Application

Q1a: Let's use the `ping` command for a network test. Open a terminal shell (`Terminal` or `Git BASH`). Type `ping` followed by an IP address. A few you could choose from:
- OpenDNS: `208.67.222.222` and `208.67.220.220`
- Cloudflare: `1.1.1.1` and `1.0.0.1`
- Google: `8.8.8.8` and `8.8.4.4`

Sample command for Google:
```
ping 8.8.8.8
```

Press `Enter`/`Return`.

Q1b: Describe what you're seeing in the `ping` command output. What do these results indicate about the network status? A couple resources that can help with understanding these results:
- IBM, "[`ping` Command](https://www.ibm.com/docs/en/aix/7.1?topic=p-ping-command)"
- PageDuty, "[How to Ping a Network for Testing Connectivity](https://www.pagerduty.com/resources/learn/ping-network-testing-connectivity/)"

Q2a: Let's run a similar test using the `traceroute` or `tracert` command. Still in the  terminal, type `tracert` followed by a domain name or IP address.

Domain name example:
```
tracert google.com
```

IP address example:
```
tracert 8.8.8.8
```

Press `Enter`/`Return`.

<blockquote>Alternate <code>traceroute</code> workflow for MacOS users: Shaw Support, "<a href="https://support.shaw.ca/t5/internet-articles/how-to-run-a-traceroute-mac-os/ta-p/5053">How to run a Traceroute (Mac OS)</a>."</blockquote>

Q2b: Describe what you're seeing in the `traceroute`/`tracert` program output. What do these results indicate about the network status? How are they similar or different from the `ping` output? 

A couple resources that can help with understanding these results:
- RedHat, "[Traceroute: Finding meaning among the stars](https://www.redhat.com/sysadmin/traceroute-finding-meaning)"
- InMotion Hosting, "[How to Read a Traceroute](https://www.inmotionhosting.com/support/server/ssh/read-traceroute/)"