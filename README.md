# ESTRELLADOS AL DEVTOOLS EAD

Snippets creados para mejorar la experiencia de desarrollo de BC del grupo estrellados.

## Caracteristicas

AL
* Crear procesos para escribir en un campo blob.
* Crear procesos para leer un campo blob.
* Agregar comentario para firmar codigo.
* Agregar comentario para firmar codigo en varias lienas.
* Agregar complemento para Findset repeater.
* Crear campo en pagina con tooltip.
* Crear plantilla para Notificacion.
* Crear plantilla para cambiar color de los campos en paginas.
* Crea proceso para verificar si un numero es multiplo de alguno.
* Proceso para enviar correo.
* Suscripción a un evento para remplazar report.
* API insert/modify.
* Accion para cargar blob.
* Algoritmo de ordenamiento bubbleSort
* Algoritmo de ordenamiento InsertionSort 
* Algoritmo de ordenamiento QuickSort 
* Algoritmo de ordenamiento cocktailSort  
* Factorial recursividad
* Manejar overflow en campos texto
* Cambiar idioma en report
* Función format mes report
* Cambiar fecha a texto para reports 
* Upgrade tags/gestionar CU de upgrade.
* Función para verificar si existe letra.
* Ejemplo de Gitignore que despues copiaremos al archivo gitignore.
* Version ampliada de snippet upgradetags.
* Traducciones usando expresiones regulares.
* Formato de fecha mediante la funcion Format.
* RegExp para encontrar fallos en fichero de traduccion.
* Bound Action a pagina WebService.
* Trabajar con Enum.
* Mostrar un campo en pagina y guardar otro en tabla.
* Mapear tabla en DB externa.
* Trabajar con Json anidados.
* TableRelation con condicional.
* Lanzar pruebas unitarias desde VSCode.
* Usar controlAddin para embeber Web dentro de Business Central.

DOCKER
* Crear contenedor Onpremise.
* Crear contenedor SandBox.
* Crear contenedor desde respaldo .bak. 
* Crear contenedor BD Externa. 
* Importar C/U de test.
* Extraer BaseApp desde un contenedor.
* Ver detalles de imagen antes de descargar.
* Ver ayuda navcontainerhelper.
* Copiar archivo de contenedor a local.
* Copiar archivo de local a contenedor.
* Importar licencia a contenedor.
* Agergar fuentes de Windows a un contenedor.
* Crear usuarios navcontainer.
* Desinstalar .app.
* Instalar .app.
* Actualizar .app.

HTTP
* Test apis personalizadas BC SANDBOX.
* Test apis personalizadas BC DOCKER.
* Test WS Docker BC Aut basica.

POWERSHELL
* Activar caracteristica Microsoft-Windows-Subsystem-Linux.
* Comparar ficheros de texto.
* Compilar objetos
* Importar licencia a una instalacion local.
* Instalar, desinstalar actualizar app local.
* Compilar objetos Local.
* Crear alias para GIT.
* Generar simbolos.
* Alias de GIT dentro de la configuracion.

GITBASH
* Cambiar origin a un proyecto que use git. 
* Activar o desactivar uso de ssl para git en terminal. 
* Añadir auth ssh para usar conexiones seguras con github. 
* Añadir alias arbolito para ver por terminal el historico de git. 
* Añadir alias personas para saber cuantos commits tiene cada colaborador. 
* Añadir a commit anterior. 
* Buscar palabra en git. 
* Abrir historico visual para git. 
* Reset rama. 

JSON
* Crear ruleset que excluya warning.
* Agrega analizadores de codigo.
* Agregar configuracion para que renombre nuestros archivos.

-----------------------------------------------------------------------------------------------------------

## Snippets

