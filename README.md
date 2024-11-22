
# ?????? EvilTrust by s4v1tar - Custom README

?? **Descripci�n**  
EvilTrust es un script avanzado de Bash dise�ado para convertir un dispositivo Linux en un punto de acceso malicioso (*rogue AP*), ideal para pruebas de penetraci�n y auditor�as de seguridad WiFi. Este script permite capturar credenciales, interceptar tr�fico, y realizar ataques de ingenier�a social mediante la creaci�n de redes falsas y portales cautivos.  

?? **Instalaci�n**  
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
- Configurar sniffing de tr�fico HTTP/HTTPS.  
- Simular redes WiFi conocidas para enga�ar dispositivos cercanos.  

Ejemplo de ejecuci�n:  
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
- Auditor�as de seguridad en redes WiFi.  
- Simulaci�n de ataques de ingenier�a social.  
- Captura de tr�fico en entornos controlados.  

?? **Importante**  
Este script debe ser utilizado �nicamente con fines �ticos y en entornos donde tengas autorizaci�n expl�cita.  

---

# ??? Demos y Ejemplos

Aqu� tienes algunos ejemplos de uso del script EvilTrust en acci�n:  

### 1?? **Configuraci�n de un Rogue AP con portal cautivo falso**  
Captura de credenciales mediante un entorno controlado.  
![Demo 1 - Portal Cautivo](https://your-demo-link.com/demo1.png)  

### 2?? **Sniffing de tr�fico HTTP/HTTPS**  
Interceptaci�n de tr�fico para auditor�as en tiempo real.  
![Demo 2 - Sniffing Tr�fico](https://your-demo-link.com/demo2.png)  

### 3?? **Simulaci�n de redes WiFi conocidas**  
Desautenticaci�n y redirecci�n a una red falsa.  
![Demo 3 - Redes Simuladas](https://your-demo-link.com/demo3.png)  

> ?? **Nota**: Sustituye los enlaces `https://your-demo-link.com` por URLs reales donde tengas alojadas las capturas o ejemplos.

---

?? **Caracter�sticas**  
- Automatizaci�n total para pruebas de seguridad WiFi.  
- Soporte para m�ltiples modos de ataque.  
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
