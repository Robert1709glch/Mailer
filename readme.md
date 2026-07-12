# [Nombre del Proyecto / Ejemplo: Aplicación de Envíos con Flask]

Este es un proyecto práctico desarrollado como parte de mi aprendizaje en Python y desarrollo web. La aplicación permite gestionar [menciona brevemente qué hace, ej: el registro de usuarios y envío de notificaciones por correo].

---

## 📚 Créditos y Origen

Este proyecto fue construido siguiendo las bases del curso **"[Nombre del Curso Aquí]"** impartido por **[Nombre del Profesor o Plataforma, ej: Udemy, Alura, Código Facilito]**. 

Agradezco al instructor por el material y las explicaciones. Como parte de mi toque personal y mejora del proyecto, implementé los siguientes cambios respecto al curso original:
* Migración del motor de correos de SendGrid a **Resend** para optimizar el proceso de envío y autenticación.
* Manejo de variables de entorno seguras mediante `.env`.

---

## 🛠️ Tecnologías Utilizadas

* **Python 3**
* **Flask** (Framework web)
* **Resend SDK** (Para el envío de correos electrónicos)
* **MYSQL** (La base de datos)

---

## 🚀 Instalación y Uso

Si deseas ejecutar este proyecto localmente, sigue estos pasos:

1. **Clonar el repositorio:**
   ```bash
   git clone [Link_de_tu_repositorio_de_GitHub]
   cd [Nombre_de_la_carpeta]
   ```

2. **Crear e iniciar el entorno virtual**
    ```bash
    python -m venv venv
    # En Windows:
    .\venv\Scripts\activate
    # En Mac/Linux:
    source venv/bin/activate
    ```

3. **Instalar las dependencias**
    ```bash
    # En Windows:
    pip install -r requirements.txt
    ```

4. **Configurar variables de entorno**
    Crea un archivo ```.env``` en la raiz del proyecto, necesitarás una cuenta de Resend
    ```bash
    RESEND_KEY=tu_api_de_resend
    FROM_EMAIL=onboarding@resend.dev
    ```

5. **Ejecutar la app**
    ```bash
    flask run
    ```