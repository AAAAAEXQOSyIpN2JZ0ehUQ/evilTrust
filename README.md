
# ?????? EvilTrust by s4v1tar - Custom README

?? **Descripción**  
EvilTrust es un script avanzado de Bash diseñado para convertir un dispositivo Linux en un punto de acceso malicioso (*rogue AP*), ideal para pruebas de penetración y auditorías de seguridad WiFi. Este script permite capturar credenciales, interceptar tráfico, y realizar ataques de ingeniería social mediante la creación de redes falsas y portales cautivos.  

?? **Instalación**  
Clona el repositorio y prepara el entorno:  
```bash
git clone https://github.com/s4v1tar/EvilTrust.git
cd EvilTrust
sudo chmod +x eviltrust.sh
sudo ./eviltrust.sh
```

?? **Modo de Uso**  
Al ejecutar el script, selecciona entre los diversos modos de ataque disponibles, como:  
- Crear un *Rogue AP* con portal cautivo.  
- Configurar sniffing de tráfico HTTP/HTTPS.  
- Simular redes WiFi conocidas para engañar dispositivos cercanos.  

Ejemplo de ejecución:  
```bash
sudo ./eviltrust.sh
```

?? **Requisitos**  
- **Sistema Operativo**: Linux (Kali Linux, Raspberry Pi OS, etc.)  
- **Hardware**: Tarjeta WiFi compatible con modo monitor y AP.  
- **Dependencias**:  
  - `hostapd`  
  - `dnsmasq`  
  - `iptables`  

?? **Notas adicionales**  
El script es ideal para:  
- Auditorías de seguridad en redes WiFi.  
- Simulación de ataques de ingeniería social.  
- Captura de tráfico en entornos controlados.  

?? **Importante**  
Este script debe ser utilizado únicamente con fines éticos y en entornos donde tengas autorización explícita.  

---

# ??? Demos y Ejemplos

Aquí tienes algunos ejemplos de uso del script EvilTrust en acción:  

### 1?? **Configuración de un Rogue AP con portal cautivo falso**  
Captura de credenciales mediante un entorno controlado.  
![Demo 1 - Portal Cautivo](https://your-demo-link.com/demo1.png)  

### 2?? **Sniffing de tráfico HTTP/HTTPS**  
Interceptación de tráfico para auditorías en tiempo real.  
![Demo 2 - Sniffing Tráfico](https://your-demo-link.com/demo2.png)  

### 3?? **Simulación de redes WiFi conocidas**  
Desautenticación y redirección a una red falsa.  
![Demo 3 - Redes Simuladas](https://your-demo-link.com/demo3.png)  

> ?? **Nota**: Sustituye los enlaces `https://your-demo-link.com` por URLs reales donde tengas alojadas las capturas o ejemplos.

---

?? **Características**  
- Automatización total para pruebas de seguridad WiFi.  
- Soporte para múltiples modos de ataque.  
- Herramienta liviana y personalizable.  

??? **Colaboradores**  
- ?? s4v1tar  
- ?? Gato  

?? **Contacto**  
Si tienes preguntas o sugerencias:  
- ?? Contacta a [s4v1tar](https://github.com/s4v1tar).  
- ?? Gato, adaptaciones personalizadas.  

?? **Repositorio oficial**  
[EvilTrust GitHub](https://github.com/s4v1tar/EvilTrust)
