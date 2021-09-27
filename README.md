# Instalacion_Sublime_Text
Este repositorio explica la instalación del Sublime text

## Introdución

¿Qué es Sublime Text?

Sublime Text es un editor de texto que permite muchos lenguajes(ASP, C, C++, C#, CSS, D, Erlang, Groovy, Haskell, HTML, Java, Javascript), siendo este muy ligero y útil, permitiendo tener varios documentos abiertos en pestañas.

<div align="center">
<img width="50%" src="https://www.easyappcode.com/upload/post-716768416.jpg">
</div>


## Pasos de Instalación

### 1.Actualizar
Primero debemos actualizar los repositorios con
```
apt-get upgrade
```

<div align="center">
<img width="100%" src="http://drive.google.com/uc?export=view&id=1L1S_4svqyHMwSsqMS3ZM93zjIdOrI6EU">
</div>

### 2.Instalación de Transport

Instalamos el transport con
```
sudo apt-get install apt-transport-https
```
<div align="center">
<img width="100%" src="http://drive.google.com/uc?export=view&id=1PaImYIoK3V-YOgrSTreeHukBSHJ82QHZ">
</div>


### 3.Últimos pasos

Utilizamos este comando para terminar la instalación
```
echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
```

<div align="center">
<img width="100%" src="http://drive.google.com/uc?export=view&id=1skTkqcu3E6_FvK6Z2pnnrdFGKOM6y5mi">
</div>

### 4.Actualizar

Actualizamos repositorios con 
```
sudo apt update
```
<div align="center">
<img width="100%" src="http://drive.google.com/uc?export=view&id=1Qn_OLF0hsg7dM-BhEgpGmK6CpiStg7ul">
</div>


### 5.Instalamos Sublime Text

Después instalamos el Sublime Text con 
```
sudo apt install sublime-text
```

<div align="center">
<img width="100%" src="http://drive.google.com/uc?export=view&id=1nEK1ha0D06k1yQawCXBWS6QgMsfuevyz">
</div>

## Conclusión

Así podemos descargar el Sublime Text, un buen editor de texto que permite utilizar muchos lenguajes. 


