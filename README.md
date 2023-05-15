# SqlConnectionGeo
Librería de conexión mediante UserSecret

## Configurar los NuGets externos
 %AppData%\NuGet\
 
    <add key="NetCore NuGet" value="your_path/NuGet/SqlConnectionGeo/netcore"/>
    
## Configurar user-secret

### En el CMD ejecutar el comando:
 dotnet user-secrets init

### En la siguiente ubicación 
%APPDATA%\Microsoft\UserSecrets\

* Crear la carpeta \SQL_CONEXION
* Crear el archivo secrets.json con la siguiente estructura
```json
{
  "ConnectionString:0:Key": "KEY_NAME",
  "ConnectionString:0:UserValue": "USER_DATABASE",
  "ConnectionString:0:PasswordValue": "PASSWORD_DATABASE",
  "ConnectionString:0:DataSourceValue": "DATASOURCE_DATABASE",
  "ConnectionString:0:CatalogValue": "NAME_OF_DATABASE",
 }
 ```
