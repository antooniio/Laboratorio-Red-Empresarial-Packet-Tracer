# Diseño y Fortificación de Red Empresarial

## 📌 Descripción

Proyecto desarrollado en Cisco Packet Tracer para simular una red empresarial segmentada y segura.

La solución implementa VLANs para separar departamentos, servicios de infraestructura (DHCP, DNS y Web) y controles de acceso mediante ACLs para proteger los recursos internos de la organización.

---

## 🎯 Objetivos

- Implementar segmentación lógica mediante VLANs.
- Configurar interconexión entre VLANs utilizando Router-on-a-Stick.
- Implementar DHCP para asignación automática de direcciones IP.
- Configurar servicios DNS y Web.
- Aplicar ACLs para restringir accesos no autorizados.
- Proteger la red inalámbrica mediante WPA2.

---

## 🛠 Tecnologías Utilizadas

- Cisco Packet Tracer
- VLAN
- Router-on-a-Stick
- DHCP
- DNS
- Access Control Lists (ACL)
- Wireless Networking
- WPA2 Security

---

## 🏗 Topología de Red

> Agregar aquí una captura de pantalla de la topología.

![Topologia](images/topologia.png)

---

## 📡 Segmentación VLAN

| VLAN | Área |
|--------|--------|
| 10 | Administración |
| 20 | Soporte Técnico |
| 30 | Visitantes (WiFi) |
| 40 | Servidores |

---

## 🔐 Medidas de Seguridad Implementadas

- Segmentación de red mediante VLANs.
- ACLs para restringir el acceso de visitantes a redes internas.
- WPA2 para acceso inalámbrico.
- Separación de recursos críticos en una VLAN dedicada.

---

## 🌐 Servicios Implementados

### DHCP
Asignación automática de direcciones IP para dispositivos clientes.

### DNS
Resolución de nombres para recursos internos.

### Web Server
Publicación de servicios web internos.

---

## ✅ Resultados

- Comunicación exitosa entre áreas autorizadas.
- DHCP funcional en todas las VLANs.
- Resolución DNS operativa.
- Acceso restringido para visitantes.
- Conectividad validada mediante pruebas de ping.

---

## 📂 Estructura del Proyecto

```text
lab-red-empresarial-packet-tracer/
│
├── README.md
├── docs/
│   └── Informe.pdf
│
├── packet-tracer/
│   └── RedEmpresarial.pkt
│
└── images/
    ├── topologia.png
    ├── vlan10.png
    ├── vlan20.png
    ├── vlan30.png
    └── servidor.png
```

## 📚 Aprendizajes Obtenidos

Durante este laboratorio reforcé conocimientos sobre:

- Diseño de redes empresariales.
- Segmentación mediante VLANs.
- Configuración de Router-on-a-Stick.
- Implementación de servicios de infraestructura.
- Aplicación de controles básicos de seguridad.
- Documentación técnica de proyectos de redes.

---

## 👨‍💻 Autor

**Robert Antonio De Jesus Cuevas**

Estudiante de Tecnologías de la Información enfocado en:

- Redes
- Infraestructura
- Administración de Sistemas
- Ciberseguridad
- Homelabs con Proxmox
