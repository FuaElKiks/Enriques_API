# 🧮 Calculadora de IMC con Registro y Login (Flask + MySQL)

Este es un proyecto web desarrollado con Flask que permite a los usuarios registrarse, iniciar sesión y calcular su IMC (Índice de Masa Corporal). El sistema almacena los datos personales y genera mensajes personalizados según el resultado del IMC.

---

## 🚀 Características

- Registro de usuarios con contraseñas encriptadas
- Login seguro con sesiones y JWT
- Almacenamiento de datos en MySQL
- Cálculo automático del IMC con feedback de salud
- Interfaz responsiva con CSS personalizado
- Flash messages dinámicos (errores, éxito, advertencias)
- Ruta protegida accesible solo con token JWT

---

## 🛠️ Tecnologías usadas

- Python 3
- Flask
- Flask-JWT-Extended
- MySQL + mysql-connector-python
- Werkzeug (hashing de contraseñas)
- HTML5 + CSS3 (responsive)

---

## 🖼️ Capturas

### 🏠 Página de inicio
![inicio](./screenshots/index.png)

### 🔐 Registro
![registro](./screenshots/register.png)

### 🧾 Formulario de datos IMC
![formulario](./screenshots/formulario.png)

---

## 📦 Instalación local

1. **Clona este repositorio:**
   ```bash
   git clone https://github.com/tuusuario/flask-imc-app.git
   cd flask-imc-app
