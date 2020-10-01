# Título del Proyecto

Personaliza windows Terminal para Powershell y WSL

<img src=/Capturas/WT.png alt="Windows_Terminal"/>

<img src=/Capturas/2.png alt="CMD"/>

<img src=/Capturas/4.png alt="Ubuntu"/>

<img src=/Capturas/5.png alt="Kali"/>

<img src=/Capturas/6.png alt="Debian"/>


## Comenzando 🚀

_Te comparto mi configuración de Windows Terminal para personalizar mi entorno de trabajo y sentirte más cómodo, en la carpeta recursos encontrarás los logos y fuentes para utilizar en tu terminal; CascadiaCode para powershell y DroidSansMono para WSL, no olvides instalar estas fuentes en la carpeta fonts de windows 😅, en la carpeta windows terminal está mi configuración completa de la terminal y en la carpeta colorscheme está la configuración de temas y una muestra en imagen por cada shell. Disfrutalo_


### Pre-requisitos 📋

_Lo que necesitas para personalizar tu terminal

```
1.-La nueva terminal de windows preferentemente descarga desde Microsoft Store .

2.-Tener instalado git para windows y git para Windows Subsystem for Linux.

3.-Descargar este repositorio por medio de git o como un zip.

4.-Un editor de texto plano bloc de notas, vim, nano, etc.

5.-De preferencia instalar la versión mas reciente de powershell.

6.-Las distrubuciones de Linux que gustes

7.-Paciencia

```

### Oh-my-posh en PowerShell 🔧

_Una serie de ejemplos paso a paso que te dice lo que debes ejecutar para personalizar powershell en tu terminal_

_Una ve descargados la terminal de windows y el repositorio copia las fuentes de las carpetas comprimidas(Obio descomprime primero) en Fonts de windows recuerdad Cascadia Code PL para powershell y DroidSansMono para WSL:_

<img src=/Capturas/Fonts.png alt="Fonts"/>

```
Da un ejemplo
```

_Despues instala Oh-my-posh, con los siguientes comandos; recuerda declinar por confiar en la fuente_

```
Install-Module posh-git -Scope CurrentUser
```
```
Install-Module oh-my-posh -Scope CurrentUser
```

_Importa los modulos a tu perfil de powershell, SUSTITUYE adria por tu usuario_

<img src=/Capturas/PROFILE$.png alt="ProfilePS"/>

```
Import-Module posh-git
Import-Module oh-my-posh
Set-Theme Paradox
```

_Corre una shell de powershell como administrador, para quitar las restricciones a los modulos_

<img src=/Capturas/Set.png alt="Set"/>

_En la carpeta Windows-Terminal te dejo dos secciones de archivos json, uno para la configuración completa de windows terminal y otro por temas de colores, por cada esquema de color anexo una toma para que veas como tiene que quedar, en gustos se rompen generos, es mi personalización no tiene porque gustarte, te invito a que copies los perfiles que necesites y posteriormente jugar con el esquema de colores_

<img src=/Capturas/ConfPS.png alt="ConfigPS"/>

<img src=/Capturas/esquemasPS.png alt="SchemesPS"/>

_Si todo salio bien, el resultado es:_ 

<img src=/Capturas/1.png alt="PS"/>



_Finaliza con un ejemplo de cómo obtener datos del sistema o como usarlos para una pequeña demo_

## Ejecutando las pruebas ⚙️

_Explica como ejecutar las pruebas automatizadas para este sistema_

### Analice las pruebas end-to-end 🔩

_Explica que verifican estas pruebas y por qué_

```
Da un ejemplo
```

### Y las pruebas de estilo de codificación ⌨️

_Explica que verifican estas pruebas y por qué_

```
Da un ejemplo
```

## Despliegue 📦

_Agrega notas adicionales sobre como hacer deploy_

## Construido con 🛠️

_Menciona las herramientas que utilizaste para crear tu proyecto_

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - El framework web usado
* [Maven](https://maven.apache.org/) - Manejador de dependencias
* [ROME](https://rometools.github.io/rome/) - Usado para generar RSS

## Contribuyendo 🖇️

Por favor lee el [CONTRIBUTING.md](https://gist.github.com/villanuevand/xxxxxx) para detalles de nuestro código de conducta, y el proceso para enviarnos pull requests.

## Wiki 📖

Puedes encontrar mucho más de cómo utilizar este proyecto en nuestra [Wiki](https://github.com/tu/proyecto/wiki)

## Versionado 📌

Usamos [SemVer](http://semver.org/) para el versionado. Para todas las versiones disponibles, mira los [tags en este repositorio](https://github.com/tu/proyecto/tags).

## Autores ✒️

_Menciona a todos aquellos que ayudaron a levantar el proyecto desde sus inicios_

* **Andrés Villanueva** - *Trabajo Inicial* - [villanuevand](https://github.com/villanuevand)
* **Fulanito Detal** - *Documentación* - [fulanitodetal](#fulanito-de-tal)

También puedes mirar la lista de todos los [contribuyentes](https://github.com/your/project/contributors) quíenes han participado en este proyecto. 

## Licencia 📄

Este proyecto está bajo la Licencia (Tu Licencia) - mira el archivo [LICENSE.md](LICENSE.md) para detalles

## Expresiones de Gratitud 🎁

* Comenta a otros sobre este proyecto 📢
* Invita una cerveza 🍺 o un café ☕ a alguien del equipo. 
* Da las gracias públicamente 🤓.
* etc.



---
⌨️ con ❤️ por [Villanuevand](https://github.com/Villanuevand) 😊
