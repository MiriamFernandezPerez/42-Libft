# 📚 Libft - Biblioteca Personal en C

---

## ✨ Propósito y Alcance

**Libft** es una biblioteca personalizada que reimplementa funciones estándar de C y añade utilidades adicionales. Los objetivos principales son:

* ✅ Proporcionar implementaciones fiables de **funciones esenciales de C**.
* 🔁 Crear una **base de código reutilizable** para futuros proyectos en C.
* 🎯 Demostrar comprensión de **conceptos fundamentales de programación**.

---

## 🧱 Arquitectura de la Biblioteca

La biblioteca está organizada en categorías funcionales que abarcan diferentes aspectos de la programación en C:

* **Gestión de Memoria** 🧠
* **Procesamiento de Cadenas** 🔤
* **Clasificación de Caracteres** 🔎
* **Conversión de Datos** 🔄
* **Entrada/Salida de Archivos** 📂
* **Funciones Adicionales (Bonus)** 🎁

---

## 🔧 Componentes Principales

### 🧠 Funciones de Gestión de Memoria

Funciones para la asignación, inicialización y manipulación de memoria:

* `ft_memset`, `ft_bzero`, `ft_memcpy`, `ft_memmove`, `ft_memchr`, `ft_memcmp`, `ft_calloc`

### 🔤 Funciones de Procesamiento de Cadenas

Funciones para la manipulación y análisis de cadenas:

* `ft_strlen`, `ft_strchr`, `ft_strrchr`, `ft_strncmp`, `ft_strlcpy`, `ft_strlcat`, `ft_strnstr`, `ft_strdup`
* **Operaciones avanzadas**: `ft_substr`, `ft_strjoin`, `ft_strtrim`, `ft_split`, `ft_strmapi`, `ft_striteri`

### 🔎 Funciones de Clasificación de Caracteres

Funciones para verificar el tipo de carácter y realizar conversiones:

* `ft_isalpha`, `ft_isdigit`, `ft_isalnum`, `ft_isascii`, `ft_isprint`, `ft_tolower`, `ft_toupper`

### 🔄 Funciones de Conversión de Datos

Funciones para convertir entre diferentes tipos de datos:

* `ft_atoi`, `ft_itoa`

### 📂 Funciones de Entrada/Salida de Archivos

Funciones para la salida en descriptores de archivos:

* `ft_putchar_fd`, `ft_putstr_fd`, `ft_putendl_fd`, `ft_putnbr_fd`

### 🎁 Funciones Adicionales (Bonus)

#### 🔗 Funciones de Listas Enlazadas

Funciones para crear y manipular listas enlazadas:

* `ft_lstnew`, `ft_lstadd_front`, `ft_lstsize`, `ft_lstlast`, `ft_lstadd_back`, `ft_lstdelone`, `ft_lstclear`, `ft_lstiter`, `ft_lstmap`

---

## 🛠️ Sistema de Construcción

La biblioteca utiliza un **Makefile** para gestionar la compilación y los procesos de construcción:

| Objetivo | Descripción                                  |
| :------- | :------------------------------------------- |
| `all`    | Compila la biblioteca principal              |
| `bonus`  | Compila la biblioteca con funciones bonus    |
| `clean`  | Elimina los archivos objeto                  |
| `fclean` | Elimina los archivos objeto y la biblioteca  |
| `re`     | Reconstruye la biblioteca principal          |
| `rebonus`| Reconstruye la biblioteca con funciones bonus|

La compilación se realiza con `gcc` y las banderas `-Wall -Wextra -Werror` para asegurar la calidad del código y detectar posibles errores.

---

## 🚀 Flujo de Uso de la Biblioteca

1.  🧱 **Compila la biblioteca** utilizando el `Makefile`.
2.  📥 **Incluye `libft.a`** en tu proyecto.
3.  🧠 **Utiliza las funciones** proporcionadas para facilitar el desarrollo en C.

---

## 📌 Resumen

**Libft** es una biblioteca completa en C que proporciona implementaciones de funciones estándar y utilidades adicionales. Está organizada en categorías funcionales que incluyen gestión de memoria, procesamiento de cadenas, clasificación de caracteres, conversión de datos, entrada/salida de archivos y operaciones con listas enlazadas. La biblioteca se construye como una **biblioteca estática (`libft.a`)** y puede integrarse fácilmente en proyectos en C.
