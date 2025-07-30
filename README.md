## CONFIGURACIÓN FONDO DE PANTALLA

### Paso 1  
Nos vamos a dirigir a la dirección:  
![Directorio del fondo de pantalla](/screenshots/directorio.png)  

Luego de acceder a esa ubicación y haber agregado nuestro nuevo fondo de pantalla, haremos que siempre esté presente al iniciar sesión.  
Para ello entraremos a esta dirección:  
![Modificación del archivo de configuración](/screenshots/parte1.png)  

Luego modificaremos el archivo `bspwmrc` para asignar la imagen deseada:  
![Edición de bspwmrc](/screenshots/parte2.png)  

---

## SOLUCIÓN TECLADO EN ESPAÑOL

### Paso 1  
Accedemos a una terminal y editamos el archivo de configuración:  
```bash
sudo nano /etc/vconsole.conf

# KEYBOARD CONFIGURATION FILE
# Consult the keyboard(5) manual page.

KEYMAP=es
XKBMODEL="pc105"
XKBLAYOUT="es"
XKBVARIANT=""
XKBOPTIONS=""
BACKSPACE="guess"

