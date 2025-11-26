# Comandos que aprendí en Ubuntu
#Cristóbal Serna, 4506706

A continuación se presenta una guía sobre comandos básicos de Linux (Ubuntu) y su función

---

##Navegación de directorios

### **`pwd`**

Muestra la ruta completa del directorio actual.

### **`ls`**

Lista los archivos y carpetas en el directorio actual.

* `ls -l` → lista detallada
* `ls -a` → incluye archivos ocultos

### **`cd`**

Permite moverse entre directorios.

* `cd nombre_carpeta/`
* `cd ..` → retroceder un nivel

---

## Gestión de archivos y directorios

### **`mkdir`**

Crea un nuevo directorio.

```bash
mkdir nueva_carpeta
```

### **`touch`**

Crea un archivo vacío.

```bash
touch archivo.txt
```

### **`cp`**

Copia archivos o directorios.

```bash
cp archivo.txt destino/
cp -r carpeta/ destino/
```

### **`mv`**

Mueve o renombra archivos.

```bash
mv archivo.txt carpeta/
mv viejo.txt nuevo.txt
```

### **`rm`**

Elimina archivos o carpetas.

```bash
rm archivo.txt
rm -r carpeta/
```

> **Precaución:** `rm -r` borra todo el contenido del directorio.

---

## Visualización de contenido

### **`cat`**

Muestra el contenido de un archivo.

### **`head` / `tail`**

Muestra las primeras o últimas líneas de un archivo.

### **`less`**

Permite ver archivos largos de forma paginada.

---

## Sistema y administración

### **`sudo`**

Ejecuta un comando como administrador.

### **`apt update`**

Actualiza la lista de paquetes.

### **`apt upgrade`**

Instala actualizaciones disponibles.

### **`df -h`**

Muestra el uso del disco.

### **`free -h`**

Muestra el uso de memoria RAM.

### **`top`**

Muestra procesos en ejecución en tiempo real.

---

## Red

### **`ping`**

Comprueba el estado de la conexión hacia un host.

### **`ifconfig`** (o `ip a`)

Muestra configuración de red.

### **`curl`**

Realiza solicitudes HTTP desde la terminal.

---

## Búsqueda

### **`find`**

Busca archivos por nombre.

```bash
find /ruta -name "archivo.txt"
```

### **`grep`**

Busca texto dentro de archivos.

```bash
grep "palabra" archivo.txt
```

---

