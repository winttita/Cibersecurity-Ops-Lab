# Portafolio de Operaciones de Ciberseguridad (SecOps)

¡Hola! Soy un Analista de Ciberseguridad enfocado en **Defensa Activa (Blue Team)**, **Hacking Ético (Red Team)** e **Ingeniería de Detección**.
Este repositorio documenta mi laboratorio práctico ("Home Lab") donde simulo el ciclo de vida completo de un ciberataque para desarrollar contramedidas efectivas.

## Metodología "Purple Team"
El proyecto sigue la filosofía **"Learning by Doing"**, integrando ofensiva y defensiva:
1.  **Infrastructure:** Despliegue de entornos aislados (Sandbox) y gestión de logs.
2.  **Offense:** Ejecución de la "Cyber Kill Chain" (Reconocimiento, Armamento, Explotación).
3.  **Defense:** Monitoreo con SIEM (Splunk), análisis forense y automatización de alertas.

---

## Módulos Completados

### 🔹 Infraestructura y Redes
* **[Módulo 1: El Laboratorio (Sandbox)](./Modulo-1-Laboratorio/README.md)**
    * *Tech:* VirtualBox, Kali Linux, Redes Host-Only.
    * *Skill:* Virtualización y aislamiento de entornos críticos.
* **[Módulo 2: Análisis de Tráfico](./Modulo-2-Analisis-De-Red/README.md)**
    * *Tech:* Wireshark, TCP/IP, Telnet.
    * *Skill:* Packet Sniffing e identificación de credenciales en texto plano.

### Red Team (Ofensiva)
* **[Módulo 3: Explotación de Vulnerabilidades](./Modulo-3-Explotacion/README.md)**
    * *Tech:* Nmap, Metasploit, vsftpd Backdoor.
    * *Skill:* Escaneo de puertos, explotación de servicios y escalada de privilegios a Root.

### Blue Team (Defensiva & Forense)
* **[Módulo 4: Forense Digital Manual](./Modulo-4-Forense-Manual/README.md)**
    * *Tech:* Linux Logs (Auth/Syslog), Netstat, Grep.
    * *Skill:* Threat Hunting manual y detección de Reverse Shells activas.
* **[Módulo 5: Despliegue de SIEM](./Modulo-5-SIEM-Splunk/README.md)**
    * *Tech:* Splunk Enterprise, Syslog (UDP 514).
    * *Skill:* Centralización de logs e ingeniería de ingesta de datos.
* **[Módulo 6: Automatización de Alertas](./Modulo-6-Defensa-Automatizada/README.md)**
    * *Tech:* Splunk Alerts, Cron Scheduling, Detection Rules.
    * *Skill:* **Detection Engineering:** Creación de reglas automatizadas para bloquear ataques de Fuerza Bruta en tiempo real.

---

## Stack Tecnológico Dominado
| Área | Herramientas |
| :--- | :--- |
| **Sistemas** | Kali Linux, Debian, Windows (Virtualización) |
| **SIEM & Logs** | **Splunk Enterprise**, Syslog-ng, Rsyslog |
| **Redes** | Wireshark, Nmap, Netstat, SSH Tunneling |
| **Pentesting** | Metasploit Framework, Burp Suite (Básico) |

---
*Este portafolio demuestra capacidad técnica práctica para roles de Analista SOC, Incident Responder y Pentester Junior.*
