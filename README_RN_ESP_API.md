<p align="center">
  <img src="https://github.com/Ationet/ationetdocs/raw/master/Content/Images/ATIOnetLogo_250x70.png" />
</p>

|**Información del Documento**||
|--- |--- |
|**Archivo:**|README_RN_ESP_Console.md|
|**Versión Doc:**|1.0|
|**Fecha Liberación:**|Dic 12, 2024|
|**Autor:**|ATIONET LLC|

|**Bitácora de Cambios**|||
|--- |--- |--- |
|**Versión**|**Fecha**|**Resumen de Cambios**|
|1.0|12/Dic/2024|- Versión Inicial

# Contents
-[API Native](#api-native)

-[API Rest](#api-rest)

# API Native

### 02 Diciembre 2024
- El rol de CPInterfaceAPI ahora se podra asignar a multiples compañias con el mismo usuario


# API Rest

### 02 Diciembre 2024
- Cambio en API Rest Users para no notificar usuarios
  - Se agrega un nuevo parámetro booleano a la API https://api.ationet.com/Users que permite indicar si se le enviará o no el correo de bienvenida a ATIONET al usuario creado (o al cual se le agrega el nuevo rol).
    Dicho parámetro, por defecto permitirá el envío del correo de bienvenida al usuario.
    
