# 🌐 Semana 1: Redes y Fundamentos (19/10 al 25/10)

## 📌 Resumen de la semana
Aquí documentaré mis avances, laboratorios de redes y prácticas con Wireshark y la línea de comandos de Linux.

---

## 📅 Actividades Diarias

### 🔹 Lunes: Teoría de Redes
* **Temas estudiados:** Modelo OSI, TCP/IP, direccionamiento IP, puertos y DNS.
* **Notas clave:**
  * **Modelo OSI y TCP/IP:** Estructura en capas para entender cómo viaja la información desde la aplicación hasta el medio físico. Las capas clave que conectan con la práctica son la **Capa 3 (Red)** con el direccionamiento IP y la **Capa 4 (Transporte)** con los protocolos de comunicación.
  * **TCP vs. UDP:** TCP es orientado a conexión y confiable (requiere el *3-way handshake*: SYN, SYN-ACK, ACK), ideal para integridad de datos. UDP es más rápido pero sin conexión ni garantía de entrega, usado en streaming o juegos.
  * **Direccionamiento y Puertos:** Las direcciones IP identifican los dispositivos en la red, mientras que los puertos (como el 80 para HTTP o el 443 para HTTPS) actúan como "puertas lógicas" para dirigir el tráfico al servicio correcto dentro de la máquina.
  * **DNS:** El sistema que traduce nombres de dominio legibles (ej. google.com) a direcciones IP numéricas.

### 🔹 Martes: Laboratorio en TryHackMe
* **Módulo:** Pre-Security / Network Fundamentals
* **Rooms completados:** `What is Networking?` (Tareas 1 a 5 completadas).
* **Conceptos nuevos / Aprendizajes:**
  * **Redes e Internet:** Comprensión de cómo los dispositivos se comunican entre sí y la estructura general del internet.
  * **IP vs. MAC Address:** Diferencia fundamental entre la dirección lógica (IP, asignada en red) y la dirección física/hardware (MAC, única de la tarjeta de red).
  * **Comando Ping (ICMP):** Aplicación práctica para verificar la conectividad, el estado de la comunicación y el tiempo de respuesta hacia una dirección IP objetivo.
* **Evidencias del laboratorio:**
  * ![Room Completado](img/room-completed.png)
  * ![Tareas Finalizadas](img/tasks-network.png)
* **Dudas pendientes / Preguntas para Wireshark:** Ninguna por el momento, todo claro para pasar al análisis de tráfico local.
  * 

### 🔹 Miércoles: Wireshark (Práctica local)
* **Captura de tráfico:** Análisis de handshake TCP, consultas DNS y peticiones HTTP.
* **Evidencias:** *(Sube capturas a una carpeta img/ y enlázalas aquí)*

### 🔹 Jueves: Comandos de Linux
* **Comandos practicados:** `ls`, `grep`, `netstat`, `ping`, etc.
* **Ejemplo de uso:** *(Algún comando útil que hayas probado)*
