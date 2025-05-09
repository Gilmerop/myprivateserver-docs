# 🛡️ Configuración de Servidor WireGuard - TP-Link AX55

Documentación de la futura implementación del servidor VPN **WireGuard** desde el router TP-Link AX55.

---

## 🔧 Requisitos previos

- Soporte para WireGuard habilitado en el router
- Generación de claves (privada, pública)
- Definición de pares permitidos (clientes)
- Redireccionamiento de puerto o DMZ activo
- Cliente WireGuard instalado (PC o móvil)

---

## 🌐 Datos de conexión

⚠️ *La IP pública y claves no se publican por seguridad. Datos técnicos están en el repositorio privado.*

- **Puerto:** `51820` (por defecto)
- **Protocolo:** `UDP`
- **Red virtual:** `10.8.x.x/24` o similar
- **Interface de red:** `wg0`
- **Claves:** almacenadas en repositorio privado

---

## ✅ Pruebas realizadas

- [ ] Conexión desde dispositivo interno
- [ ] Conexión desde red externa (en espera de DMZ)

---

## 📂 Archivos involucrados

- Configuración de WireGuard en el router:  
  `myprivateserver-config/vpn/wireguard-servidor.md`

- Archivos de configuración de clientes:  
  `myprivateserver-config/vpn/clients/` (uno por cliente)

---

👨‍💻 Autor: Gilmer  
📅 Última actualización: `{{coloca la fecha aquí}}`
