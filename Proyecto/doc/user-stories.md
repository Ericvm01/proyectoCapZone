
# 👤 Historias de Usuario (User Stories) - CapZone

Este documento recopila las historias de usuario desglosadas a partir del Product Backlog, especificando sus criterios de aceptación para garantizar el cumplimiento de los requerimientos funcionales del sistema.

---

## 🛠️ Módulo: Catálogo de Productos

### US-01: Visualización del Catálogo
* **Como** cliente de la tienda online,
* **Quiero** visualizar una lista organizada de las gorras disponibles con su imagen, precio y nombre,
* **Para** explorar los productos que ofrece la marca de manera rápida y atractiva.

#### Criterios de Aceptación:
1. La página principal debe mostrar una cuadrícula con los productos activos.
2. Cada tarjeta de producto debe incluir: Imagen principal, Nombre, Precio y un botón de "Ver detalle".
3. El diseño debe ser responsivo (adaptable a dispositivos móviles y de escritorio).

---

### US-02: Filtrado y Búsqueda de Productos
* **Como** usuario interesado en un estilo específico,
* **Quiero** filtrar el catálogo por categorías (ej. Snapback, Dad Hat, Trucker) y rangos de precio,
* **Para** encontrar con mayor facilidad el producto que se adapte a mis gustos.

#### Criterios de Aceptación:
1. Debe existir una barra o panel lateral de filtros visible en la vista del catálogo.
2. Al seleccionar un filtro, la lista de productos debe actualizarse de forma dinámica o mediante un botón de aplicar.
3. Si no se encuentran productos con los criterios seleccionados, se debe mostrar un mensaje amigable indicando que no hay resultados.

---

### US-03: Detalle del Producto
* **Como** comprador interesado en una gorra,
* **Quiero** hacer clic en un producto para ver su información ampliada (descripción completa, galería de fotos y tallas/colores disponibles),
* **Para** tomar una decisión de compra informada.

#### Criterios de Aceptación:
1. Al seleccionar un producto, el sistema debe redirigir a una vista de detalle.
2. Se deben mostrar múltiples imágenes o ángulos de la gorra si están disponibles.
3. El selector de cantidad y variantes (si aplica) debe bloquearse o advertir si el stock es cero.

---

## 🛒 Módulo: Carrito de Compras

### US-04: Agregar Productos al Carrito
* **Como** usuario de la plataforma,
* **Quiero** agregar productos seleccionados al carrito de compras especificando la cantidad,
* **Para** acumular los artículos que deseo adquirir antes de proceder al pago.

#### Criterios de Aceptación:
1. El botón "Agregar al carrito" debe actualizar un contador visual en el encabezado de la página.
2. Si el producto ya está en el carrito, se debe incrementar su cantidad en lugar de duplicar la línea (o permitir gestionarlo de forma fluida).
3. Debe mostrarse una alerta o notificación flotante confirmando que el producto fue añadido con éxito.
