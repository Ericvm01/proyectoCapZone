* F-3.1 Operaciones básicas del carrito: Agregar productos indicando variante (talla/color), modificar cantidades y eliminar ítems.

HU-3.1 - Operaciones Básicas del Carrito

Código Requerimiento: F-3.1

Rol: Cliente / Visitante

Descripción:

Como cliente de la tienda,

quiero agregar productos indicando variante (talla/color), modificar cantidades o eliminar ítems,

para gestionar las gorras que deseo adquirir antes de pagar.

Criterios de Aceptación:

Agregar ítems al carrito especificando cantidad y variante.

Validar que la cantidad no exceda el stock real.

Controles para incrementar, decrementar o eliminar ítems en el carrito.

 * F-3.2 Persistencia del carrito: Guardado del carrito en la sesión del usuario para conservar los ítems al navegar o volver a iniciar sesión.

HU-3.2 - Persistencia del Carrito de Compras

Código Requerimiento: F-3.2

Rol: Cliente / Visitante

Descripción:

Como cliente de la tienda,

quiero que el contenido de mi carrito se conserve mientras navego o al reiniciar sesión,

para no perder las gorras seleccionadas.

Criterios de Aceptación:

Persistencia en localStorage/cookies para usuarios invitados.

Vinculación del carrito a la base de datos para usuarios autenticados.

Fusión automática (merge) de carritos al pasar de visitante a usuario autenticado.

 * F-3.3 Resumen de costos: Cálculo automático e inmediato de subtotales, impuestos y desgloses de precio según la cantidad seleccionada.

HU-3.3 - Resumen y Cálculo de Costos

Código Requerimiento: F-3.3

Rol: Cliente / Visitante

Descripción:

Como cliente,

quiero ver un desglose automático con subtotal, impuestos y total de mi carrito,

para tener claridad sobre el monto a pagar.

Criterios de Aceptación:

Recálculo automático e inmediato ante cualquier cambio en los ítems.

Desglose detallado: Subtotal, Impuestos, Estimado de envío y Total.

Coincidencia exacta de totales entre el frontend y las validaciones de backend.
