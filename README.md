🚀 **Day 2 of My 60-Day Network Engineering Challenge**

Today, I explored how devices communicate on a network when **nothing is known yet** — no MAC addresses, no ARP entries.

Here’s what I worked on:

* Simulated communication between PCs with empty MAC & ARP tables
* Observed how ARP requests are broadcast across the network
* Used Packet Tracer simulation mode to trace packet flow
* Generated traffic to allow switches to learn MAC addresses
* Verified learned MAC addresses using `show` commands
* Cleared MAC address tables to reset learning

💡 **Key Takeaways:**

* ARP requests are **broadcast** to all devices in the network
* ARP replies are **unicast** back to the sender
* Switches learn MAC addresses dynamically from incoming frames
* MAC address tables are built **automatically through traffic**

⚠️ What stood out:
At the start, the switch behaves like a hub (flooding traffic) until it learns MAC addresses.

This is how networks *actually* learn and adapt in real time.

✅ Day 2 done
🎯 58 days to go

#CCNA #NetworkEngineering #Cisco #LearningInPublic #Networking #TechJourney #PacketTracer
