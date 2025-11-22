### **Curso de Capacitación: De Cero a Junior IT Support & SysAdmin**

**Objetivo del Curso:** Al finalizar, el participante será capaz de resolver problemas comunes de hardware y software, administrar usuarios y servicios básicos en un entorno de red corporativo, entender los fundamentos de redes y seguridad, y operar con las mejores prácticas de la industria.

**Filosofía:** "Aprender haciendo". Cada módulo teórico debe ir acompañado de prácticas en un entorno controlado (laboratorio virtual).

---

### **Módulo 1: Fundamentos y el Rol del Profesional de TI (1 semana)**

*   **Objetivo:** Entender el rol, las responsabilidades y las herramientas de comunicación.
*   **Temas:**
    *   **¿Qué es y para qué sirve un departamento de TI?** El objetivo es habilitar al negocio, no solo "arreglar computadoras".
    *   **El Triángulo del Soporte:** Usuario - Hardware - Software.
    *   **Habilidades Blandas (Soft Skills) CRÍTICAS:**
        *   Comunicación efectiva: Cómo hablar con usuarios no técnicos, empatía y paciencia.
        *   Etiqueta profesional: Email, chat y teléfono.
        *   Mentalidad de resolución de problemas (Troubleshooting Mindset).
    *   **Herramientas del Día a Día:**
        *   **Sistemas de Ticketing (Teoría y Práctica):** ¿Qué son? (Jira Service Management, ServiceNow, etc.). Ciclo de vida de un ticket: Creación, asignación, trabajo en progreso, resolución, cierre.
            *   **Video Sugerido:** [¿Qué es un sistema de Help Desk y Ticketing?](https://www.youtube.com/watch?v=QL_y-_y-aI0)
        *   **Bases de Conocimiento (Knowledge Base):** La importancia de documentar TODO. Cómo leer y cómo crear un artículo de conocimiento básico.
    *   **Conceptos Básicos de ITIL (versión simple):** Incidente, Requerimiento, Problema y Cambio.
        *   **Video Sugerido:** [Introducción a ITIL 4 en Español](https://www.youtube.com/watch?v=_4U_4Y-Vj8E)

---

### **Módulo 2: Soporte al Usuario Final y Hardware (1 semana)**

*   **Objetivo:** Diagnosticar y resolver problemas comunes de hardware y periféricos.
*   **Temas:**
    *   **Anatomía de un PC/Laptop:** CPU, RAM, Disco Duro (HDD vs. SSD), Placa base, Fuente de poder.
        *   **Video Sugerido:** [Componentes de una PC para Principiantes](https://www.youtube.com/watch?v=nC-s_4s-w-I)
    *   **Metodología de Troubleshooting (Diagnóstico):**
        1.  Identificar el problema (hacer las preguntas correctas).
        2.  Establecer una teoría de la causa probable.
        3.  Probar la teoría para determinar la causa.
        4.  Establecer un plan de acción y ejecutarlo.
        5.  Verificar la funcionalidad completa.
        6.  Documentar la solución.
        *   **Video Sugerido:** [Metodología para Diagnosticar Fallas en PC](https://www.youtube.com/watch?v=8e5-iL3_5_A)
    *   **Casos Prácticos Comunes:**
        *   "Mi PC no enciende" (cables, fuente, etc.).
        *   "Mi PC está muy lenta" (Task Manager, uso de RAM/CPU/Disco, malware básico).
        *   "No puedo imprimir" (drivers, cola de impresión, conectividad de red).
    *   **Manejo de Periféricos:** Monitores, teclados, ratones, docking stations.

---

### **Módulo 3: Sistemas Operativos Cliente (2 semanas)**

*   **Objetivo:** Dominar la administración y troubleshooting de los sistemas operativos más comunes en empresas.
*   **Temas:**
    *   **Windows (Enfoque Principal):**
        *   Panel de Control vs. Configuración.
        *   Administración de cuentas de usuario locales.
        *   Sistema de archivos NTFS y permisos básicos.
            *   **Video Sugerido:** [Permisos NTFS y Carpetas Compartidas](https://www.youtube.com/watch?v=f3h_i2_jPqQ)
        *   Herramientas clave: Administrador de Tareas, Visor de Eventos, Administrador de Discos, `msconfig`, `sfc /scannow`.
            *   **Video Sugerido:** [Cómo usar el Visor de Eventos de Windows](https://www.youtube.com/watch?v=5-8GDMw03gE)
        *   Instalación y desinstalación de software.
    *   **macOS:**
        *   Preferencias del Sistema.
        *   Cuentas de usuario.
        *   Utilidad de Discos y Monitor de Actividad.
        *   Concepto de Time Machine para backups.
    *   **Linux (Introducción):**
        *   Concepto de distribuciones (Ubuntu como ejemplo).
        *   Terminal básica: `ls`, `cd`, `pwd`, `sudo`, `apt get`, `ping`, `ifconfig`. El objetivo es que no le tema a la pantalla negra.
            *   **Video Sugerido:** [Comandos Básicos en la Terminal de Linux](https://www.youtube.com/watch?v=x-32P3_nB-8)

---

### **Módulo 4: Redes para SysAdmin (2 semanas)**

*   **Objetivo:** Entender cómo se comunican los dispositivos para poder diagnosticar problemas de conectividad.
*   **Temas:**
    *   **Modelo OSI y TCP/IP (Versión Práctica):** ¿Para qué sirve? Cables (Capa 1), Switches y MAC (Capa 2), Routers e IP (Capa 3).
        *   **Video Sugerido:** [El Modelo OSI Explicado Fácil](https://www.youtube.com/watch?v=--OutyqH6-c)
    *   **Direccionamiento IP:**
        *   IPv4, Máscara de subred (qué significa `255.255.255.0`), Puerta de enlace (Gateway).
        *   IP Estática vs. Dinámica (DHCP).
        *   **Video Sugerido:** [¿Qué es una Dirección IP, Subred y Gateway?](https://www.youtube.com/watch?v=g_g-8_jP_So)
    *   **Servicios de Red Esenciales:**
        *   **DHCP:** ¿Cómo un dispositivo obtiene una IP automáticamente?
        *   **DNS:** ¿Cómo `www.google.com` se convierte en una IP? El "directorio telefónico" de internet.
        *   **Video Sugerido:** [¿Cómo funcionan DNS y DHCP?](https://www.youtube.com/watch?v=RY_3S3q-A4I)
    *   **Herramientas de Diagnóstico de Red:**
        *   `ping`: ¿Está "vivo" el otro dispositivo?
        *   `ipconfig` / `ifconfig`: ¿Qué configuración de red tengo?
        *   `nslookup`: ¿Está funcionando el DNS?
        *   `tracert` / `traceroute`: ¿Por dónde se va mi conexión?
        *   **Video Sugerido:** [Uso de Ping, IPConfig, NSLookup y Tracert](https://www.youtube.com/results?search_query=como+usar+ping+ipconfig+nslookup+tracert+español)
    *   **Fundamentos de Wi-Fi:** SSID, WPA2/WPA3, Canales.

---

### **Módulo 5: Administración de Servidores y Servicios Centrales (2 semanas)**

*   **Objetivo:** Aprender a gestionar los recursos centralizados de la empresa. El corazón del rol de SysAdmin junior.
*   **Temas:**
    *   **Virtualización (Concepto):** ¿Qué es una Máquina Virtual (VM)? ¿Qué son VMware vSphere y Microsoft Hyper-V?
        *   **Video Sugerido:** [¿Qué es la Virtualización? (VMware, Hyper-V)](https://www.youtube.com/watch?v=Z_g0kHkI21k)
    *   **Windows Server (Introducción):** Roles y características.
    *   **Active Directory (AD) - El Más Importante:**
        *   Crear, modificar y eliminar usuarios.
        *   Resetear contraseñas.
        *   Unidades Organizativas (OUs).
        *   Grupos de Seguridad y Grupos de Distribución.
        *   Unir una computadora al dominio.
        *   **Video Sugerido:** [Active Directory para Principiantes (Usuarios y Grupos)](https://www.youtube.com/watch?v=JMMo-yDrD-4)
    *   **Servidores de Archivos (File Servers):**
        *   Crear carpetas compartidas.
        *   Diferencia entre Permisos de Recurso Compartido (Share) y Permisos NTFS.
        *   **Video Sugerido:** [Permisos en Carpetas Compartidas vs NTFS](https://www.youtube.com/watch?v=f3h_i2_jPqQ)
    *   **Servidores de Impresión:** Cómo se comparte una impresora en la red.

---

### **Módulo 6: Seguridad Informática Práctica (1 semana)**

*   **Objetivo:** Entender las amenazas comunes y cómo aplicar las primeras líneas de defensa.
*   **Temas:**
    *   **Principio de Menor Privilegio:** Dar solo los permisos necesarios.
    *   **Tipos de Amenazas:** Virus, Malware, Ransomware, Phishing.
        *   **Video Sugerido:** [¿Qué es el Phishing y el Malware?](https://www.youtube.com/watch?v=Yt-5-A3w2eA)
    *   **Defensas Comunes:**
        *   Antivirus y Antimalware.
        *   Firewall (concepto básico).
        *   Importancia crítica de las actualizaciones (Patching).
        *   **Autenticación Multifactor (MFA):** Qué es y por qué es vital.
            *   **Video Sugerido:** [¿Qué es la Autenticación de Doble Factor (MFA)?](https://www.youtube.com/watch?v=M-hB_m4nKjA)
    *   **El Rol del Soporte en la Seguridad:** Educar al usuario final.

---

### **Módulo 7: Introducción a la Automatización (1 semana)**

*   **Objetivo:** Dar el primer paso para dejar de ser reactivo y empezar a ser proactivo.
*   **Temas:**
    *   **¿Por qué automatizar?** Ahorrar tiempo, reducir errores.
    *   **Scripts Básicos de CMD (Batch):** `ipconfig /all > net_info.txt`, `gpupdate /force`.
    *   **Introducción a PowerShell (Windows):**
        *   La consola y el ISE.
        *   Estructura Verbo-Sustantivo (`Get-Help`, `Get-Process`, `Get-Service`).
        *   Ejemplos simples: Obtener la lista de usuarios locales, verificar el estado de un servicio.
        *   **Video Sugerido:** [PowerShell para Principiantes - Tutorial](https://www.youtube.com/watch?v=j_B2r5F6p_Q)
    *   **Introducción a Bash (Linux):** Scripts simples para listar archivos o verificar espacio en disco.
        *   **Video Sugerido:** [Bash Scripting para Principiantes - Tutorial](https://www.youtube.com/watch?v=E-0cbtHnQUA)

---

### **Sugerencia de Implementación:**

*   **Laboratorio en Casa/Virtual:** Es indispensable que el participante tenga un entorno para practicar. Se puede usar VirtualBox (gratuito) para instalar:
    *   1 x Windows Server (la versión de evaluación dura 180 días).
    *   2 x Windows 10/11 (se pueden usar sin activar para pruebas).
    *   1 x Ubuntu Desktop.
*   **Proyecto Final:** Simular un caso real de principio a fin. "Un nuevo empleado, Juan Pérez, se une a la empresa. Realiza todo el proceso de onboarding: crea su usuario en AD, asígnale los grupos correctos, prepara su laptop con el software estándar y documenta el proceso en un ticket de ejemplo".