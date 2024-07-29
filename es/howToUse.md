
[`Ver video de introducción en YouTube`](https://youtu.be/uN3GkA_Afuw)

## Conceptos

Los conceptos principales de Daily Money son muy simples, solo hay tres:

> 1. Uno o muchos `Libros de Cuentas`
> 2. Varios `Cuentas` dentro de los Libros de Cuentas
> 3. Transferir montos entre diferentes cuentas y registrar estas `Transacciones`

## ![Libros de Cuentas](icon:///notebook-multiple) Libros de Cuentas

Se requiere al menos un Libro de Cuentas, con cuentas que tengan la misma unidad monetaria. También puedes crear múltiples Libros de Cuentas con la misma unidad monetaria según tus necesidades.

## ![Cuentas](icon:///bookmark-multiple) Cuentas

Hay cinco tipos diferentes de cuentas, que puedes agregar, editar o eliminar en la pantalla de gestión de cuentas.

> - `Ingreso`: Salario, etc.
> - `Gasto`: Comida, entretenimiento, etc.
> - `Activos`: Efectivo, banco, etc.
> - `Pasivos`: Tarjetas de crédito, préstamos, etc.
> - `Otros`: ...

* Los nombres de las cuentas pueden usar puntos (.) para separar (por ejemplo, Comida.Cena, Comida.Reunión), proporcionando una mejor visualización jerárquica al seleccionar cuentas o ver balances.
* Puedes ordenar las cuentas para priorizar las cuentas de uso más frecuente.

## ![Transacciones](icon:///receipt) Transacciones 

Cuando hay una transacción entre cuentas, como gastar, retirar, depositar o usar una tarjeta de crédito (por ejemplo, gastaste 320 yuanes en una comida), usa `Nueva Transacción` para crear una nueva transacción.
> - Selecciona `Fecha y Hora`: Fecha y hora de la transacción.
> - Selecciona `Cuenta de Transferencia Saliente`: Efectivo
> - Selecciona `Cuenta de Transferencia Entrante`: Cena
> - Ingresa `Monto`: 320
> - Ingresa `Nota`: Reunión con amigos
> - Haz clic en `Crear`

## Ejemplos

### Transferencia de Salario al Banco

> Cuenta de Transferencia Saliente `Ingreso`: Salario
> Cuenta de Transferencia Entrante `Activos`: Banco

### Retirar Efectivo del Banco

> Cuenta de Transferencia Saliente `Activos`: Banco
> Cuenta de Transferencia Entrante `Activos`: Efectivo

### Comprar un Teléfono con Tarjeta de Crédito

> Cuenta de Transferencia Saliente `Pasivos`: Tarjeta de Crédito
> Cuenta de Transferencia Entrante `Gasto`: Electrónicos

### Pagar Factura de Tarjeta de Crédito con el Banco

> Cuenta de Transferencia Saliente `Activos`: Banco 
> Cuenta de Transferencia Entrante `Pasivos`: Tarjeta de Crédito

## ![Balance General](icon:///scale-balance)![Gráfico de Balance](icon:///chart-pie) Balance General y Gráfico

A través de una contabilidad diligente, la aplicación te ayudará a registrar todos los detalles de las transacciones y generará un balance general según las condiciones de consulta. Este balance presenta claramente el balance de activos y pasivos en diferentes períodos, permitiéndote comprender mejor tu situación financiera. Además, la aplicación puede generar varios gráficos para representar visualmente tus ingresos y gastos, facilitando la comprensión de tu flujo financiero.

## Valores Iniciales de las Cuentas

Cuando usas la aplicación por primera vez, es posible que ya tengas algunas cuentas actuales con valores reales, como depósitos bancarios, efectivo disponible o deudas de tarjetas de crédito. Para asegurar que el balance general proporcione resultados de cálculo más precisos, puedes usar la función de inicializar cuentas para establecer los valores iniciales correctos de estas cuentas. De esta manera, puedes hacer que el balance general refleje la verdadera situación financiera.

## División Uno-a-Muchos

A veces, un solo gasto puede involucrar múltiples categorías de gasto. Por ejemplo, al hacer compras en un supermercado, puedes comprar alimentos, productos de uso diario y productos electrónicos al mismo tiempo. Para enfrentar esta situación, la aplicación proporciona edición avanzada de creación de transacciones, permitiendo que un solo gasto se asigne a múltiples categorías de gasto diferentes. En otras palabras, puedes asignar el monto de un solo gasto con tarjeta de crédito a múltiples categorías como alimentos, productos de uso diario y productos electrónicos. Por favor, ten en cuenta: En las transacciones dentro del mismo libro de cuentas, como las unidades monetarias son iguales, el monto total transferido debe ser igual al monto total recibido, de lo contrario, el programa rechazará la creación de tu transacción.

## Transferencia entre Libros de Cuentas

El programa te permite transferir entre cuentas en diferentes libros de cuentas. Ya sea en la edición o creación básica o avanzada de transacciones, puedes seleccionar cuentas de otros libros de cuentas al seleccionar cuentas. Dado que los valores monetarios entre diferentes libros de cuentas pueden diferir, y la tasa de cambio no es fija en el momento, como transferir de Dólares de Taiwán a Dólares Americanos, el programa no te limitará a crear una transacción donde el monto total transferido deba ser igual al monto total recibido. Por favor, crea transacciones basadas en los montos reales al crear y ten cuidado.

## Vista Rápida del Balance General y Gráficos

Al navegar por el balance general o los gráficos, puedes agregar elementos de cuenta específicos a la vista rápida en la pantalla de inicio [*1]. Simplemente desliza hacia la derecha en el elemento en el balance general y haz clic en `Agregar a Vista Rápida`, o haz clic en "Agregar a Vista Rápida Icono" en la esquina superior derecha de la tarjeta del gráfico de balance. Luego, en la pantalla de inicio, verás el balance de activos y pasivos de ese elemento, o puedes verlo en la página de gráficos de la pantalla de inicio. Además, puedes ordenar o eliminar estos elementos en `Preferencias > Configuración de la Pantalla de Inicio`.

[*1] Vistas rápidas excesivas en la pantalla de inicio pueden afectar el tiempo de carga de la pantalla de inicio.

## Plantillas de Transacciones y Programación Recurrente

Puede configurar plantillas de transacciones para acciones contables comunes, lo que le permite agregar transacciones rápidamente. También puede configurar plantillas de programación recurrente para acciones contables recurrentes. El programa le notificará cuando sea necesario, permitiéndole agregar rápidamente la transacción y programarla automáticamente para el próximo vencimiento. Simplemente deslice hacia la izquierda en el elemento en la lista de transacciones, luego toque `Crear Plantilla`, ingrese el tiempo de programación y créelo. Además, puede ordenar, editar o eliminar estos elementos en la página de `Gestión de Plantillas de Transacciones`.