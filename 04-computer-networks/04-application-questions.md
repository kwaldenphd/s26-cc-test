# Application Questions

[Link to application question template](https://docs.google.com/document/d/1qYZRLlZzbZHCGIJEn4Urvpk9uBHouE_psQCsU61lEvE/copy) (ND users, Google Doc)

## Question #1

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

## Question #2

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

## Question #3

Q3a: Let's use the `ipconfig` (Windows) or `ifconfig` (Mac) commands to learn more about your computer's network configuration. Open a terminal shell (`Terminal` or `Git BASH`). Type `ipconfig` (Windows) or `ifconfig` (Mac) followed by `Enter`/`Return`.

Q3b: Describe what you're seeing in the output. What information are these results providing about your network? How do they connect to concepts covered in this lab?

A couple resources that can help with understanding these results:
- `ipconfig`
  * LazyAdmin, "[How to use the ipconfig command and options explained](https://lazyadmin.nl/it/ipconfig-command/)"
  * Meridian Outpost, "[How to use ipconfig command with examples](https://www.meridianoutpost.com/resources/articles/command-line/ipconfig.php)"
- `ifconfig`
  * StackExchange, "[MacOS ifconfig output](https://superuser.com/questions/267660/can-someone-please-explain-ifconfig-output-in-mac-os-x)"
  * Oracle, "[Monitoring the interface with the `ifconfig` command](https://docs.oracle.com/cd/E19253-01/816-4554/ipconfig-141/index.html)"