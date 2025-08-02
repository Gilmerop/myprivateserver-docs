## 🔁 Router Topology and Internet Access

### 🛠️ Configuration Summary

- The **ISP router** is configured in **DMZ mode**, forwarding all external traffic to the MyRouter.
- A **public static IP address** is contracted and assigned to the ISP router.
- The **MyRouter** is assigned a **private static IP** by the ISP router and receives all inbound traffic.
- The **MyRouter** handles all local network management and remote access (VPN).
- All internal devices connect through the TP-Link router, which acts as firewall, DHCP server, DNS relay, and OpenVPN endpoint.

> ⚠️ The actual public IP is not shared here for security reasons.

---

### 🧰 TP-Link Router Configuration

- OpenVPN server enabled with custom port  
- Local subnet: `192.168.x.x/24`  
- Static IP reservation for internal devices  
- Manual DNS configured (Cloudflare 1.1.1.1)  
- Port forwarding not yet enabled (under testing)



