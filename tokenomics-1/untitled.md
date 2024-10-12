# Cómo funciona Gyro

**Introducción**

El objetivo de Gyro es ofrecer una clase de token y activos que pueda formar parte de cualquier cartera. Se puede utilizar para cubrir activos de riesgo al tiempo que ofrece incentivos más seguros y mejores que las monedas estables.

**Cómo funciona Gyro:**

Cada token GYRO está respaldado por 1 USD (es decir, USDT, DAI, BUSD, USDC) en la tesorería.

Inicialmente, comenzaremos con USDT como nuestro activo de tesorería. Después del lanzamiento, agregaremos otras monedas estables para equilibrar nuestra tesorería. Esto incluirá DAI, BUSD, USDC, etc.

Los tokens no pueden ser acuñados ni quemados por nadie excepto por el protocolo..

El protocolo solo se acuña o quema en respuesta al precio.

GYRO no hace rebases. En cambio, se crea una nueva oferta a través de ventas directas en el mercado y se quema a través de compras directas en el mercado. De esta manera, GYRO permanece respaldado por activos reales en tesorería, es decir, USD.

Esto básicamente se traduce en:

Cuando GYRO cotiza por debajo de ↓ 1 USDT, el protocolo lo vuelve a comprar y quema GYRO.

Cuando GYRO cotiza por encima de ↑ 1 USDT, el protocolo acuña y vende un nuevo GYRO.

Esto se debe a que la tesorería debe tener 1 USDT y solo 1 USDT por cada GYRO cada vez que se compra o vende para que obtenga una ganancia. Eso significa que el protocolo obtiene más de 1 USDT por el lado de la venta o gasta menos de 1 USDT por el lado de la compra.

El hecho de que el protocolo contenga USDT para cada token nos permite decir con certeza que GYRO no cotizará por debajo de su valor intrínseco a largo plazo..

Las inversiones se pueden realizar con un riesgo definido porque 1 USDT es el precio mínimo garantizado a largo plazo. Y debido a esto, el protocolo puede comprar (y lo hará) indefinidamente por debajo de 1 USDT hasta que no queden vendedores, incluso si la oferta se reduce a 0. En este ejemplo, este evento recompensaría inmensamente a aquellos que no vendieron porque terminarían con un pedazo de cada ficha que se quemó.

Mantener monedas estables para respaldar tokens también crea una oportunidad de generación de rendimiento.

Guardar las monedas estables en una bóveda sería un desperdicio. Dado que el protocolo nunca necesita más que un pequeño porcentaje de reservas, incluso en el mayor de los días de inactividad, significa que puede utilizar el resto para conectarse a agregadores de rendimiento y agregar esos ingresos a las ganancias de la compra y venta de GYRO.

**Distribución inicial de beneficios de Gyro**

90% a los stakers.

10% al DAO (estas asignaciones se cambiarán, si es necesario, según lo decida el DAO).

Todas las recompensas se pagan en GYRO, respaldadas por monedas estables.

Este sistema mantiene un valor intrínseco estable y reduce el rol incentivador de la apreciación a favor de la acumulación. Al igual que con la moneda real, usted intenta acumular más dólares y no tiene que desearle a una estrella que sus dólares valgan más. Aunque ambos pueden suceder.

**Staking  y rebasing**

El protocolo distribuye tokens enviándolos al contrato de staking sin solicitar la devolución de sGYRO. Esto aumenta la proporción de GYRO stakeado respecto al sGYRO en circulación y da como resultado un rebase para corregir la diferencia.

Por ejemplo: hay 500k GYRO stakeados y 500k sGYRO pendientes. El protocolo produjo una ganancia de $ 5k por día, que utiliza para acuñar y respaldar 5k GYRO. Envía a esos GYRO al contrato de staking; ahora hay 505k GYRO apostados y 500k sGYRO pendientes. El suministro de sGYRO debe aumentar en 5k, o 1%, para volver al equilibrio. Entonces, sGYRO se refuerza en un 1%.

La única advertencia es que las rebases se producen de forma retroactiva. El final de la época 100 desencadena una rebase de las ganancias de la época 99. Este retraso le permite ver lo que se está perdiendo si quiere dejar de stakear o lo que obtendrá si quiere stakear.

Stakeando es cómo distribuimos las ganancias de manera equitativa entre los participantes. A través de sGYRO, todos reciben el mismo porcentaje de ganancia por época. Rebasar también nos permite aumentar el rendimiento sin necesidad de cosechar ni hacer nada más que holdear.

**Bonding**

El bonding es el proceso de negociar una acción LP con el protocolo de GYRO. El protocolo cita una cantidad de GYRO y un período de adquisición de derechos para el trading. **Es importante saber: cuando crea su bond, está renunciando a su participación de LP. El protocolo lo compensa con más GYRO** de lo que obtendría en el mercado, pero su exposición se convierte completamente en GYRO y ya no en GYRO-USDT LP.

_Tenga en cuenta que sGYRO es el token de acumulación de ganancias del protocolo y, dado que los bonders ganan GYRO (no sGYRO), los stakers obtienen el 100% de las ganancias del protocolo (menos el corte que va hacia el DAO)._

**¿Por qué es interesante el bonding?**

Porque le permite comprar GYRO a un costo menor. A cambio de vender su LP, el protocolo le venderá GYRO con un descuento.

**Dinámica de un bond**

El protocolo cotiza los precios de los bonds en función del valor libre de riesgo (RFV) del protocolo. El "Bond Premium" es una herramienta de políticas regida por un protocolo que controla la prima que se cobra por los bonds. Una prima más baja significa un descuento más alto y un incentivo más alto para el bond.

_Execution price = RFV / Premium {Premium ≥ 1}_

La prima está determinada por la deuda total del sistema y una variable de escala. Esto vincula el precio de los bonds al número de bonos en circulación; cuantos menos bonos en circulación, menor será la prima y mayor el descuento.

Premium = 1 + (Debt Ratio \* BCV)\
Debt Ratio = Bonds Outstanding / GYRO Supply

El valor libre de riesgo de la acción LP para el protocolo es el punto en el que se equilibra el pool (1 GYRO = 1 USDT). Dado que el protocolo debe proteger el respaldo de GYRO, este es el precio más bajo que puede aceptar; En el peor de los casos, puede respaldar cada 2 GYRO unidos por 1 USDT y 1 GYRO. Por encima de este equilibrio, hay un exceso de USDT. Por debajo de este equilibrio, hay un exceso de GYRO. Ambos pueden ser usar, y siempre habrá suficiente de ambos.

_Risk-Free Value = (LP / Total LP) \* 2sqrt(Constant Product)_

Esto significa que un bonder está (generalmente) vendiendo su LP por debajo del valor de mercado. Sin embargo, esto es cancelado por el protocolo que une a GYRO por debajo del valor de mercado.

**Escala lineal**

Ésta es una dinámica extremadamente favorable; cuanto más alto es el precio (y más vende el protocolo en respuesta), más liquidez debería haber.

Los bonders pueden realizar este intercambio, a pesar del riesgo de tiempo, porque su punto de equilibrio se ha reducido. Cuanto más alto sea el precio, mayor será el disponibilidad.

**Conclusión**

El objetivo de Gyro es ofrecer un tipo de activo/token que puede formar parte de cualquier cartera. Se puede utilizar para cubrir activos de riesgo al tiempo que ofrece incentivos más seguros y mejores que las monedas estables.