* AL
    * `talgo ordenamiento bubbleSort (EAD)` - Algoritmo de ordenamiento bubbleSort (existen mejores algoritmos).
    * `talgo ordenamiento InsertionSort (EAD)` - Algoritmo de ordenamiento InsertionSort (existen mejores algoritmos).
    * `talgo ordenamiento QuickSort (EAD)` - Algoritmo de ordenamiento QuickSort.
    * `talgo ordenamiento cocktailSort (EAD)` - Algoritmo de ordenamiento cocktailSort (existen mejores algoritmos).
    * `talgo recursividad/factorial (EAD)` - Procedimiento para hacer factoriales - recursividad.
    * `tinstall Upgrade tags/gestionar CU de upgrade (EAD)` - Upgrade tags/gestionar CU de upgrade.
    * `tinstall Upgrade tags/gestionar CU de upgrade Ampliada (EAD)` - Version ampliada de snippet upgradetags.
    * `treport formato fecha (EAD)` - Formato de fecha mediante la funcion Format.
    * `treport lanzar report con filtro de la pagina actual (EAD)` - Lanzar report desde pagina.
    * `treport cambiar idioma en report (EAD)` - Cambiar idioma en report.
    * `treport format mes report (EAD)` - Función format mes report.
    * `treport cambiar fecha a texto (EAD)` - Cambiar fecha a texto para reports.
    * `treport reemplazar informe (EAD)` - Suscripción a un evento para remplazar report.
    * `ttemplate enviar mail (EAD)` - Procedimiento para enviar email.
    * `ttemplate mapear db externa (EAD)` - Mapear tabla en DB externa.
    * `ttemplate pagina web dentro BC controlAddin (EAD)` - Usar controlAddin para embeber Web dentro de BC.
    * `ttemplate (EAD)` - Crear plantilla para Notificacion.
    * `ttest lanzar test desde VSCode testrunner (EAD)` - Lanzar pruebas unitarias desde VSCode.
    * `ttraduccion Caption (EAD)` - Crear propiedad caption con comentario.
    * `ttraduccion ToolTip (EAD)` - Crear propiedad ToolTip con comentario.
    * `ttraduccion Label (EAD)` - Crear propiedad Label con comentario.
    * `ttraduccion Comment (EAD)` - Crear Comment.
    * `tutil numero es divisible (EAD)` - Muestra si un numero es multiplo de otro.
    * `tutil accion cargar blob (EAD)` - Accion cargar blob.
    * `tutil overflow en campos texto (EAD)` - Manejar overflow en campos texto.
    * `tutil existe letra en (EAD)` - Función para verificar si existe letra.
    * `tutil trabajar con enum (EAD)` - Trabajar con Enum.
    * `tutil onassisedit mostrar un campo en pagina y guardar otro en tabla (EAD)` - Mostrar un campo en pagina y guardar otro en tabla.
    * `tutil tablerelation en funcion de otro campo de la tabla (EAD)` - TableRelation con condicional.
    * `tutil escribir desde texto (EAD)` - Crear procesos para escribir en un campo blob.
    * `tutil obtener texto desde blob (EAD)` - Crear procesos para leer un campo blob.
    * `tutil firma una línea (EAD)` - Agregar comentario para firmar codigo.
    * `tutil firma multilínea (EAD)` - Agregar comentario para firmar codigo en varias lienas.
    * `tutil recorrer record (EAD)` - Agregar complemento para Findset repeater.
    * `tutil campo en pagina con tooltip (EAD)` - Crear campo en pagina con tooltip.
    * `tutil cambiar color de campos en pagina (EAD)` - Crear plantilla para cambiar color de los campos en paginas.
    * `tutil Agregar Links en page (EAD)` - Agregar Links en page (EAD).
    * `tutil Agregar Notes en page (EAD)` - Agregar Notes en page (EAD).
    * `tutil Validar campo Email (EAD)` - Validar campo Email (EAD).
    * `tutil play video (EAD)` - función play video (EAD).
    * `tutil abrir url (EAD)` - función abrir url (EAD).
    * `twsapi API insert/modify (EAD)` - API Insert/Modify.
    * `twsapi bound action para paginas WS (EAD)` - Bound Action a pagina WS.
    * `twsapi trabajar json anidados (EAD)` - Trabajar con Json anidados.

