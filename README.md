<p align="center">
<img src="https://i.imgur.com/kgPkWV1.png" alt="Traffic Examination"/>
</p>

<h1>Internet Protocols and Tool</h1>
A walkthough about internet protocols, and Wireshare <br />


<h2>Video Demonstration</h2>

- ### [What is Domain Name System](https://www.youtube.com/watch?v=MwxMsaFFycg)

<h2>Network concepts and tools</h2>

- DNS
- DHCP
- Wireshark 

<h2>Operating Systems Used </h2>

- Windows 10

<h2>What are these internet protocols and tools</h2>

- What is DNS
- What is DHCP
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
<img src="https://i.imgur.com/3oLYjE6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
DHCP (Dynamic Host Configuration Protocol) is like a network's "automatic address giver." When you connect your phone, computer, or any device to the internet or Wi-Fi, it needs an IP address (like a home address) to communicate with other devices. Instead of manually setting an IP address for each device, **DHCP** does it for you automatically.

### How It Works:
1. Join the Network: When you connect to a Wi-Fi network, your device asks for an IP address.
2. DHCP Server Responds: The DHCP server assigns your device a temporary IP address.
3. Device Gets an IP Address: Your device can now send and receive data, like browsing the web or checking email.
In simple terms, DHCP makes sure every device on a network gets an IP address without you having to do anything manually.
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
