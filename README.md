# 🌐 Herramientas de Redes

Una suite web moderna, rápida y ligera diseñada para administradores de sistemas, ingenieros de redes y estudiantes. Construida con **Astro** y optimizada para el rendimiento.

## 🚀 Características Principales

### 🔹 Herramientas IPv4
Accede a un conjunto completo de utilidades para gestionar redes IPv4 de forma eficiente:

*   **Calculadora IPv4**: Calcula instantáneamente la máscara de red, dirección de red, broadcast, primer host, último host y número total de hosts a partir de una dirección IP y CIDR.
*   **Divisor de Subredes (Subnetting)**: Divide una red base en múltiples subredes más pequeñas de forma rápida y visual.
*   **Agrupador de Redes (Supernetting)**: Resume y agrupa múltiples subredes en una red mayor para optimizar tablas de enrutamiento.

### 🔹 Próximamente: IPv6 🛠️
Actualmente trabajando en la implementación de:
*   Calculadora de subredes IPv6.
*   Herramientas de compresión y descompresión de direcciones.

---

## 🛠️ Tecnologías

Este proyecto utiliza tecnologías de vanguardia para ofrecer una experiencia fluida:

*   **[Astro](https://astro.build/)**: Framework web para una carga ultrarrápida (enfocado en Islas de Arquitectura).
*   **Javascript Puro**: Lógica de cálculo optimizada sin dependencias pesadas.
*   **CSS Moderno**: Interfaz limpia, responsive y enfocada en la usabilidad.
*   **[Bun](https://bun.sh/)**: Runtime de Javascript de alto rendimiento para desarrollo y gestión de paquetes.

---

## 📦 Instalación y Desarrollo

Para ejecutar este proyecto localmente:

1.  **Instala las dependencias**:
    ```bash
    bun install
    ```

2.  **Inicia el servidor de desarrollo**:
    ```bash
    bun dev
    ```

3.  **Abre tu navegador** en `http://localhost:4321`.

---

## 🏗️ Estructura del Proyecto

```text
/
├── src/
│   ├── components/     # Componentes de las herramientas (Calculadora, Divisor, etc.)
│   ├── layouts/        # Plantillas base de la aplicación
│   └── pages/          # Páginas principales (Inicio, IPv4, IPv6)
├── public/             # Recursos estáticos
└── package.json        # Configuración y dependencias
```

---

Desarrollado para facilitar las tareas diarias de gestión de redes.
