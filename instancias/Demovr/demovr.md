# [Pruebas funcionales](/README.md)

## Instancia Demovr

las pruebas se llevaron a cabo en el siguiente dominio [firmadocdemovr.login.portal-id.com](http://firmadocdemovr.login.portal-id.com/)

### Registro remitente CC

- **Prueba:**
  - Satisfactoria :white_check_mark:

- **Observaciones:**
  - El registro se realiza correctamente

### Enrolamiento CC

- **Prueba:**
  - Satisfactoria :white_check_mark:

- **Observaciones:**
  - El enrolamiento se realiza correctamente

### Verificación facial remitente

- **Prueba:**
  - Satisfactoria :white_check_mark:

- **Observaciones:**
  - La verificación facial se realiza correctamente

### Login usuario + contraseña + token Remiten

- **Prueba:**
  - Satisfactoria :white_check_mark:

- **Observaciones:**
  - El inicio de sesión se realiza correctamente

### Cargue de documento y firma por yo

- **Prueba:**
  - Satisfactoria :white_check_mark:

- **Observaciones:**
  - El cargue del documento y firma fueron satisfactorios

### Cargue de documento y firma por otros (validar registro, verificación y login con token de destinatario)

- **Prueba:**
  - Satisfactoria :white_check_mark:

- **Observaciones:**
  - El proceso del cargue y firma del documento se realiza satisfactoriamente

### Eliminar el segundo destinatario

- **Prueba:**
  - Incidencia :red_circle:

- **Observaciones:**
  - Bug: Al eliminar el segundo destinatario, se produce una actualización en la pagina que borra todos los datos del destinatario

### Cargue de documento y firma por Otros y yo (validar registro, verificación y login con token de destinatario)

- **Prueba:**
  - Satisfactoria :white_check_mark:

- **Observaciones:**
  - El proceso del cargue y firma del documento se realiza satisfactoriamente

### Crear carpeta

- **Prueba:**
  - Satisfactoria :white_check_mark:

- **Observaciones:**
  - La carpeta fue creada satisfactoria mente

### Copiar documentos a Carpeta

- **Prueba:**
  - Satisfactoria :white_check_mark:
  
- **Observaciones:**
  - Los documentos se copian a la carpeta seleccionada

### Descargar de certificado de registro perfil de datos

- **Prueba:**
  - Satisfactoria :white_check_mark:

- **Observaciones:**
  - El certificado se descarga correctamente

### Dibujar firmar, cargue de imagen de firma y fuente

- **Prueba:**
  - Satisfactoria :white_check_mark:

- **Observaciones:**
  - La firma dibujada, cargada y de fuente funcionan correctamente

### Usar mínimo 3 plantillas y firmarlas

- **Prueba:**
  - Satisfactoria :white_check_mark:

- **Observaciones:**
  - Los formatos se generan satisfactoriamente

### Editar datos de perfil

- **Prueba:**
  - Incidencia :red_circle:

    ![Foto error de editar perfil](./img/editar_perfil.png)

- **Observaciones:**
  - Solo deja editar el numero de teléfono, el campo dejar guardar el numero sin el código del país y con cualquier carácter.
