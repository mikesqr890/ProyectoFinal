
# De'yes | Tienda virtual y Cápsula de Outfit

De'yes es una aplicación web desarrollada como proyecto académico para una tienda de ropa, calzado y accesorios ubicada en Florida, Valle del Cauca.

Su objetivo es facilitar la búsqueda de productos, la realización de pedidos y la creación de combinaciones de prendas mediante una herramienta llamada **Cápsula de Outfit**.

## Enlaces del proyecto

| Recurso | Enlace |
|---|---|
| Página web | [De'yes en Netlify](https://deyes.netlify.app/) |
| Repositorio | [GitHub - ProyectoFinal](https://github.com/mikesqr890/ProyectoFinal) |
| Informe final | [Ver informe](docs/Informe_Final_DeYes.docx) |
| Propuesta gráfica | Pendiente de agregar |

## Integrantes

- Michael Steven Quimbayo Rodriguez

## Tecnologías utilizadas

- **React:** desarrollo de la interfaz.
- **Vite:** entorno de desarrollo y compilación.
- **JavaScript:** funcionalidades y lógica del sistema.
- **CSS y SCSS:** diseño y estilos.
- **Supabase:** autenticación, base de datos, almacenamiento de imágenes y chat en tiempo real.
- **React Router:** navegación entre páginas.
- **Netlify:** publicación de la aplicación.
- **Git y GitHub:** control de versiones.

## Funcionalidades

### Clientes

- Registro e inicio de sesión.
- Catálogo con búsqueda, filtros y ordenamiento.
- Carrito de compras con control de cantidades.
- Registro y consulta de pedidos.
- Creación de outfits personalizados.
- Recomendaciones de prendas y accesorios.
- Guardado de outfits en Supabase.
- Chat de atención con el administrador.
- Visualización de la ubicación de referencia de la tienda.

### Administrador

- Administración de productos e inventario.
- Registro, edición y eliminación de productos.
- Consulta de pedidos realizados.
- Actualización del estado de los pedidos.
- Organización de pedidos pendientes.
- Chat con conversaciones independientes por cliente.
- Correo del admin: maicsqr@gmail.com
- Contraseña: Andyssj123.

## Estructuras de datos implementadas

El proyecto utiliza cinco estructuras de datos:

| Estructura | Aplicación |
|---|---|
| Grafo | Recomendación de productos para completar outfits. |
| Trie | Búsqueda de productos por prefijos. |
| Árbol binario de búsqueda | Ordenamiento de productos por precio. |
| Pila (Stack) | Deshacer cambios realizados en el carrito. |
| Cola (Queue) | Organización de pedidos pendientes por orden de llegada. |

Las estructuras se encuentran en:

`src/helpers/dataStructures/`

## Instalación y ejecución

Clonar el repositorio:

```bash
git clone https://github.com/mikesqr890/ProyectoFinal.git
```

Ingresar a la carpeta que contiene `package.json` e instalar las dependencias:

```bash
npm install
```

Crear un archivo `.env.local` con las variables públicas de Supabase:

```env
VITE_SUPABASE_URL=https://TU_PROYECTO.supabase.co
VITE_SUPABASE_PUBLISHABLE_KEY=TU_CLAVE_PUBLICA
```

Ejecutar el proyecto:

```bash
npm run dev
```

## Pruebas

Para ejecutar las pruebas de las estructuras de datos:

```bash
node --test tests/structures.test.js
```

Para generar la versión de producción:

```bash
npm run build
```

## Documentación

El informe completo se encuentra en:

[Informe_Final_DeYes.docx](docs/Informe_Final_DeYes.docx)

El documento explica el funcionamiento del sistema, sus módulos, las tecnologías utilizadas y la implementación de las cinco estructuras de datos.

## Publicación

La aplicación está publicada en Netlify:

https://deyes.netlify.app/

El frontend está alojado en Netlify y utiliza Supabase como servicio de backend.

---

**Proyecto Final - De'yes**
```
