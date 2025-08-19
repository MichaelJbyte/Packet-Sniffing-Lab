# Packet-Sniffing-Lab
Lab to familiarize with logging network packets. 8/18/25

This lab followed a Wireshark beginner tutorial featured on YouTube, providing firsthand experience with both packet capture and network analyzing. This tutorial will ______.

## Process

- I first installed the latest version of Wireshark for Windows. This required me to subsequently download Npcap.

1. Beginning the lab, I clicked stop in the top right to capture all currents packets. I then used the Statistics tab to access the 'conversations' tab, showing me all the communications that happened during the packet capture, displaying all relevent information.

![photo](https://github.com/MichaelJbyte/Packet-Sniffing-Lab/blob/a7b82e2cdec92f5c42396ed0eabce13ce6a2396e/viewing%20conversations%201.png)

2. Next, I learned how to use a variety of filters.
  - When clicking on an IP address in the 'conversations' tab, you can use that IP address to filter providing multiple different results.
  - Located right below the Wireshark toolbar, I also utilized the search which allowed me to filter more precisely. This included looking for packets relating to both IP's and protocols.
  - One example for the above would be: tcp.port == 80 || udp.port == 80
Filters assist in whatever objective you have by shortening the, often large, packet capture and reducing it to the necessary packets that you may need.

![photo](https://github.com/MichaelJbyte/Packet-Sniffing-Lab/blob/2519aa83da835243ec96ae3fe024520fbf56125e/filter%20ex.png)

3. Following that, I briefed over the packet contents placed in the bottom left, the encrypted ciphertext in the bottom right, and went over the 'follow' option.
   - The 'follow' option is often utilized as a catalsyt and an identifier for phishing attacks.

4. After this, I learned how to make buttons for filters and how to view the color key for Wireshark.
   - Filters can be turned into easily accesible buttons for quick and later usage.
   - Viewing the color key can be helpful to identify what Wireshark flags as potentially malicious or packet drops.

![photo](https://github.com/MichaelJbyte/Packet-Sniffing-Lab/blob/2519aa83da835243ec96ae3fe024520fbf56125e/viewing%20coloring%20rules.png)

5. Lastly, I learned about the customization tools available in Wireshark.
   - Through the 'preferences' tab, I found you can customize the display, fields, and colors which Wireshark displays.

![photo](https://github.com/MichaelJbyte/Packet-Sniffing-Lab/blob/2519aa83da835243ec96ae3fe024520fbf56125e/wireshark%20preferences.png)

* This lab also taught me common usages for Wireshark, including its' great usage for both conducting and identifying phishing attacks. Along with this, Wireshark can be used to improve your bandwidth and monitor your network devices connectivity.


