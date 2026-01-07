# Módulo 3: Explotación de Vulnerabilidades (Red Team)

## Objetivo
Identificar y explotar una vulnerabilidad crítica en un servicio expuesto para obtener acceso administrativo total (Root) sin credenciales previas.

## Kill Chain
1.  **Reconocimiento:** `nmap -sV` detectó `vsftpd 2.3.4` en el puerto 21.
2.  **Armamento:** Se seleccionó el exploit `vsftpd_234_backdoor` en Metasploit.
3.  **Entrega/Explotación:** El exploit activó la puerta trasera (backdoor) conocida de esta versión.
4.  **Acciones en Objetivos:** Se obtuvo una Shell remota con privilegios de `root`.

## Evidencia de Compromiso
![Shell Root](./Exploit-exitoso.)
*La terminal confirma el acceso con `uid=0(root)`, otorgando control total sobre el servidor víctima.*
