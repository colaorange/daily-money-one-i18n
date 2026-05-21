
[`Ver video introductorio en YouTube`](https://youtu.be/uN3GkA_Afuw)
[`Documento en línea`](https://colaorange.gitbook.io/daily-money-one-doc/eng)

## Conceptos

Los conceptos principales de Daily Money son muy simples; solo hay tres:

> 1. Uno o varios `Libros`
> 2. Varias `Cuentas` dentro de los libros
> 3. Transferir importes entre distintas cuentas y registrar estas `Transacciones`

## ![Libros](icon:///notebook-multiple) Libros

Se necesita al menos un libro, con cuentas que usen la misma unidad monetaria. También puedes crear varios libros con la misma unidad monetaria según tus necesidades.

## ![Cuentas](icon:///bookmark-multiple) Cuentas

Hay cinco tipos distintos de cuentas, que puedes agregar, editar o eliminar en la pantalla de gestión de cuentas.

> - `Ingreso`: salario, etc.
> - `Gasto`: comida, entretenimiento, etc.
> - `Activo`: efectivo, banco, etc.
> - `Deuda`: tarjetas de crédito, préstamos, etc.
> - `Otro`: ...

* Los nombres de cuenta pueden usar puntos (.) para separar niveles (por ejemplo, Comida.Cenar, Comida.Reuniones), lo que ofrece una mejor visualización jerárquica al seleccionar cuentas o ver hojas de balance.
* Puedes ordenar las cuentas para priorizar las que usas con más frecuencia.

## ![Transacciones](icon:///receipt) Transacciones 

Cuando hay una transacción entre cuentas, como un gasto, mover dinero entre cuentas o pagar con tarjeta de crédito (por ejemplo, gastaste 320 yuanes en una comida), usa `Nueva transacción` para crear una transacción nueva.
> - Selecciona `Fecha y hora`: fecha y hora de la transacción.
> - Selecciona `Origen`: Efectivo
> - Selecciona `Destino`: Comidas
> - Ingresa `Importe`: 320
> - Ingresa `Nota`: Reunión con amigos
> - Pulsa `Crear`

## Ejemplos

### Transferencia de salario al banco

> Cuenta de `Ingreso` de origen: Salario
> Cuenta de `Activo` de destino: Banco

### Retirar efectivo del banco

> Cuenta de `Activo` de origen: Banco
> Cuenta de `Activo` de destino: Efectivo

### Comprar un teléfono con tarjeta de crédito

> Cuenta de `Deuda` de origen: Tarjeta de crédito
> Cuenta de `Gasto` de destino: Electrónica

### Pagar la factura de la tarjeta de crédito con el banco

> Cuenta de `Activo` de origen: Banco 
> Cuenta de `Deuda` de destino: Tarjeta de crédito

## ![Hoja de balance](icon:///scale-balance)![Gráfico de balance](icon:///chart-pie) Hoja de balance y gráfico

Al llevar tus cuentas con constancia, la aplicación te ayudará a registrar todos los detalles de las transacciones y generar una hoja de balance según las condiciones de consulta. Esta hoja muestra claramente el saldo de activos y deudas en distintos periodos, para que entiendas mejor tu situación financiera. Además, la aplicación puede generar varios gráficos para representar visualmente tus ingresos y gastos, facilitando la comprensión de tu flujo financiero.

## Saldos iniciales de las cuentas

Cuando usas la aplicación por primera vez, puede que ya tengas algunas cuentas actuales con valores reales, como depósitos bancarios, efectivo disponible o deudas de tarjeta de crédito. Para que la hoja de balance ofrezca cálculos más precisos, puedes usar la función de inicializar cuentas para establecer los saldos iniciales correctos de estas cuentas. Así, la hoja de balance podrá reflejar tu situación financiera real.

## División de uno a muchos (avanzado)

A veces, un solo gasto puede involucrar varias categorías. Por ejemplo, al comprar en un supermercado, puedes adquirir comida, artículos de uso diario y productos electrónicos al mismo tiempo. Para esta situación, la aplicación ofrece creación y edición avanzada de transacciones, lo que permite asignar un solo gasto a varias categorías distintas. En otras palabras, puedes asignar el importe de un pago con tarjeta de crédito a varias categorías, como comida, artículos diarios y productos electrónicos. Ten en cuenta: en transacciones dentro del mismo libro, como las unidades monetarias son iguales, el importe total transferido desde el origen debe ser igual al importe total transferido al destino; de lo contrario, el programa rechazará la creación de la transacción.

## Transferencia entre libros

El programa permite transferir entre cuentas de distintos libros. Ya sea en la pantalla básica o avanzada de edición o creación de transacciones, puedes seleccionar cuentas de otros libros al elegir las cuentas. Como los valores de moneda entre distintos libros pueden diferir y el tipo de cambio no es fijo en ese momento, por ejemplo al transferir de nuevos dólares taiwaneses a dólares estadounidenses, el programa no te limitará a crear una transacción donde el total transferido desde el origen deba ser igual al total transferido al destino. Crea las transacciones según los importes reales y ten cuidado.

## Vista rápida de hoja de balance y gráficos

Al navegar por la hoja de balance o los gráficos, puedes agregar cuentas específicas a Vista rápida en la pantalla de inicio [*1]. Solo desliza a la derecha sobre el elemento en la hoja de balance y pulsa `Agregar a Vista rápida`, o pulsa el icono "Agregar a Vista rápida" en la esquina superior derecha de la tarjeta del gráfico de balance. Luego, en la pantalla de inicio, verás el saldo de activos y deudas de ese elemento, o podrás consultarlo en la página de gráficos de la pantalla de inicio. Además, puedes ordenar o quitar estos elementos en `Preferencias > Pantalla de inicio`.

[*1] Demasiados elementos de Vista rápida en la pantalla de inicio pueden afectar el tiempo de carga de la pantalla de inicio.

## Plantillas y programación recurrente

Puedes configurar plantillas de transacción para acciones contables comunes, lo que te permite agregar transacciones rápidamente. También puedes configurar plantillas de programación recurrente para acciones contables periódicas. El programa te notificará cuando venzan, permitiéndote agregar rápidamente la transacción y programarla automáticamente para la siguiente fecha. Solo desliza a la izquierda sobre el elemento en la lista de transacciones, pulsa `Nueva plantilla`, ingresa la hora de programación y créala. Además, puedes ordenar, editar o quitar estos elementos en la página `Plantillas`.

## Configuración de presupuestos

Al navegar por la hoja de balance, simplemente desliza a la derecha sobre una cuenta, pulsa `Crear presupuesto` y selecciona el modo. Una vez creado, puedes ver el progreso del presupuesto en la hoja de balance o en Vista rápida en la pantalla de inicio. Además, puedes ordenar, editar o quitar estos elementos en la página `Presupuestos`.
