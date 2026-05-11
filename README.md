# 🧪 Laboratorio - Implementación de Autocarga PSR-4 con Composer

## 📖 Introducción

Este laboratorio implementa la carga automática de clases utilizando el estándar PSR-4 junto con Composer en PHP.

El objetivo es eliminar el uso manual de include y require mediante Namespaces y autoload.

---

# ⚙️ Requisitos

- PHP 8 o superior
- Composer instalado
- Visual Studio Code

---

# 🚀 Instalación

## 1. Clonar el repositorio

```bash
git clone URL_DEL_REPOSITORIO
```

## 2. Entrar al proyecto

```bash
cd AUTOCARGAAUTOMATICA
```

## 3. Generar autoload

```bash
composer dump-autoload
```

---

# 📂 Estructura del Proyecto

```txt
AUTOCARGAAUTOMATICA/
│
├── App/
│   └── User.php
│
├── Database/Model/
│   └── ProductModel.php
│
├── composer.json
├── prueba.php
└── vendor/
```

---

# 🧠 Funcionamiento

Composer utiliza PSR-4 para cargar automáticamente las clases usando namespaces.

Ejemplo:

```php
use App\User;
```

Sin necesidad de usar include o require manualmente.

---

# 🖥️ Ejemplo de Ejecución

```php
require 'vendor/autoload.php';

use App\User;

$user = new User();
```

---

# 📸 Evidencias

## Composer funcionando

(AQUÍ VA TU CAPTURA)

## Programa funcionando

(AQUÍ VA TU CAPTURA)

---

# 📚 Conclusiones Técnicas

## 1. Mantenibilidad

Permite agregar nuevas clases fácilmente.

## 2. Eficiencia

Las clases se cargan únicamente cuando se necesitan.

## 3. Organización

PSR-4 mantiene una estructura limpia y profesional.

---

# 👨‍💻 Autor

Ana Cheung