* DOCKER
    * `tdocker instalar app (EAD)` - Instalar .app.
    * `tdocker actualizar app (EAD)` - Actualizar .app.
    * `tdocker desinstalar/despublicar app (EAD)` - Desinstalar .app.
    * `tdocker compilar objetos (EAD)` - Compilar objetos de contenedor.
    * `tdocker crear contenedor BC OnPremise (EAD)` - Crear contenedor.
    * `tdocker crear contenedor BC Sandbox (EAD)` - Crear contenedor.
    * `tdocker crear contenedor BC desde .bak (EAD)` - Crear contenedor desde respaldo .bak.
    * `tdocker crear contenedor BC con Sql Externo (EAD)` - Crear contenedor desde respaldo .bak.
    * `tdocker importar codeunit y extensiones de test (EAD)` - Importar C/U de test.
    * `tdocker ver detalles de imagenes de Docker (EAD)` - Extraer BaseApp desde un contenedor.
    * `tdocker extraer codigo de la BaseAPP desde contenedor (EAD)` - Ver detalles de imagen antes de descargar.
    * `tdocker importar licencia (EAD)` - Importar licencia a contenedor.
    * `tdocker agregar fuentes de Windows a un contenedor (EAD)` - Agergar fuentes de Windows a un contenedor.
    * `tdocker instalar BCcontainerhelper (EAD)` - instalar BCcontainerhelper a contenedor.
    * `tdocker ver ayuda de navcontainerhelper (EAD)` - Ver ayuda navcontainerhelper.
    * `tdocker copiar archivo desde contenedor a local (EAD)` - Copiar archivo de contenedor a local.
    * `tdocker copiar archivo local a contenedor (EAD)` - Copiar archivo de local a contenedor.
    * `tdocker crear usuario en contenedor (EAD)` - Crear usuarios navcontainer.

* POWERSHELL
    * `tonprem compilar objetos Local (EAD)` - Compilar objetos Local.
    * `tonprem instalar desinstalar actualizar app local (EAD)` - Instalar, desinstalar actualizar app local.
    * `tonprem comparar ficheros de texto desde PS (EAD)` - Comparar ficheros de texto desde PS (Verificar rutas).
    * `tonprem importar licencia local (EAD)` - Importar licencia a una instalacion local.
    * `tonprem crear usuario local (EAD)` - crear usuario en una instalacion local.
    * `tonprem generar simbolos local (EAD)` - generar simbolos en una instalacion local.
    * `tpowershell Activar caracteristica Microsoft-Windows-Subsystem-Linux (EAD)` - Activar caracteristica Microsoft-Windows-Subsystem-Linux para ejecutar la terminal de linux dentro de Windows.
    * `tpowershell traduccion con expresiones regulares (EAD)` - Traducciones usando expresiones regulares.
    * `tpowershell expresion regular para encontrar fallos traduciones (EAD)` - RegExp para encontrar fallos en fichero de traduccion.
    
* GITBASH
    * `tgit cambiar origin git (EAD)` - Cambiar origin a un proyecto que use git. 
    * `tgit activar o desactivar uso de ssl en git (EAD)` - Activar o desactivar uso de ssl para git en terminal. 
    * `tgit añadir auth ssh github (EAD)` - Añadir auth ssh para usar conexiones seguras con github. 
    * `tgit añadir alias arbolito (EAD)` - Añadir alias arbolito para ver por terminal el historico de git. 
    * `tgit añadir alias personas (EAD)` - Añadir alias personas para saber cuantos commits tiene cada colaborador. 
    * `tgit añadir a commit anterior (EAD)` - Añadir a commit anterior. 
    * `tgit buscar palabra en git (EAD)` - Buscar palabra en git. 
    * `tgit ver historico visual (EAD)` - Abrir historico visual para git. 
    * `tgit Crear alias para GIT (EAD)` - Crear alias para GIT.
    * `tgit reset rama (EAD)` - Reset rama. 
    * `tgit alias git cfg (EAD)` - Alias de GIT dentro de la configuracion.
    * `tgit gitignore (EAD)` - Ejemplo de Gitignore que despues copiaremos al archivo gitignore.

* HTTP
    * `tapi Test APIs SANDBOX BC Aut basica (EAD)` - Test apis personalizadas BC SANDBOX.
    * `tapi Test APIs DOCKER BC Aut basica (EAD)` - Test apis personalizadas BC DOCKER.
    * `tws test WS Docker BC Aut basica (EAD)` - Test WS Docker BC Aut basica.

* JSON
    * `tjson ruleset que excluya warning en nombre de archivo (EAD)` - Crear ruleset que excluya warning en nombre de archivo.
    * `tjson analizadores de codigo (EAD)` - Agrega analizadores de codigo.
    * `tjson nombres objetos (EAD)` - Agregar configuracion para que renombre nuestros archivos.

