# -Connecting-Devices-Lab
The goal of this lab is to practice connecting various networking devices using the correct cables, taking into account device type, port compatibility, and distance requirements. The topology includes routers, switches, and end devices such as PCs and servers.
![image](https://github.com/user-attachments/assets/e1bb5a93-cffb-4187-a250-9064699eaad0)

🛠️ Instructions
🔗 Connect devices as labeled:

Follow the topology and use correct port names (e.g., Fa0/1, Gig0/0).

Check the distance notes (e.g., 3 km, 50 m) for each connection.

🔌 Use the appropriate cable:

📗 Straight-through for different device types (PC ↔ Switch, Switch ↔ Router).

📘 Crossover for similar device types (Switch ↔ Switch, Router ↔ Router).

🌐 Fiber for long-distance connections:

R1 🔁 R3 – 3 km ➡️ use fiber!

R3 🔁 R4 – 250 m ➡️ also fiber!

⚠️ MDI/MDI-X Note:

Assume auto MDI-X is ❌ disabled.

Manually choose crossover cables when connecting similar devices.

💡 Fiber Tip:

🎯 Use single-mode fiber for long distances (e.g., 3 km).

🌀 Use multi-mode fiber for shorter links (e.g., 250 m).

Packet Tracer doesn't simulate the difference, but it's good practice to know! 😉

🗺️ Topology Overview
🖧 Routers: R1, R2, R3, R4

🧷 Switches:

Distribution: SW1, SW2 (to R2); SW5, SW6 (to R4)

Access: SW3, SW4, SW7, SW8

💻 End Devices:

PC1, PC2, PC3

🖥️ SRV1 (Server)

✅ Tips
✔️ Double-check port labels before connecting!

✔️ Choose the correct cable – especially for similar vs. different devices.

✔️ Use "Simulation Mode" 🐢 to test connections and troubleshoot.

