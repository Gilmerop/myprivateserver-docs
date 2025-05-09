# Acceso Remoto por VPN (OpenVPN)

Guía para conectarse de forma remota a la red doméstica a través de un servidor OpenVPN instalado en el router TP-Link AX55, como parte del proyecto **myprivateserver**.

---

## 🎯 Objetivo

Permitir el acceso seguro a recursos internos desde el exterior usando un cliente VPN (Windows, Android, etc.).

---

## 🛠 Requisitos previos

- Servidor OpenVPN habilitado en el router
- Certificado generado y archivo `.ovpn` exportado
- Redireccionamiento de puerto o DMZ activo
- Cliente OpenVPN instalado

---

## 🌐 Datos de conexión

> Los datos exactos (IP pública, claves) no se publican por seguridad. Están documentados en el repositorio privado.

- **Puerto:** `1194`
- **Protocolo:** `UDP`
- **Subred VPN:** `10.8.0.0/24`
- **Archivo de configuración:** `.ovpn`
- **Modo de acceso:** Solo red interna (en pruebas) → pendiente acceso externo

---

## 🧪 Pruebas realizadas

- ✅ Conexión desde dispositivo interno
- 🔜 Conexión desde red externa (en espera de DMZ)

---

## 📂 Archivos involucrados

- Configuración del servidor OpenVPN (ver `myprivateserver-config/vpn/openvpn-servidor.md`)

---

✍️ Autor: Gilmer  
📁 Proyecto: myprivateserver  
