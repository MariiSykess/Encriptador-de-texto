# Encriptador de Texto

Este proyecto es una aplicación web simple para encriptar y desencriptar textos. Permite a los usuarios transformar un texto de entrada en un mensaje encriptado y luego revertir el proceso para obtener el texto original.

## Características

- **Encriptar Texto**: Convierte un texto utilizando las siguientes reglas:
  - `e` -> `enter`
  - `i` -> `imes`
  - `a` -> `ai`
  - `o` -> `ober`
  - `u` -> `ufat`
- **Desencriptar Texto**: Revertir el texto encriptado a su forma original.
- **Copiar Texto**: Permite copiar el texto encriptado o desencriptado al portapapeles.

## Uso

1. Ingresa el texto en el área designada.
2. Haz clic en "Encriptar" para encriptar el texto.
3. Si quieres revertir el texto encriptado, ingresa el texto y haz clic en "Desencriptar".
4. Utiliza el botón "Copiar" para copiar el resultado al portapapeles.

## Estructura del Proyecto

- `index.html`: Contiene la estructura principal de la página.
- `styles/style.css`: Contiene los estilos CSS para la interfaz de usuario.
- `js/encriptador.js`: Contiene el código JavaScript que maneja la lógica de encriptación y desencriptación.

## Requisitos

- Un navegador web moderno.
- Conexión a Internet (para cargar las fuentes y los íconos).

## Instalación

1. Clona el repositorio a tu máquina local.
   ```bash
   git clone https://github.com/tu_usuario/encriptador-texto.git
