# 🐧 Debian Bug Tracker – Guía para Administradores

Bienvenido a este repositorio de seguimiento de fallos (bugs) enfocado en sistemas **Debian**.
Aquí encontrarás herramientas, enlaces y comandos útiles para reportar, consultar y gestionar errores de forma profesional.

- [🐧 Debian Bug Tracker – Guía para Administradores](#-debian-bug-tracker--guía-para-administradores)
  - [🔍 Consulta de bugs](#-consulta-de-bugs)
  - [📦 Bugs por paquete](#-bugs-por-paquete)
  - [🛠️ Reportar bugs](#️-reportar-bugs)
  - [📖 Guía oficial de reporte](#-guía-oficial-de-reporte)
  - [✨ Extras útiles](#-extras-útiles)
    - [📊 Buscar bugs desde terminal](#-buscar-bugs-desde-terminal)
    - [🔎 Ver información detallada de un paquete](#-ver-información-detallada-de-un-paquete)
    - [📁 Logs importantes](#-logs-importantes)
  - [🎨 Notas de estilo del repositorio](#-notas-de-estilo-del-repositorio)
  - [🧠 Recomendaciones](#-recomendaciones)
  - [🐧 Debian FTW](#-debian-ftw)


---


---

## 🔍 Consulta de bugs

Repositorio oficial de seguimiento de errores de Debian:

```
https://bugs.debian.org/
```

👉 Aquí puedes ver:

* Todos los bugs abiertos
* Bugs corregidos
* Historial completo de incidencias

---

## 📦 Bugs por paquete

Consulta errores específicos de un paquete:

```
https://bugs.debian.org/<nombre-del-paquete>
```

Ejemplo:

```
https://bugs.debian.org/bash
```

📌 Nota:

* Usa el pseudo-paquete `wnpp` para solicitar nuevos paquetes (aunque no estén en Debian).

---

## 🛠️ Reportar bugs

Herramienta recomendada:

```
reportbug
```

Instalación:

```bash
sudo apt update
sudo apt install reportbug
```

Uso:

```bash
reportbug
```

📨 Este comando enviará el bug por correo electrónico de forma estructurada.

---

## 📖 Guía oficial de reporte

Documentación oficial:

```
https://www.debian.org/Bugs/Reporting
```

Incluye:

* Buenas prácticas
* Qué información incluir
* Cómo hacer reportes efectivos

---

## ✨ Extras útiles

### 📊 Buscar bugs desde terminal

```bash
apt list --upgradable
apt-cache policy <paquete>
```

---

### 🔎 Ver información detallada de un paquete

```bash
apt show <paquete>
```

---

### 📁 Logs importantes

Revisa logs para encontrar errores:

```bash
/var/log/syslog
/var/log/dpkg.log
/var/log/apt/history.log
```

---

## 🎨 Notas de estilo del repositorio

* Uso de bloques `code` para fácil copia
* Enlaces limpios y accesibles
* Organización clara para administradores
* Basado en flujo de trabajo real en Debian

---

## 🧠 Recomendaciones

* Siempre revisa si el bug ya existe antes de reportarlo
* Sé claro y específico en los reportes
* Incluye versiones, logs y pasos para reproducir el error

---

## 🐧 Debian FTW

Este repositorio está pensado para administradores que buscan eficiencia, claridad y buenas prácticas en la gestión de bugs en Debian.

---

<br>

<p align="right">
  <img src="./logo/logo.JPG" alt="MasofieDeploy" width="80"/>
</p>