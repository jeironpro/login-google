# login-google

## 📌 Descripción

Este proyecto forma parte de mi portafolio personal.  
El objetivo es demostrar buenas prácticas de programación, organización y documentación en GitHub.

## 🛠️ Uso

Clonar el repositorio:

```bash
git clone https://github.com/jeironpro/login-google.git
cd login-google
```

Crear y activar entorno virtual:
```bash
python -m venv venv


source venv/bin/activate (Linux)
.\env\Scripts\activate (Windows)
```

Instalar las dependencias:

```bash
pip install -r requirements.txt
```

Crear el archivo .env en la raiz del proyecto con las siguientes variables:

```bash
GOOGLE_CLIENT_ID=tu_cliente_id_google_cloud_app
GOOGLE_CLIENT_SECRET=tu_cliente_secret_google_cloud_app
DATABASE=sqlite_db # Se puede cambiar por el URL / DSN de tu base de datos
OAUTHLIB_INSECURE_TRANSPORT=1 # Se usa para permitir el protocolo HTTP en oauthlib
```

Iniciar el servidor de desarrollo de Flask:

```bash
python app.py
```

## 📜 Licencia

Este proyecto está bajo la licencia **MIT**.  
Consulta el archivo [LICENSE](LICENSE) para más detalles.
