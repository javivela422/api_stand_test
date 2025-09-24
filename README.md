### 🧪 Pruebas para la creación de usuarios

Esta sección cubre las pruebas automatizadas para validar el proceso de creación de usuarios en el sistema.

#### 📦 Requisitos previos

Asegúrate de tener instalados los siguientes paquetes:

```bash
pip install pytest requests
```

#### 🚀 Ejecución de pruebas

Puedes ejecutar las pruebas de dos maneras:

- **Desde la terminal**:

  ```bash
  pytest
  ```

- **Desde PyCharm**:
  - Usa la consola integrada.
  - O haz clic derecho sobre el archivo de prueba y selecciona **"Run"** para usar la interfaz gráfica.

#### ✅ Qué se prueba

Las pruebas verifican:

- Que se pueda crear un usuario con parámetros válidos.
- Que se manejen correctamente los errores al ingresar datos inválidos.
- Que el sistema responda con los códigos de estado esperados (por ejemplo, 201 para creación exitosa, 400 para errores de validación).
- Que el usuario creado contenga los atributos esperados (nombre)