####Ejemplos :
**`tdocker crear contenedor BC (EAD)`**
```powershell
#container
$ContainerName = 'ContainerName'
$licenseFile = 'C:\License\License.flf'

# Image
$artifactUrl = Get-BCArtifactUrl -type onPrem -country "es" -version 17  
$imageName = 'onprem17'

# User
$UserName = 'User'
$Password = ConvertTo-SecureString "Pass123" -AsPlainText -Force
$Credential = New-Object System.Management.Automation.PSCredential ($UserName, $Password)
			
New-BCContainer -accept_eula `
                -accept_outdated `
                -updateHosts `
                -containername $containername `
                -licenseFile $licenseFile `
   		        -artifactUrl $artifactUrl `
                -imageName $imageName `
                -auth NavUserPassword `
                -Credential $credential
```

**`tcambiar color de campos en pagina (EAD)`**
```pascal
procedure fontColorChange(VAR styleColor: Text; Validations : Text)
// Para funcionar correctamente necesitamos:
// 1- Propiedad StyleExpr en los campos en los que queremos cambiar el estilo. Ejemplo: StyleExpr = fontStyle (Variable global de página).
// 2- Usa un disparador para llamar a nuestra función a la cual pasaremos como la variable global que asignamos a la propiedad StyleExpr.
// 3- Modifica el parámetro "Validación", el caso y los colores que queremos usar.
begin
    case Validations of
        'Soft Red':
            styleColor:= 'Attention';
        'Soft blue':
            styleColor := 'AttentionAccent';
        'Soft gray':
            styleColor := 'Subordinate';
        'Standard Black':
            styleColor := 'Standard';
        'Standard Blue':
            styleColor := 'StandardAccent';
        'Strong Black':
            styleColor := 'Strong';
        'Strong Blue':
            styleColor := 'StrongAccent';
        'Red strong':
            styleColor := 'Unfavorable';
        'Green':
            styleColor:= 'Favorable';
        'Yellow':
            styleColor := 'Ambiguous';
    end;
end;
```

## Comandos
Los comandos EAD que usaremos desde la paleta crearan una nueva carpeta en nuestro proyecto con los archivos plantilla.
* Generar settings.json.
* Generar .gitignore.
* Patrones de arquitectura.
    * Singleton.
    * Supplemental and subsidiary.
    * Compound.
    * Master.
* Patrones de diseño.
    * Comentarios.
    * Bloqueado.
    * Descripcion.
    * Nos Series.
    * Dimensiones.
    * Vendedor.
    * Direcciones.
    * Contacto.
* Patrones EAD !AT YOUR OWN RISK!.
    * UpgradeTags.
    * ControlAddin.

## Release Notes
### 1.0.4
* Se agregarón los siguientes snippetes:
    * AL - Plantilla agregar links en paginas.
    * AL - Plantilla agregar notas en paginas.
    * AL - Agregar campo Email con validación.
    * AL - Agregar función para reproducir video.
    * AL - Agregar función para abrir url.

* Se agregarón los siguientes comentarios:
    * Generar settings.json.
    * Generar .gitignore.
    * Patrones de arquitectura.
        * Singleton.
        * Supplemental and subsidiary.
        * Compound.
        * Master.
    * Patrones de diseño.
        * Comentarios.
        * Bloqueado.
        * Descripcion.
        * Nos Series.
        * Dimensiones.
        * Vendedor.
        * Direcciones.
        * Contacto.
    * Patrones EAD !AT YOUR OWN RISK!.
        * UpgradeTags.
        * ControlAddin.
### 1.0.3
* Se modificaron los siguientes snippets: crear contenedores con artifacts
    * Docker - Instalar BCContainerHelper.
    * Docker - Crear contenedor Onpremise.
    * Docker - Crear contenedor SandBox.
    * Docker - Crear contenedor desde respaldo .bak. 
    * Docker - Crear contenedor con sql externo. 
    * Docker - Desinstalar .app.
    * Docker - Instalar .app.
    * Docker - Actualizar .app.
    
