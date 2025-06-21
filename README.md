-----

```
 ██████╗░███████╗░█████╗░░█████╗░███╗░░██╗ ░██████╗░░█████╗░███████╗███████╗██████╗░  ██╗░░░██╗██████╗░██╗░░░░░ 
 ██╔══██╗██╔════╝██╔══██╗██╔══██╗████╗░██║ ██╔════╝░██╔══██╗╚════██║██╔════╝██╔══██╗  ██║░░░██║██╔══██╗██║░░░░░ 
 ██████╔╝█████╗░░██║░░╚═╝██║░░██║██╔██╗██║ ██║░░██╗░███████║░░███╔═╝█████╗░░██████╔╝  ██║░░░██║██████╔╝██║░░░░░ 
 ██╔══██╗██╔══╝░░██║░░██╗██║░░██║██║╚████║ ██║░░╚██╗██╔══██║██╔══╝░░██╔══╝░░██╔══██╗  ██║░░░██║██╔══██╗██║░░░░░ 
 ██║░░██║███████╗╚█████╔╝╚█████╔╝██║░╚███║ ╚██████╔╝██║░░██║███████╗███████╗██║░░██║  ╚██████╔╝██║░░██║███████╗ 
 ╚═╝░░╚═╝╚══════╝░╚════╝░░╚════╝░╚═╝░░╚══╝░ ╚═════╝░╚═╝░░╚═╝╚══════╝╚══════╝╚═╝░░╚═╝  ░╚═════╝░╚═╝░░╚═╝╚══════╝ 
```

-----

## 👁️‍🗨️ Descripción

**ReconGazer URL** es una herramienta sencilla pero potente, desarrollada en Python, diseñada para la **enumeración de enlaces** en páginas web. Como parte fundamental de la fase de reconocimiento (OSINT) en **Red Team**, esta herramienta te permite descubrir todos los enlaces (`<a>` tags) presentes en una URL objetivo, ayudándote a mapear la superficie de ataque y encontrar recursos ocultos o interesantes.

Desarrollada para pentesters en formación, **ReconGazer URL** prioriza la facilidad de uso y la efectividad en su tarea principal.

-----

## ✨ Características

  * **Extracción de Enlaces:** Rastrea una URL y extrae todos los enlaces HTML.
  * **Conversión a Absolutos:** Transforma enlaces relativos en absolutos para facilitar su acceso.
  * **Eliminación de Duplicados:** Presenta una lista limpia de enlaces únicos.
  * **Manejo de Errores:** Incluye gestión básica de errores de red y HTTP.

-----

## ⚠️ Advertencia de Uso Ético y Legal

**¡IMPORTANTE\!** Esta herramienta ha sido desarrollada con fines educativos y de seguridad ofensiva (Red Team) **ética**. El uso de **ReconGazer URL** para acceder, escanear o manipular sistemas sin la **autorización explícita, previa y por escrito del propietario** es **ilegal**.

**El creador y el desarrollador de esta herramienta no se hacen responsables del mal uso que se le pueda dar.** Utilízala siempre en entornos controlados, laboratorios de prueba o con el permiso legal adecuado. En Colombia, las actividades no autorizadas sobre sistemas informáticos son sancionadas penalmente bajo la **Ley 1273 de 2009**.

-----

## 🚀 Instalación y Uso

Sigue estos pasos para poner en marcha **ReconGazer URL** en tu sistema.

### 1\. **Clonar el Repositorio (Recomendado)**

Si tienes tu código en un repositorio de Git (como GitHub, GitLab, Bitbucket), el primer paso es clonarlo en tu máquina local.

```bash
git clone https://github.com/juanmcaicedo/recongazer_url.git
cd recongazer_url
```

### 2\. **Instalación de Dependencias**

**ReconGazer URL** requiere algunas librerías de Python. Asegúrate de tener `pip` (el gestor de paquetes de Python) instalado y actualizado.

1.  **Actualizar el sistema y `pip`:**

    ```bash
    sudo apt update
    sudo apt install python3-pip -y
    python3 -m pip install --upgrade pip
    ```

2.  **Instalar las librerías de Python:**

    ```bash
    python3 -m pip install requests beautifulsoup4
    ```

      * `requests`: Para realizar peticiones HTTP/HTTPS.
      * `beautifulsoup4`: Para parsear el HTML y extraer los enlaces.

### 3\. **Ejecutar la Herramienta**

Una vez que las dependencias estén instaladas, puedes ejecutar **ReconGazer URL** directamente desde la terminal.

```bash
python3 extrac_url_website.py
```

La herramienta te guiará pidiéndote que **ingreses la URL del sitio web objetivo**.

-----

