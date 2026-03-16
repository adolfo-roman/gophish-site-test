# Simulacro de Phishing - Landing Page (GoPhish)

Este repositorio contiene la página de aterrizaje (landing page) utilizada para una campaña de simulacro de phishing. Este proyecto forma parte de una práctica académica para la materia de **Seguridad Informática**.

## 🎯 Propósito del Proyecto

El objetivo principal es educar y concientizar a los usuarios sobre los riesgos del phishing. Cuando un usuario hace clic en el enlace de un correo electrónico de prueba (enviado mediante GoPhish), es redirigido a esta página.

En lugar de capturar credenciales o instalar malware, la página informa al usuario que ha interactuado con un correo de phishing simulado y proporciona recomendaciones clave para identificar y evitar amenazas reales en el futuro.

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructura de la página.
* **Tailwind CSS (CDN):** Estilos y diseño responsivo, sin necesidad de compilar archivos locales.
* **Lucide Icons (CDN):** Iconografía limpia y ligera para ilustrar las recomendaciones.

## 🚀 Despliegue en GitHub Pages

Esta página está diseñada para ser alojada de forma rápida y gratuita usando GitHub Pages.

1. Haz un *fork* o clona este repositorio en tu cuenta de GitHub.
2. Asegúrate de que el archivo principal se llame `index.html` y esté en la raíz del repositorio.
3. Ve a la pestaña **Settings** de tu repositorio.
4. En el menú lateral izquierdo, selecciona **Pages**.
5. En la sección *Build and deployment*, bajo *Source*, selecciona **Deploy from a branch**.
6. En *Branch*, selecciona `main` (o tu rama principal) y la carpeta `/ (root)`. Haz clic en **Save**.
7. En un par de minutos, GitHub te proporcionará la URL pública de tu página (ej. `https://tu-usuario.github.io/tu-repositorio/`).

## ⚙️ Configuración en GoPhish

Para conectar esta página con tu campaña de GoPhish:

1. Inicia sesión en tu panel de administración de GoPhish.
2. Ve a la sección **Landing Pages** y crea una nueva (o edita una existente).
3. Puedes optar por dos opciones:
   * **Opción A (Recomendada):** Pega directamente el código fuente de `index.html` en el editor HTML de GoPhish.
   * **Opción B:** Si estás capturando credenciales (solo como métrica, no para almacenarlas) y luego quieres redirigir al usuario, pon la URL de tu GitHub Pages en el campo **Redirect to** dentro de la configuración de la Landing Page.
4. Asegúrate de configurar correctamente tu **URL base** (la dirección de tu servidor GoPhish) al momento de lanzar la campaña (*Campaigns* > *URL*), ya que de ahí saldrán los enlaces en los correos.

## ⚠️ Descargo de Responsabilidad

Este material ha sido creado **única y exclusivamente con fines educativos**. No debe ser utilizado para realizar ataques reales, robo de credenciales, o cualquier actividad maliciosa o ilegal.
