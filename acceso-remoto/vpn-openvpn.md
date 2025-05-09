## 🛠️ Prerequisites

- OpenVPN server enabled on the router  
- Certificate generated and `.ovpn` file exported  
- Port forwarding or active DMZ  
- OpenVPN client installed

---

## 🌐 Connection Details

> Exact data (public IP, keys) is not published for security reasons. It is documented in the private repository.

- **Port:** `1194`  
- **Protocol:** `UDP`  
- **VPN Subnet:** `10.8.0.0/24`  
- **Configuration File:** `.ovpn`  
- **Access Mode:** Internal network only (in testing) → external access pending

---

## ✅ Tests Performed

- ✅ Connection from internal device  
- ⏳ Connection from external network (pending DMZ setup)

---

## 📁 Related Files

- OpenVPN server configuration (see `myprivateserver-config/vpn/openvpn-servidor.md`)


---

✍️ Autor: Gilmer  
📁 Proyecto: myprivateserver  
