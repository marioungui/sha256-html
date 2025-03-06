# Encriptador SHA256 para Excel 🔐

Una aplicación web simple y segura que permite encriptar columnas específicas de archivos Excel utilizando el algoritmo SHA256. Todo el procesamiento se realiza localmente en el navegador del usuario, garantizando la privacidad de los datos.

## 🌟 Características

- Encriptación SHA256 de columnas seleccionadas en archivos Excel (.xlsx, .xls)
- Procesamiento 100% local (sin envío de datos a servidores externos)
- Vista previa de los datos procesados
- Descarga automática del archivo resultante con marca de tiempo
- Interfaz intuitiva y fácil de usar

## 🚀 Cómo usar

1. **Seleccionar archivo**
   - Haga clic en "Seleccionar archivo" y elija su archivo Excel
   - Solo se admiten formatos .xlsx y .xls

2. **Configurar campos**
   - Ingrese los nombres exactos de las columnas que desea encriptar
   - Puede agregar múltiples campos usando el botón "+ Agregar campo"
   - Los nombres de las columnas deben coincidir exactamente con los del archivo Excel

3. **Procesar y descargar**
   - Haga clic en "Procesar" para iniciar la encriptación
   - Revise la vista previa de las primeras 5 filas
   - Descargue el archivo procesado con el botón "Descargar Excel"

## 🔒 Privacidad y Seguridad

- La aplicación funciona completamente en el navegador
- Las únicas conexiones a Internet son para cargar las librerías necesarias:
  - XLSX.js (para procesamiento de Excel)
  - CryptoJS (para encriptación SHA256)
- Ningún dato es enviado o almacenado en servidores externos

## 🛠️ Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript (Vanilla)
- [SheetJS (XLSX)](https://github.com/SheetJS/sheetjs)
- [CryptoJS](https://github.com/brix/crypto-js)

## 📋 Requisitos

- Navegador web moderno con JavaScript habilitado
- Conexión a Internet (solo para la carga inicial de las librerías)

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor, siéntase libre de:
- Reportar bugs
- Sugerir nuevas características
- Crear pull requests

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - vea el archivo [LICENSE.md](LICENSE.md) para más detalles.
