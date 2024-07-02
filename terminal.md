> Terminal | Sebastián Vidal Aedo | 2024MMDD

- [Introducción a la Terminal](#introducción-a-la-terminal)
- [Ventajas y Desventajas de la Terminal](#ventajas-y-desventajas-de-la-terminal)
  - [Ventajas](#ventajas)
  - [Desventajas](#desventajas)
  - [Consideraciones para elegir una terminal, o mejor dicho la aplicación que la encapsula](#consideraciones-para-elegir-una-terminal-o-mejor-dicho-la-aplicación-que-la-encapsula)
- [Los 100 comandos más útiles para desarrolladores](#los-100-comandos-más-útiles-para-desarrolladores)
  - [Manejo de archivos:](#manejo-de-archivos)
    - [1. **ls**: Lista los archivos y directorios en el directorio actual.](#1-ls-lista-los-archivos-y-directorios-en-el-directorio-actual)
    - [2. **cd**: Cambia el directorio actual por el especificado después del comando.](#2-cd-cambia-el-directorio-actual-por-el-especificado-después-del-comando)
    - [3. **mkdir**: Crea un nuevo directorio.](#3-mkdir-crea-un-nuevo-directorio)
    - [4. **rm**: Elimina archivos o directorios.](#4-rm-elimina-archivos-o-directorios)
    - [5. **cp**: Copia archivos o directorios. Primero se indica lo que se copiara y luego donde se copiara.](#5-cp-copia-archivos-o-directorios-primero-se-indica-lo-que-se-copiara-y-luego-donde-se-copiara)
    - [6. **mv**: Mueve o renombra archivos o directorios.](#6-mv-mueve-o-renombra-archivos-o-directorios)
    - [7. **cat** : Muestra el contenido de un archivo.](#7-cat--muestra-el-contenido-de-un-archivo)
    - [8. **nano**: Abre el editor de texto simple Nano en la terminal.](#8-nano-abre-el-editor-de-texto-simple-nano-en-la-terminal)
    - [9. **vi**: Abre el editor de texto Vi en la terminal.](#9-vi-abre-el-editor-de-texto-vi-en-la-terminal)
    - [10. **echo**: Muestra un mensaje en la pantalla o redirige texto a un archivo.](#10-echo-muestra-un-mensaje-en-la-pantalla-o-redirige-texto-a-un-archivo)
    - [11. **pwd**: Muestra el directorio actual de trabajo.](#11-pwd-muestra-el-directorio-actual-de-trabajo)
    - [12. **tar**: Crea o extrae archivos de un archivo tar.](#12-tar-crea-o-extrae-archivos-de-un-archivo-tar)
    - [13. **unzip**: Extrae archivos de un archivo comprimido zip.](#13-unzip-extrae-archivos-de-un-archivo-comprimido-zip)
    - [14. **find**: Busca archivos en un directorio.](#14-find-busca-archivos-en-un-directorio)
    - [15. **diff**: Muestra las diferencias entre dos archivos.](#15-diff-muestra-las-diferencias-entre-dos-archivos)
    - [16. **sed**: Filtra y transforma texto.](#16-sed-filtra-y-transforma-texto)
    - [17. **awk**: Procesa y filtra texto.](#17-awk-procesa-y-filtra-texto)
    - [18. **gzip**: Comprime archivos en formato gzip.](#18-gzip-comprime-archivos-en-formato-gzip)
    - [19. **gunzip**: Descomprime archivos comprimidos en formato gzip.](#19-gunzip-descomprime-archivos-comprimidos-en-formato-gzip)
    - [20. **bzip2**: Comprime archivos en formato bzip2.](#20-bzip2-comprime-archivos-en-formato-bzip2)
    - [21. **bunzip2**: Descomprime archivos comprimidos en formato bzip2.](#21-bunzip2-descomprime-archivos-comprimidos-en-formato-bzip2)
    - [22. **tee**: Lee desde la entrada estándar y escribe en la salida estándar y en uno o más archivos.](#22-tee-lee-desde-la-entrada-estándar-y-escribe-en-la-salida-estándar-y-en-uno-o-más-archivos)
    - [23. **ln**: Crea enlaces simbólicos o enlaces duros a archivos o directorios.](#23-ln-crea-enlaces-simbólicos-o-enlaces-duros-a-archivos-o-directorios)
    - [24. **touch**: Actualiza la marca de tiempo de acceso y modificación de un archivo o crea un archivo vacío.](#24-touch-actualiza-la-marca-de-tiempo-de-acceso-y-modificación-de-un-archivo-o-crea-un-archivo-vacío)
    - [25. **cut**: Extrae secciones de cada línea de un archivo.](#25-cut-extrae-secciones-de-cada-línea-de-un-archivo)
    - [26. **paste**: Combina líneas de archivos de texto lado a lado.](#26-paste-combina-líneas-de-archivos-de-texto-lado-a-lado)
  - [Git y GitHub:](#git-y-github)
    - [27. "git clone": Clona un repositorio en un nuevo directorio.](#27-git-clone-clona-un-repositorio-en-un-nuevo-directorio)
    - [28. "git init": Inicializa un nuevo repositorio Git.](#28-git-init-inicializa-un-nuevo-repositorio-git)
    - [29. "git add": Añade archivos al área de preparación.](#29-git-add-añade-archivos-al-área-de-preparación)
    - [30. "git commit": Registra cambios en el repositorio.](#30-git-commit-registra-cambios-en-el-repositorio)
    - [31. "git push": Sube cambios al repositorio remoto.](#31-git-push-sube-cambios-al-repositorio-remoto)
    - [32. "git pull": Baja y fusiona cambios desde el repositorio remoto.](#32-git-pull-baja-y-fusiona-cambios-desde-el-repositorio-remoto)
    - [33. "git status": Muestra el estado del repositorio.](#33-git-status-muestra-el-estado-del-repositorio)
    - [34. "git branch": Gestiona las ramas.](#34-git-branch-gestiona-las-ramas)
    - [35. "git checkout": Cambia entre ramas.](#35-git-checkout-cambia-entre-ramas)
    - [36. "git merge": Fusiona ramas.](#36-git-merge-fusiona-ramas)
    - [37. "git log": Muestra el historial de commits.](#37-git-log-muestra-el-historial-de-commits)
    - [38. "git tag": Gestiona las etiquetas.](#38-git-tag-gestiona-las-etiquetas)
    - [39. "git reset": Restablece el estado del repositorio.](#39-git-reset-restablece-el-estado-del-repositorio)
    - [40. "git remote": Gestiona los repositorios remotos.](#40-git-remote-gestiona-los-repositorios-remotos)
    - [41. "git config": Configura opciones de Git.](#41-git-config-configura-opciones-de-git)
    - [42. "git diff": Muestra las diferencias entre commits.](#42-git-diff-muestra-las-diferencias-entre-commits)
    - [43. "git stash": Guarda temporalmente los cambios en un stash.](#43-git-stash-guarda-temporalmente-los-cambios-en-un-stash)
    - [44. "git blame": Muestra quién modificó cada línea de un archivo.](#44-git-blame-muestra-quién-modificó-cada-línea-de-un-archivo)
    - [45. "git show": Muestra información detallada sobre un commit.](#45-git-show-muestra-información-detallada-sobre-un-commit)
    - [46. "git revert": Deshace un commit específico.](#46-git-revert-deshace-un-commit-específico)
  - [Redes y conectividad:](#redes-y-conectividad)
    - [47. **ssh**: Accede a máquinas remotas de forma segura.](#47-ssh-accede-a-máquinas-remotas-de-forma-segura)
    - [48. **scp**: Copia archivos entre hosts de forma segura.](#48-scp-copia-archivos-entre-hosts-de-forma-segura)
    - [49. **rsync**: Sincroniza archivos y directorios de manera eficiente.](#49-rsync-sincroniza-archivos-y-directorios-de-manera-eficiente)
    - [50. **traceroute**: Rastrea la ruta que toma un paquete para llegar a un host.](#50-traceroute-rastrea-la-ruta-que-toma-un-paquete-para-llegar-a-un-host)
    - [51. **ping**: Envía paquetes ICMP a un host para verificar la conectividad de red.](#51-ping-envía-paquetes-icmp-a-un-host-para-verificar-la-conectividad-de-red)
    - [52. **ifconfig**: Configura interfaces de red.](#52-ifconfig-configura-interfaces-de-red)
    - [53. **netstat**: Muestra conexiones de red, tablas de enrutamiento y estadísticas de interfaz.](#53-netstat-muestra-conexiones-de-red-tablas-de-enrutamiento-y-estadísticas-de-interfaz)
    - [54. **ssh-keygen**: Genera pares de claves de autenticación SSH.](#54-ssh-keygen-genera-pares-de-claves-de-autenticación-ssh)
    - [55. **curl**: Transfiere datos desde o hacia un servidor.](#55-curl-transfiere-datos-desde-o-hacia-un-servidor)
    - [56. **nc** (Netcat): Lee y escribe datos en conexiones de red.](#56-nc-netcat-lee-y-escribe-datos-en-conexiones-de-red)
    - [57. **dig**: Realiza consultas DNS.](#57-dig-realiza-consultas-dns)
    - [58. **whois**: Consulta información de registros de dominio.](#58-whois-consulta-información-de-registros-de-dominio)
    - [59. **hostname**: Muestra o establece el nombre del host.](#59-hostname-muestra-o-establece-el-nombre-del-host)
    - [60. **systemctl**: Controla el sistema y los servicios de administración.](#60-systemctl-controla-el-sistema-y-los-servicios-de-administración)
    - [61. **journalctl**: Muestra los registros del sistema.](#61-journalctl-muestra-los-registros-del-sistema)
    - [62. **crontab**: Edita la tabla de trabajos programados para el usuario.](#62-crontab-edita-la-tabla-de-trabajos-programados-para-el-usuario)
  - [Administración de usuarios y grupos:](#administración-de-usuarios-y-grupos)
    - [63. **whoami**: Muestra el nombre del usuario actual.](#63-whoami-muestra-el-nombre-del-usuario-actual)
    - [64. **sudo**: Ejecuta un comando con privilegios de superusuario.](#64-sudo-ejecuta-un-comando-con-privilegios-de-superusuario)
    - [65. **su**: Cambia de usuario o a superusuario.](#65-su-cambia-de-usuario-o-a-superusuario)
    - [66. **passwd**: Cambia la contraseña de un usuario.](#66-passwd-cambia-la-contraseña-de-un-usuario)
    - [68. **useradd**: Crea un nuevo usuario.](#68-useradd-crea-un-nuevo-usuario)
    - [69. **userdel**: Elimina un usuario.](#69-userdel-elimina-un-usuario)
    - [70. **groupadd**: Crea un nuevo grupo.](#70-groupadd-crea-un-nuevo-grupo)
    - [71. **groupdel**: Elimina un grupo.](#71-groupdel-elimina-un-grupo)
    - [72. **usermod**: Modifica una cuenta de usuario.](#72-usermod-modifica-una-cuenta-de-usuario)
    - [73. **groupmod**: Modifica un grupo.](#73-groupmod-modifica-un-grupo)
  - [Administración de procesos:](#administración-de-procesos)
    - [74. **ps**: Muestra información sobre los procesos en ejecución.](#74-ps-muestra-información-sobre-los-procesos-en-ejecución)
    - [75. **kill**: Envía una señal a un proceso, generalmente para terminarlo.](#75-kill-envía-una-señal-a-un-proceso-generalmente-para-terminarlo)
    - [76. **top**: Muestra en tiempo real los procesos en ejecución y el uso del sistema.](#76-top-muestra-en-tiempo-real-los-procesos-en-ejecución-y-el-uso-del-sistema)
    - [77. **df**: Muestra el uso del espacio en disco de los sistemas de archivos.](#77-df-muestra-el-uso-del-espacio-en-disco-de-los-sistemas-de-archivos)
    - [78. **du**: Muestra el uso del espacio en disco por archivos y directorios.](#78-du-muestra-el-uso-del-espacio-en-disco-por-archivos-y-directorios)
    - [79. **head**: Muestra las primeras líneas de un archivo.](#79-head-muestra-las-primeras-líneas-de-un-archivo)
    - [80. **tail**: Muestra las últimas líneas de un archivo.](#80-tail-muestra-las-últimas-líneas-de-un-archivo)
    - [81. **sort**: Ordena líneas de texto.](#81-sort-ordena-líneas-de-texto)
    - [82. **wc**: Cuenta líneas, palabras y caracteres.](#82-wc-cuenta-líneas-palabras-y-caracteres)
    - [83. **date**: Muestra o establece la fecha y hora del sistema.](#83-date-muestra-o-establece-la-fecha-y-hora-del-sistema)
    - [84. **history**: Muestra el historial de comandos.](#84-history-muestra-el-historial-de-comandos)
    - [85. **lsof**: Lista archivos abiertos y los procesos que los abrieron.](#85-lsof-lista-archivos-abiertos-y-los-procesos-que-los-abrieron)
    - [86. **mount**: Monta un sistema de archivos.](#86-mount-monta-un-sistema-de-archivos)
    - [87. **umount**: Desmonta un sistema de archivos.](#87-umount-desmonta-un-sistema-de-archivos)
    - [88. **screen**: Permite gestionar sesiones de terminal múltiples.](#88-screen-permite-gestionar-sesiones-de-terminal-múltiples)
    - [89. **tmux**: Multiplexador de terminal que permite dividir una terminal en múltiples sesiones.](#89-tmux-multiplexador-de-terminal-que-permite-dividir-una-terminal-en-múltiples-sesiones)
    - [90. **watch**: Ejecuta un comando de forma repetida y muestra la salida en tiempo real.](#90-watch-ejecuta-un-comando-de-forma-repetida-y-muestra-la-salida-en-tiempo-real)

# Introducción a la Terminal

La terminal, también conocida como línea de comandos o shell, es una poderosa herramienta que permite interactuar con un sistema operativo a través de texto. A diferencia de las interfaces gráficas, donde se utilizan ventanas y menús, la terminal se basa en comandos escritos en texto plano para ejecutar acciones en el sistema.

Una de las características más destacadas de la terminal es su capacidad para realizar tareas complejas con solo unas pocas líneas de comando. Desde la gestión de archivos hasta la configuración de redes, pasando por el desarrollo de software y la administración de servidores, la terminal ofrece una amplia gama de funcionalidades que pueden adaptarse a las necesidades de cualquier usuario.

Las terminales más usadas son:

- **Bash**: Es la terminal por defecto en la mayoría de los sistemas basados en Unix (terminal real, no solo una app que nos permite interactuar con el SO), como Linux y macOS. Es muy versátil y potente, con una amplia gama de comandos y opciones.

- **Zsh**: Es una terminal avanzada que ofrece características adicionales sobre Bash, como autocompletado avanzado, temas personalizables y plugins. Es muy popular entre los desarrolladores y usuarios avanzados.

- **Fish**: Es una terminal moderna y fácil de usar, con un enfoque en la usabilidad y la estética. Ofrece un autocompletado inteligente y una interfaz gráfica interactiva que facilita la escritura de comandos.

Y también tenemos aplicaciones que encapsulan la terminal y la hacen más amigable para el usuario, como:

- **iTerm2**: Es una terminal avanzada para macOS que ofrece características adicionales sobre la terminal por defecto, como pestañas, división de paneles y temas personalizables.

- **Terminator**: Es una terminal avanzada para Linux que permite dividir la pantalla en múltiples paneles y pestañas, lo que facilita la ejecución de varios comandos simultáneamente.

- **Warp**: Es una terminal moderna y minimalista para macOS que ofrece una interfaz gráfica limpia y sencilla, con soporte para temas personalizables y autocompletado avanzado.

Como desarrolladores, la terminal es una herramienta imprescindible en nuestro día a día. Es fundamental conocer los comandos básicos y comprender que existen diversas aplicaciones que nos permiten trascender la monotonía de la línea de comandos estándar, ofreciéndonos entornos más profesionales y funcionalidades que elevan nuestra interacción con el sistema operativo a un nivel superior. Estas herramientas no solo simplifican nuestras tareas, sino que también añaden un grado de sofisticación que puede hacer que nuestro trabajo sea más eficiente y agradable de lo que inicialmente podríamos pensar.

# Ventajas y Desventajas de la Terminal

## Ventajas

1. Eficiencia: La terminal permite realizar tareas de forma rápida y eficiente mediante comandos de texto, lo que puede ser más rápido que navegar a través de menús y ventanas en una interfaz gráfica.
2. Automatización: Es más fácil automatizar tareas repetitivas mediante scripts y alias en la terminal, lo que puede ahorrar tiempo y reducir errores.
3. Control Total: La terminal proporciona un control total sobre el sistema operativo, lo que permite realizar una amplia gama de acciones y personalizar la configuración según las necesidades del usuario.
4. Acceso Remoto: Es posible acceder a sistemas remotos a través de la terminal utilizando protocolos como SSH, lo que facilita la administración de servidores y la colaboración en equipos distribuidos.
5. Recursos del Sistema: La terminal consume menos recursos del sistema en comparación con algunas interfaces gráficas, lo que puede ser beneficioso en sistemas con recursos limitados.

## Desventajas

1. Curva de Aprendizaje: Para los usuarios que no están familiarizados con la línea de comandos, puede haber una curva de aprendizaje pronunciada al comenzar a utilizar la terminal.
2. Errores Potenciales: Debido a la naturaleza de los comandos de texto, es posible cometer errores al ingresar comandos en la terminal, lo que podría provocar resultados no deseados o dañar el sistema si no se tiene cuidado.
3. Limitaciones Visuales: Algunos usuarios pueden encontrar limitante la falta de elementos visuales en la terminal en comparación con las interfaces gráficas, especialmente para tareas que requieren una representación visual de los datos.
4. Dificultad en Tareas Complejas: Para algunas tareas complejas, puede ser más fácil y claro utilizar una interfaz gráfica que intentar realizarlas a través de comandos en la terminal.
5. Compatibilidad: Aunque la mayoría de los sistemas operativos admiten la terminal, puede haber diferencias en los comandos y la sintaxis entre diferentes sistemas y distribuciones, lo que podría causar problemas de compatibilidad.

## Consideraciones para elegir una terminal, o mejor dicho la aplicación que la encapsula

Estamos hablando de la aplicación que nos permite usar la terminal para interactuar con el SO (solo para aclararlo bien.)

1. Funcionalidades
   Las funcionalidades de una terminal incluyen características como autocompletado avanzado, plugins adicionales, temas personalizables y capacidades de scripting.

2. Compatibilidad:
   La compatibilidad se refiere a la capacidad de una terminal para ejecutarse en diferentes sistemas operativos y funcionar correctamente con una variedad de programas y herramientas. Si solo usas equipos de un tipo, este apartado no es tan importante, ya que la la mayoría (si no todos) los comandos aplican para cualquier entorno (con mínimas diferencias).

3. **Facilidad de Uso**:
   La facilidad de uso se refiere a lo intuitiva y accesible que es una terminal para los usuarios, especialmente aquellos que no tienen experiencia previa con la línea de comandos. Aquí es donde las "funcionalidades avanzadas" son la clave, la customización y la capacidad de abreviar comandos (como en Zsh o Fish) son muy importantes y un punto crucial a la hora de decidirse por la terminal.

Cabe destacar que, al igual que con la elección del lenguaje de programación, el editor de código o incluso el equipo de trabajo, la mejor terminal será aquella con la que te sientas más cómodo y obtengas mejores resultados. Cada usuario tiene sus propias preferencias y necesidades, y lo más importante es encontrar una terminal que se adapte a tu estilo de trabajo y te permita alcanzar tus objetivos de manera eficiente y efectiva. Experimenta con diferentes opciones, explora sus características y elige aquella que te brinde la mejor experiencia en tu día a día como desarrollador, yo uso [Warp](https://www.warp.dev/)... ¿Por qué? Me gusta como se ve, tiene auto-completado, el history es muy dinámico para auto-completar y tiene Warp IA para ayudarte con dudas.

# Los 100 comandos más útiles para desarrolladores

Los comandos disponibles son muchos, si en alguna ocasión debes usar uno y no sabes como, la misma terminal te puede ayudar, solo escribe `man comando` y te mostrará la documentación del comando que necesitas.

### Manejo de archivos:

#### 1. **ls**: Lista los archivos y directorios en el directorio actual.

```bash
ls
```

salida:

```bash
archivo1.txt archivo2.txt directorio1 directorio2
```

Variaciones:

- `ls -l`: Muestra los archivos y directorios en formato detallado.
- `ls -a`: Muestra todos los archivos y directorios, incluidos los ocultos.
- `ls -lh`: Muestra los archivos y directorios en formato detallado con tamaños legibles por humanos.
- `ls -R`: Muestra los archivos y directorios recursivamente.
- `ls -t`: Muestra los archivos y directorios ordenados por fecha y hora de modificación.
- `ls -S`: Muestra los archivos y directorios ordenados por tamaño.
- `ls -h`: Muestra los archivos y directorios con tamaños legibles por humanos.
- `ls -d`: Muestra solo los nombres de los directorios.

#### 2. **cd**: Cambia el directorio actual por el especificado después del comando.

```bash
cd documentos
```

Variaciones:

- `cd ..`: Cambia al directorio padre.
- `cd ~`: Cambia al directorio de inicio del usuario.
- `cd -`: Cambia al directorio anterior.
- `cd /`: Cambia al directorio raíz.
- `cd /ruta/directorio`: Cambia al directorio especificado por la ruta.

#### 3. **mkdir**: Crea un nuevo directorio.

```bash
mkdir nombre_directorio
```

#### 4. **rm**: Elimina archivos o directorios.

```bash
rm archivo.txt
rm -r directorio
```

Variaciones:

- `rm -f`: Elimina archivos sin preguntar.
- `rm -r`: Elimina directorios y su contenido recursivamente.
- `rm -rf`: Elimina directorios y su contenido sin preguntar.

#### 5. **cp**: Copia archivos o directorios. Primero se indica lo que se copiara y luego donde se copiara.

```bash
cp archivo.txt copia.txt
cp -r directorio1 directorio2
```

#### 6. **mv**: Mueve o renombra archivos o directorios.

```bash
mv archivo.txt nuevo_nombre.txt
```

Variaciones:

- `mv archivo.txt directorio`: Mueve el archivo a un directorio específico.
- `mv archivo.txt directorio/nuevo_nombre.txt`: Mueve y renombra el archivo.
- `mv directorio1 directorio2`: Mueve un directorio a otro.

#### 7. **cat** : Muestra el contenido de un archivo.

```bash
cat archivo.txt
```

salida:

```bash
Este es el contenido del archivo.
```

Nos es muy útil para ver el contenido de un archivo, pero si el archivo es muy grande, no es la mejor opción. Existe un derivado llama `bat` que es más amigable y nos permite ver el contenido de un archivo de manera más amigable.

#### 8. **nano**: Abre el editor de texto simple Nano en la terminal.

```bash
nano archivo.txt
```

Es el editor de texto por defecto en la mayoría de los sistemas basados en Unix, es muy fácil de usar y es ideal para principiantes.

#### 9. **vi**: Abre el editor de texto Vi en la terminal.

```bash
vi archivo.txt
```

Muy similar a Nano, pero con más funcionalidades y opciones avanzadas. Es poderoso pero tiene una curva de aprendizaje empinada para principiantes. En distribuciones como ubuntu igual encontramos `vim` que es una versión mejorada de `vi` (y que muchos usan como entorno de desarrollo).

#### 10. **echo**: Muestra un mensaje en la pantalla o redirige texto a un archivo.

```bash
echo "Hola, mundo!" > archivo.txt
echo $PATH
```

Es util para ver el valor de una variable de sistema o para redirigir texto a un archivo.

#### 11. **pwd**: Muestra el directorio actual de trabajo.

```bash
pwd
```

salida:

```bash
/home/usuario
```

#### 12. **tar**: Crea o extrae archivos de un archivo tar.

```bash
tar -czvf archivo.tar.gz directorio
```

Parámetros:

- `c`: Crea un nuevo archivo tar.
- `x`: Extrae archivos de un archivo tar.
- `z`: Comprime el archivo tar con gzip.
- `v`: Muestra el progreso del comando.
- `f`: Especifica el nombre del archivo tar.

#### 13. **unzip**: Extrae archivos de un archivo comprimido zip.

```bash
unzip archivo.zip -d directorio
```

Parámetros:

- `-d`: Especifica el directorio de destino para la extracción.
- `-l`: Muestra el contenido del archivo zip sin extraerlo.
- `-o`: Sobrescribe los archivos existentes sin preguntar.

#### 14. **find**: Busca archivos en un directorio.

```bash
find . -name "*.txt"
```

Parámetros:

- `.`: Especifica el directorio de inicio de la búsqueda.
- `-name`: Especifica el patrón de búsqueda.
- `-type f`: Busca solo archivos.
- `-type d`: Busca solo directorios.

#### 15. **diff**: Muestra las diferencias entre dos archivos.

```bash
diff archivo1.txt archivo2.txt
```

Ideal cuando debemos comparar dos archivos y ver las diferencias entre ellos.

#### 16. **sed**: Filtra y transforma texto.

```bash
sed 's/palabra/reemplazo/g' archivo.txt
sed 's/palabra/reemplazo/gi' archivo.txt
```

Parámetros:

- `s`: Indica que se realizará una sustitución.
- `palabra`: La palabra a buscar.
- `reemplazo`: La palabra con la que se reemplazará.
- `g`: Realiza la sustitución de forma global.
- `i`: Realiza la sustitución sin distinción entre mayúsculas y minúsculas.
- `archivo.txt`: El archivo en el que se realizará la sustitución.

#### 17. **awk**: Procesa y filtra texto.

```bash
awk '{print $1}' archivo.txt
```

Ejemplo, supongamos que tenemos un archivo csv con el siguiente contenido:

```bash
nombre,apellido,edad
Juan,Perez,30
Maria,Lopez,25
```

Si queremos obtener solo los nombres (la primera columna), podemos hacer:

```bash
awk -F"," '{print $1}' archivo.csv
```

```bash
 nombre
 Juan
 Maria
```

Parámetros:

- `-F","`: Especifica el delimitador de campos.
- `'{print $1}'`: Imprime el primer campo de cada línea.
- `archivo.txt`: El archivo en el que se realizará el procesamiento.
- `'{print $0}'`: Imprime toda la línea.
- `'{print $NF}'`: Imprime el último campo de cada línea.
<!-- TODO: voy aqui -->

#### 18. **gzip**: Comprime archivos en formato gzip.

```bash
gzip archivo.txt
```

**Particularidad**: Es rápido y eficiente en términos de compresión.

#### 19. **gunzip**: Descomprime archivos comprimidos en formato gzip.

```bash
gunzip archivo.txt.gz
```

**Particularidad**: Puede descomprimir archivos múltiples en un solo paso.

#### 20. **bzip2**: Comprime archivos en formato bzip2.

```bash
bzip2 archivo.txt
```

**Particularidad**: Ofrece una mayor relación de compresión que gzip.

#### 21. **bunzip2**: Descomprime archivos comprimidos en formato bzip2.

```bash
bunzip2 archivo.txt.bz2
```

**Particularidad**: Es compatible con la descompresión de archivos en formato bunzip2 y bzip2.

#### 22. **tee**: Lee desde la entrada estándar y escribe en la salida estándar y en uno o más archivos.

```bash
cat archivo.txt | tee copia.txt
```

**Particularidad**: Útil para redirigir la salida de un comando a la vez que se muestra en la pantalla.

#### 23. **ln**: Crea enlaces simbólicos o enlaces duros a archivos o directorios.

```bash
ln -s archivo.txt enlace.txt
```

**Particularidad**: Los

enlaces simbólicos pueden apuntar a cualquier ubicación del sistema de archivos.

#### 24. **touch**: Actualiza la marca de tiempo de acceso y modificación de un archivo o crea un archivo vacío.

```bash
touch nuevo_archivo.txt
```

**Particularidad**: Útil para crear archivos de marcador de posición o para actualizar marcas de tiempo.

#### 25. **cut**: Extrae secciones de cada línea de un archivo.

```bash
cut -d"," -f1 archivo.csv
```

**Particularidad**: Permite especificar delimitadores y campos a extraer.

#### 26. **paste**: Combina líneas de archivos de texto lado a lado.

```bash
paste archivo1.txt archivo2.txt
```

**Particularidad**: Útil para fusionar datos de múltiples archivos en columnas.

### Git y GitHub:

#### 27. "git clone": Clona un repositorio en un nuevo directorio.

"clonar" hace referencia a la descarga de un repositorio desde Github o cualquier otro servicio de control de versiones a el entorno donde se está trabajando.

```bash
git clone https://github.com/usuario/repositorio.git
```

**Variaciones**: Clona una rama especifica.

```bash
git clone --branch nombre_rama
```

#### 28. "git init": Inicializa un nuevo repositorio Git.

```bash
git init
```

**Particularidad**: Crea un nuevo repositorio Git en el directorio actual, en otras palabras, convierte el directorio actual en un repositorio Git versionable.

#### 29. "git add": Añade archivos al área de preparación.

```bash
git add archivo.txt
```

Con este comando se añade un archivo al área de preparación, lo que significa que se incluirá en el próximo commit.

**Variaciones**: Añade todos los archivos al área de preparación.

```bash
git add .
```

#### 30. "git commit": Registra cambios en el repositorio.

```bash
git commit -m "Mensaje del commit"
```

Con este comando se registra un conjunto de cambios en el repositorio, junto con un mensaje que describe los cambios realizados. Existen muchas "buenas practicas" para escribir mensajes de commit y de ahí varias convenciones que cada equipo de trabajo adopta.

**Variaciones**: Modificar el mensaje de un commit.

```bash
git commit --amend -m "Nuevo mensaje"
```

#### 31. "git push": Sube cambios al repositorio remoto.

```bash
git push origin nombre_rama
```

Con este comando se suben los cambios locales al repositorio remoto, en la rama especificada (puede ser la rama principal o cualquier otra rama).

**Variaciones**: Forzar el push.

```bash
git push --force
```

#### 32. "git pull": Baja y fusiona cambios desde el repositorio remoto.

```bash
git pull origin nombre_rama
```

Con este comando se bajan los cambios del repositorio remoto y se fusionan con los cambios locales, en la rama especificada, en otras palabras, se actualiza el repositorio local con los cambios del repositorio remoto.

**Variaciones**: Forzar el pull.

```bash
git pull --force
```

#### 33. "git status": Muestra el estado del repositorio.

```bash
git status
```

Con este comando se muestra el estado actual del repositorio, incluidos los archivos modificados, los archivos en el área de preparación y los cambios pendientes de confirmación.

#### 34. "git branch": Gestiona las ramas.

```bash
git branch
```

Con este comando se muestran las ramas locales y se puede crear, eliminar y cambiar entre ramas.

**Variaciones**: Crear una nueva rama.

```bash
git branch nombre_rama
```

#### 35. "git checkout": Cambia entre ramas.

```bash
git checkout nombre_rama
```

Con este comando se cambia entre ramas locales, lo que permite trabajar en diferentes ramas de un repositorio.

#### 36. "git merge": Fusiona ramas.

```bash
git merge nombre_rama
```

Con este comando se fusionan los cambios de una rama en otra, lo que permite combinar el trabajo de diferentes ramas en un solo conjunto de cambios.

**Variaciones**: Fusionar una rama con la rama actual.

```bash
git merge --no-ff nombre_rama
```

donde el parámetro `--no-ff` significa "no fast-forward" y se utiliza para mantener un historial de cambios más limpio y organizado.

#### 37. "git log": Muestra el historial de commits.

```bash
git log
```

Con este comando se muestra el historial de commits del repositorio, incluidos los autores, las fechas y los mensajes de los commits.

**Variaciones**: Muestra el historial de commits en un formato más compacto (sólo una línea por commit)

```bash
git log --oneline
```

#### 38. "git tag": Gestiona las etiquetas.

```bash
git tag -a v1.0 -m "Versión 1.0"
```

Con este comando se crean etiquetas en el repositorio, lo que permite marcar versiones específicas de un proyecto, siguiendo el ejemplo, se crea una etiqueta llamada `v1.0` con un mensaje asociado que permite identificar la versión.

#### 39. "git reset": Restablece el estado del repositorio.

```bash
git reset --hard HEAD
```

Con este comando se restablece el estado del repositorio a un commit anterior, lo que permite deshacer cambios y volver a un estado anterior del proyecto. En el comando anterior, se restablece el estado del repositorio al commit más reciente (HEAD).

**Variaciones**: Restablece el estado del repositorio, **pero** mantiene los cambios en el área de preparación.

```bash
git reset --soft HEAD
```

**Variaciones**: revertir, por ejemplo 4 commits

```bash
git reset --hard HEAD~4
```

#### 40. "git remote": Gestiona los repositorios remotos.

```bash
git remote -v
```

Con este comando se muestran los repositorios remotos asociados con el repositorio local, lo que permite gestionar la conexión con los repositorios remotos.

**Variaciones**: Añadir un repositorio remoto.

```bash
git remote add nombre_repositorio url_repositorio
```

#### 41. "git config": Configura opciones de Git.

```bash
git config --global user.name "Nombre Usuario"
git config --global user.email "user@mail.com"
```

Con este comando se configuran opciones de Git, como el nombre de usuario y la dirección de correo electrónico, lo que permite identificar al autor de los commits en el log del repositorio. No sólo existen "global", también existen "local" y "system".

- global: se aplica a todos los repositorios de Git en tu sistema.
- local: se aplica solo al repositorio actual.
- system: se aplica a todos los repositorios de Git en tu sistema.

#### 42. "git diff": Muestra las diferencias entre commits.

```bash
git diff commit1 commit2
```

Con este comando se muestran las diferencias entre dos commits, lo que permite comparar los cambios realizados en diferentes momentos del proyecto.

#### 43. "git stash": Guarda temporalmente los cambios en un stash.

```bash
git stash
```

Con este comando se guardan temporalmente los cambios locales en un stash, lo que permite trabajar en otra tarea sin comprometer los cambios actuales. Es muy útil cuando estamos trabajando en una rama y necesitamos cambiar a otra rama para hacer algo rápido y luego volver a la rama original. Para recuperar los cambios guardados, se utiliza `git stash pop`.

#### 44. "git blame": Muestra quién modificó cada línea de un archivo.

```bash
git blame archivo.txt
```

Con este comando se muestra quién modificó cada línea de un archivo, lo que permite identificar a los autores de los cambios en un archivo específico. Es ideal cuando necesitamos saber el autor de un cambio especifico, no para culpar, sino para entender el **por qué** de un cambio.

#### 45. "git show": Muestra información detallada sobre un commit.

```bash
git show commit
```

Con este comando se muestra información detallada sobre un commit específico, incluidos los cambios realizados, los autores y los mensajes asociados. Es útil para revisar los cambios realizados en un commit específico.

#### 46. "git revert": Deshace un commit específico.

```bash
git revert commit
```

Con este comando se deshace un commit específico, lo que permite revertir los cambios realizados en un commit anterior sin perder el historial de cambios. Es útil cuando necesitamos deshacer un cambio específico sin afectar el resto del proyecto.

Para mas comandos e información sobre Git, puedes revisar el [Documento de Git](./git_github.md)

### Redes y conectividad:

#### 47. **ssh**: Accede a máquinas remotas de forma segura.

```bash
ssh usuario@servidor.com
```

**Variaciones**: Usa una clave privada específica para la autenticación.

```bash
ssh -i ruta_a_clave_privada usuario@servidor.com
```

#### 48. **scp**: Copia archivos entre hosts de forma segura.

```bash
scp archivo.txt usuario@servidor.com:/ruta/destino/
```

**Variaciones**: Copia un directorio recursivamente.

```bash
scp -r directorio usuario@servidor.com:/ruta/destino/
```

#### 49. **rsync**: Sincroniza archivos y directorios de manera eficiente.

```bash
rsync -avh archivo.txt usuario@servidor.com:/ruta/destino/
```

**Variaciones**: Sincroniza y elimina archivos en el destino que ya no están en el origen.

```bash
rsync -avh --delete directorio/ usuario@servidor.com:/ruta/destino/
```

#### 50. **traceroute**: Rastrea la ruta que toma un paquete para llegar a un host.

```bash
traceroute google.com
```

**Particularidad**: Útil para diagnosticar problemas de red y localizar puntos de fallos.

#### 51. **ping**: Envía paquetes ICMP a un host para verificar la conectividad de red.

```bash
ping google.com
```

**Variaciones**: Envía solo 4 paquetes.

```bash
ping -c 4 google.com
```

#### 52. **ifconfig**: Configura interfaces de red.

```bash
ifconfig
```

**Particularidad**: Muestra información sobre las interfaces de red. En sistemas modernos, se recomienda usar `ip`.

#### 53. **netstat**: Muestra conexiones de red, tablas de enrutamiento y estadísticas de interfaz.

```bash
netstat -an
```

**Variaciones**: Muestra puertos escuchando y su estado.

```bash
netstat -tuln
```

#### 54. **ssh-keygen**: Genera pares de claves de autenticación SSH.

```bash
ssh-keygen -t rsa -b 4096 -C "tuemail@example.com"
```

**Particularidad**: Crea un par de claves pública y privada para autenticación SSH.

#### 55. **curl**: Transfiere datos desde o hacia un servidor.

```bash
curl https://example.com
```

**Variaciones**: Descarga un archivo.

```bash
curl -O https://example.com/archivo.txt
```

Envía datos en una solicitud POST.

```bash
curl -X POST -d "param1=valor1&param2=valor2" https://example.com/api
```

#### 56. **nc** (Netcat): Lee y escribe datos en conexiones de red.

```bash
nc -l -p 1234
```

**Variaciones**: Se conecta a un puerto específico en un host.

```bash
nc host.com 1234
```

#### 57. **dig**: Realiza consultas DNS.

```bash
dig google.com
```

**Variaciones**: Muestra solo la dirección IP.

```bash
dig +short google.com
```

#### 58. **whois**: Consulta información de registros de dominio.

```bash
whois example.com
```

**Particularidad**: Proporciona detalles sobre el registrador, fechas de registro y expiración, y contactos administrativos.

#### 59. **hostname**: Muestra o establece el nombre del host.

```bash
hostname
```

**Variaciones**: Establece un nuevo nombre de host.

```bash
hostnamectl set-hostname nuevo_nombre
```

#### 60. **systemctl**: Controla el sistema y los servicios de administración.

```bash
systemctl status servicio
```

**Variaciones**:

- `systemctl start servicio`: Inicia un servicio.
- `systemctl stop servicio`: Detiene un servicio.
- `systemctl restart servicio`: Reinicia un servicio.
- `systemctl enable servicio`: Habilita un servicio para iniciar al arrancar.
- `systemctl disable servicio`: Deshabilita un servicio.

#### 61. **journalctl**: Muestra los registros del sistema.

```bash
journalctl -xe
```

**Variaciones**: Muestra los registros para un servicio específico.

```bash
journalctl -u servicio
```

Muestra los registros en un rango de fechas.

```bash
journalctl --since "2023-01-01" --until "2023-12-31"
```

#### 62. **crontab**: Edita la tabla de trabajos programados para el usuario.

```bash
crontab -e
```

**Particularidad**: Abre el editor para crear, editar o eliminar trabajos programados.

**Ejemplo de entrada en crontab**:

```bash
# Ejecuta un script cada día a las 3 AM
0 3 * * * /ruta/al/script.sh
```

Estos ejemplos proporcionan una guía completa y práctica sobre los comandos esenciales relacionados con redes y conectividad, siguiendo el estilo de tu libro. ¡Espero que te sea útil!

### Administración de usuarios y grupos:

#### 63. **whoami**: Muestra el nombre del usuario actual.

```bash
whoami
```

**Particularidad**: Útil para verificar la identidad del usuario que está ejecutando comandos.

#### 64. **sudo**: Ejecuta un comando con privilegios de superusuario.

```bash
sudo comando
```

**Variaciones**: Inicia una sesión de shell como root.

```bash
sudo -i
```

#### 65. **su**: Cambia de usuario o a superusuario.

```bash
su usuario
```

**Variaciones**: Cambia a superusuario e inicia un nuevo shell.

```bash
su -
```

#### 66. **passwd**: Cambia la contraseña de un usuario.

```bash
passwd
```

**Variaciones**: Cambia la contraseña de otro usuario.

````bash
sudo passwd usuario


#### 67. **groups**: Muestra los grupos a los que pertenece un usuario.

```bash
groups
````

**Variaciones**: Muestra los grupos de un usuario específico.

```bash
groups usuario
```

#### 68. **useradd**: Crea un nuevo usuario.

```bash
sudo useradd -m nuevo_usuario
```

**Variaciones**: Especifica un shell para el nuevo usuario.

```bash
sudo useradd -m -s /bin/bash nuevo_usuario
```

#### 69. **userdel**: Elimina un usuario.

```bash
sudo userdel usuario
```

**Variaciones**: Elimina al usuario y su directorio personal.

```bash
sudo userdel -r usuario
```

#### 70. **groupadd**: Crea un nuevo grupo.

```bash
sudo groupadd nuevo_grupo
```

**Particularidad**: Útil para gestionar permisos y accesos.

#### 71. **groupdel**: Elimina un grupo.

```bash
sudo groupdel grupo
```

**Particularidad**: Solo puede eliminarse si no hay usuarios en el grupo.

#### 72. **usermod**: Modifica una cuenta de usuario.

```bash
sudo usermod -aG grupo usuario
```

**Variaciones**: Cambia el shell de un usuario.

```bash
sudo usermod -s /bin/zsh usuario
```

#### 73. **groupmod**: Modifica un grupo.

```bash
sudo groupmod -n nuevo_nombre viejo_nombre
```

**Particularidad**: Permite cambiar el nombre de un grupo existente.

Estos ejemplos y variaciones deberían proporcionar una guía clara y práctica sobre cómo utilizar estos comandos de administración de usuarios y grupos, siguiendo el estilo de tu libro. ¡Espero que te sea útil para completarlo!

### Administración de procesos:

#### 74. **ps**: Muestra información sobre los procesos en ejecución.

```bash
ps aux
```

**Variaciones**: Muestra una lista detallada de todos los procesos.

```bash
ps -ef
```

#### 75. **kill**: Envía una señal a un proceso, generalmente para terminarlo.

```bash
kill PID
```

**Variaciones**: Fuerza la terminación de un proceso.

```bash
kill -9 PID
```

#### 76. **top**: Muestra en tiempo real los procesos en ejecución y el uso del sistema.

```bash
top
```

**Particularidad**: Proporciona una vista dinámica de la actividad del sistema.

#### 77. **df**: Muestra el uso del espacio en disco de los sistemas de archivos.

```bash
df -h
```

**Particularidad**: La opción `-h` muestra los tamaños en un formato legible por humanos.

#### 78. **du**: Muestra el uso del espacio en disco por archivos y directorios.

```bash
du -sh directorio/
```

**Variaciones**: Muestra el uso del espacio en disco de los directorios en el nivel superior.

```bash
du -h --max-depth=1
```

#### 79. **head**: Muestra las primeras líneas de un archivo.

```bash
head archivo.txt
```

**Variaciones**: Muestra las primeras 20 líneas del archivo.

```bash
head -n 20 archivo.txt
```

#### 80. **tail**: Muestra las últimas líneas de un archivo.

```bash
tail archivo.txt
```

**Variaciones**: Muestra las últimas líneas de un archivo y sigue actualizándolo.

```bash
tail -f archivo.txt
```

#### 81. **sort**: Ordena líneas de texto.

```bash
sort archivo.txt
```

**Variaciones**: Ordena las líneas en orden inverso.

```bash
sort -r archivo.txt
```

Ordena las líneas numéricamente.

```bash
sort -n archivo.txt
```

#### 82. **wc**: Cuenta líneas, palabras y caracteres.

```bash
wc archivo.txt
```

**Variaciones**: Cuenta solo las líneas.

```bash
wc -l archivo.txt
```

Cuenta solo las palabras.

```bash
wc -w archivo.txt
```

Cuenta solo los caracteres.

```bash
wc -c archivo.txt
```

#### 83. **date**: Muestra o establece la fecha y hora del sistema.

```bash
date
```

**Variaciones**: Muestra la fecha en el formato `YYYY-MM-DD`

```bash
date +%Y-%m-%d
```

#### 84. **history**: Muestra el historial de comandos.

```bash
history
```

**Variaciones**: Busca un comando específico en el historial.

```bash
history | grep comando
```

#### 85. **lsof**: Lista archivos abiertos y los procesos que los abrieron.

```bash
lsof
```

**Variaciones**: Lista los procesos que están utilizando el puerto 80.

```bash
lsof -i :80
```

#### 86. **mount**: Monta un sistema de archivos.

```bash
sudo mount /dev/sdX1 /mnt
```

**Variaciones**: Especifica el tipo de sistema de archivos al montar.

```bash
sudo mount -t tipo /dev/sdX1 /mnt
```

#### 87. **umount**: Desmonta un sistema de archivos.

```bash
sudo umount /mnt
```

**Particularidad**: Asegúrate de que el sistema de archivos no esté en uso antes de desmontarlo.

#### 88. **screen**: Permite gestionar sesiones de terminal múltiples.

```bash
screen
```

**Variaciones**: Crea una nueva sesión con un nombre específico.

```bash
screen -S nombre_sesion
```

Reconecta una sesión.

```bash
screen -r nombre_sesion`
```

#### 89. **tmux**: Multiplexador de terminal que permite dividir una terminal en múltiples sesiones.

```bash
tmux
```

**Variaciones**: Crea una nueva sesión con un nombre específico.

```bash
tmux new -s nombre_sesion
```

Reconecta una sesión.

```bash
tmux attach -t nombre_sesion`
```

#### 90. **watch**: Ejecuta un comando de forma repetida y muestra la salida en tiempo real.

```bash
watch comando
```

**Variaciones**: Ejecuta el comando cada 5 segundos.

```bash
watch -n 5 comando
```

WIP: 10 comandos más