### 1.0.2
* Se agregaron los siguientes snippets:
    * AL - Lanzar report con filtro.
    * AL - Funcion existe letra en.
    * AL - Ejemplo Gitignore.
    * AL - Upgrade tags ampliada.
    * AL - Traduccion mediante expresiones regulares.
    * AL - Ejemplo Formato de fecha con format.
    * AL - RegExp para encontrar fallo en archivo de traducciones.
    * AL - Ejemplo Bound Actions para WebServices de tipo pagina.
    * AL - Ejemplo de trabajar con Enum.
    * AL - Ejemplo onAssisEdit mostrar un campo en pagina y grabar en otro campo tabla.
    * AL - Mapeo con ExternalSql.
    * AL - Trabajar con Json Anidados.
    * AL - Tablerelation con condicional.
    * AL - Lanzar pruebas unitarias desdes VSCode.
    * AL - Web embebida dentro de BC con controlAddin.
    * HTTP - Test WebServices DOCKER Aut basica.
    * HTTP - Test APIs personalizadas DOCKER Aut basica.
    * POWERSHELL - Crear alias GIT.
    * POWERSHELL - Generar simbolos.
    * POWERSHELL - Compilar Objetos.
    * POWERSHELL - Copiar alias GIT a CFG.

* Se Modificaron los siguientes snippets:
    * AL - Notificacion.

### 1.0.1
* Se agregaron los siguientes snippets:
    * AL - Verificar numero divisible.
    * AL - Proceso para enviar email.
    * AL - Suscripcion para remplazar reports.
    * AL - API insert/modify.
    * AL - Accion cargar blob.
    * AL - Algoritmo de ordenamiento bubbleSort
    * AL - Algoritmo de InsertionSort bubbleSort
    * AL - Algoritmo de QuickSort bubbleSort
    * AL - Algoritmo de cocktailSort bubbleSort
    * AL - Factoriales - recursividad
    * AL - Manejar overflow en campos texto
    * AL - Cambiar idioma en report
    * AL - Función format mes report
    * AL - Cambiar fecha a texto para reports
    * AL - Gestion upgrade con upgrade tags
    * HTTP - Test APIs personalizadas Aut basica.
    * POWERSHELL - Activar caracteristica Microsoft-Windows-Subsystem-Linux para ejecutar la terminal de linux dentro de Windows
    * POWERSHELL - Comparar ficheros de texto desde PS (Verificar rutas)
    * POWERSHELL - Compilar objetos
    * POWERSHELL - Importar licencia local
    * POWERSHELL - Instalar, actualizar, desinstalar extensiones local
    * POWERSHELL - Crear usurio local
    * GITBASH - Cambiar origin git
    * GITBASH - Activar o desactivar uso de ssl en git
    * GITBASH - Añadir auth ssh github
    * GITBASH - Añadir alias arbolito git
    * GITBASH - Añadir alias personas git
    * GITBASH - Añadir a commit anterior git
    * GITBASH - Buscar palabra en git
    * GITBASH - Ver historico visual git
    * GITBASH - Reset rama git
    * JSON - Crear ruleset que excluya warning en nombre de archivo
    * JSON - Agregar codeanalysis
    * JSON - Agregar cambiar nombre de objetos

* Se Modificaron los siguientes snippets:
    * Docker - Crear usuarios navcontainer.

### 1.0.0

* Versión inicial: se agregaron los siguientes snippets
    * Docker - Crear contenedor.
    * Docker - Crear contenedor desde respaldo .bak. 
    * Docker - Importar C/U de test.
    * Docker - Extraer BaseApp desde un contenedor.
    * Docker - Ver detalles de imagen antes de descargar.
    * Docker - Ver ayuda navcontainerhelper.
    * Docker - Copiar archivo de contenedor a local.
    * Docker - Copiar archivo de local a contenedor.
    * Docker - Importar licencia a contenedor.
    * Docker - Agergar fuentes de Windows a un contenedor.
    * Docker - Crear usuarios navcontainer.
    * Docker - Desinstalar .app.
    * Docker - Instalar .app.
    * Docker - Actualizar .app.
    * AL - Escribir blob.
    * AL - Leer blob.
    * AL - Firma.
    * AL - Firma multilinea.
    * AL - Findset repeater.
    * AL - Campo pagina con tooltip.
    * AL - Notificacion.
    * AL - Cambiar color de los campos en paginas.

**Enjoy!**

Good vibes <br>