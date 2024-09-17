<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups in Azure, IP Address, and Wireshare</h1>
A walkthough about internet protocols, and Wireshare <br />


<h2>Video Demonstration</h2>

- ### [What is Domain Name System](https://www.youtube.com/watch?v=MwxMsaFFycg)

<h2>Network concepts and tools</h2>

- DNS
- Ip Address
- Wireshark 

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>What are these internet protocols and tools</h2>

- What is DNS
- What is IP Address
- What is WireShark

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/7IZWTo1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
DNS (Domain Name System) is like the internet’s phone book. It translates website names (like `google.com`) into IP addresses (like `192.168.1.1`), which are the "addresses" computers use to find and talk to each other.

How DNS Works:
1. You Type a Website: When you type a web address in your browser, the computer sends a request to a DNS **resolver** to find out what IP address goes with that website.
2. Check Cache: If the resolver has seen that website recently, it already knows the IP address and will send it back.
3. Ask Root Servers: If not, the resolver asks a **root server** where to find the website’s top-level domain (like `.com` for `google.com`).
4. Ask TLD Servers: The root server sends the resolver to a **TLD server**, which knows which server has the exact information.
5. Get IP Address: The resolver finally asks the **authoritative server**, which gives the right IP address.
6. Website Loads: The browser uses the IP address to load the website.

DNS makes it easy for people to browse the web by converting easy-to-remember names into computer-friendly addresses.
</p>
<br />

<p>
<img src="https://i.imgur.com/Tbmwq07.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
An IP address is like a home address, but for devices on the internet. Every device (like your phone, computer, or server) has a unique IP address so it can be found and communicate with other devices online.

Types of IP Addresses:
1. IPv4: Looks like this: `192.168.1.1`. It uses numbers and is the most common type.
2. IPv6: Looks like this: `2001:0db8:85a3:0000:0000:8a2e:0370:7334`. It’s newer and longer because we’re running out of IPv4 addresses.

How It Works:
Just like mail needs a home address to know where to deliver a letter, the internet uses IP addresses to send and receive data (like emails, websites, or videos) between computers. Without an IP address, a device wouldn't be able to communicate or access the internet, because there would be no way to locate it.
</p>
<br />

<p>
<img src="https://i.imgur.com/kLpCgg5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Wireshark is a tool that lets you see what's happening on a computer network, kind of like looking at the traffic on a busy highway. It captures and analyzes data being sent over the network, such as emails, web browsing, or video streaming, to help understand or troubleshoot problems.

How It Works:
1. Captures Data: Wireshark listens to the network and collects the "packets" of data being sent between devices.
2. Analyzes Data: It lets you see where the data is coming from, where it's going, and what kind of information is being sent.
3. Troubleshooting: Network engineers use it to find issues, like why a website is slow or whether something suspicious, like hacking, is happening.
Think of Wireshark like a detective tool that helps you look at the details of what's happening on the internet in real-time.
</p>
<br />
