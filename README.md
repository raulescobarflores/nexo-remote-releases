# Nexo Remote — Descargas y Versiones (Releases)

[![Plataforma](https://img.shields.io/badge/Plataforma-Windows-blue.svg?style=for-the-badge&logo=windows)](https://www.microsoft.com/store)
[![Licencia](https://img.shields.io/badge/Licencia-Propia-orange.svg?style=for-the-badge)](#)

Este repositorio contiene las compilaciones oficiales y de acceso directo para **Nexo Remote v1.0.0**. Puedes descargar el formato que mejor se adapte a tus necesidades de instalación.

---

## 🚀 Enlaces de Descarga Directa

Selecciona uno de los siguientes instaladores para descargar la última versión de forma instantánea:

| Formato | Tipo de Instalador | Enlace de Descarga | Recomendado para |
| :--- | :--- | :--- | :--- |
| **`.exe`** | Ejecutable / Instalador NSIS | [**Descargar Nexo Remote Setup 1.0.0.exe**](https://github.com/raulescobarflores/nexo-remote-releases/raw/main/Nexo%20Remote%20Setup%201.0.0.exe) | Usuarios generales (instalación fácil e interactiva). |
| **`.msi`** | Instalador de Windows (Windows Installer) | [**Descargar Nexo Remote 1.0.0.msi**](https://github.com/raulescobarflores/nexo-remote-releases/raw/main/Nexo%20Remote%201.0.0.msi) | Despliegues corporativos, políticas de grupo (GPO) o instalación silenciosa. |
| **`.appx`** | Paquete de Aplicación de Windows | [**Descargar Nexo Remote 1.0.0.appx**](https://github.com/raulescobarflores/nexo-remote-releases/raw/main/Nexo%20Remote%201.0.0.appx) | Carga local (sideloading) o pruebas previas a la Microsoft Store. |

---

## 🛠️ Instrucciones de Instalación

### Opción 1: Instalador Estándar (`.exe`)
1. Descarga el archivo [Nexo Remote Setup 1.0.0.exe](https://github.com/raulescobarflores/nexo-remote-releases/raw/main/Nexo%20Remote%20Setup%201.0.0.exe).
2. Haz doble clic en el archivo descargado.
3. Sigue los pasos del asistente de instalación interactivo.

### Opción 2: Instalador MSI (`.msi`)
1. Descarga [Nexo Remote 1.0.0.msi](https://github.com/raulescobarflores/nexo-remote-releases/raw/main/Nexo%20Remote%201.0.0.msi).
2. Ejecuta el archivo para instalar la aplicación para todos los usuarios o en el directorio predeterminado del sistema.
3. *Para administradores:* Puedes instalarlo de forma silenciosa desde la consola de comandos (cmd) con permisos de administrador usando:
   ```cmd
   msiexec /i "Nexo Remote 1.0.0.msi" /qn
   ```

### Opción 3: Paquete de Windows Store (`.appx`)
1. Descarga el paquete [Nexo Remote 1.0.0.appx](https://github.com/raulescobarflores/nexo-remote-releases/raw/main/Nexo%20Remote%201.0.0.appx).
2. Asegúrate de tener activado el **Modo de programador** en tu sistema Windows (*Configuración > Privacidad y seguridad > Para programadores > Modo de programador*).
3. Haz doble clic en el archivo `.appx` e inicia el instalador de aplicaciones de Windows para cargar la aplicación localmente.

---

## 🔒 Seguridad y Privacidad (Local-First)
Nexo Remote está diseñada bajo el principio de **privacidad local absoluta**:
* **Sin base de datos externa:** Tus credenciales de acceso remoto RDP no se suben a ningún servidor externo.
* **Cifrado del Sistema:** Las contraseñas se almacenan de forma local en tu computadora cifradas mediante la API de protección de datos de Windows (`safeStorage`).
* **Seguridad de sesión:** Las credenciales y los archivos temporales de conexión se eliminan automáticamente del sistema a los 20 segundos de haber iniciado el escritorio remoto.

