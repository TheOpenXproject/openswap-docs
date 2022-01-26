---
description: Introducción a OpenX, detalles de migración y guía
---

# Migración de OpenSwap V2

#### Llegó OpenSwap V2: introducción a OpenX, detalles de migración y guía

Estamos más que emocionados de anunciar la llegada de OpenSwap V2. Como recordará, a fines de septiembre, OpenSwap realizó una auditoría que detectó un problema de seguridad menor. La base de la preocupación recayó únicamente en confiar en el desarrollador del proyecto. El equipo de OpenSwap quiso despejar cualquier duda de este proyecto e inmediatamente comenzó a trabajar en V2. Es hora oficial de olvidar la V1 y pasar a un nuevo futuro. OpenSwap V2 trae un nuevo nombre de token, una nueva auditoría y más.

![](https://cdn-images-1.medium.com/max/716/1\*mkQmszJITvIE-gi7N74nuQ.png)

**Token Cambio de Nombre**\
Con V2, el token de OpenSwap ahora se denominará OpenX. La dirección OpenX es 0x01A4b054110d57069c1658AFBC46730529A3E326. El intercambio de tokens entre oSwap y OpenX será 1:1 y se procesará a través de un migrador en el sitio de OpenSwap. La tokenómica del token oSwap original permanecerá intacta para OpenX. Los antiguos tokens oSwap se retirarán durante el proceso de migración.

**Auditoría V2 completada, 100% a prueba de robos**

Se completó una auditoría en V2. Hay 0 defectos altos y 0 medios con los contratos inteligentes V2. Lo que es más importante, la auditoría confirma que OpenSwap es 100 % a prueba de **robos**. La auditoría fue completada por 0xGuard; El informe se puede ver [aquí](https://github.com/0xGuard-com/audit-reports/blob/master/openswap\_v2/OpenSwapV2\_final-audit-report.pdf).

![](https://cdn-images-1.medium.com/max/716/1\*v\_R3ZmkHUT0wTIFHqdHLyA.png)

**Guías de usuario para migrar V1 a V2**\
****Para ayudarlo en el proceso de migración, creamos dos guías diferentes: una para aquellos con oSwap actualmente en su billetera y otra para aquellos con oSwap en LP depositados.

**Migrar oSwap que está actualmente en su billetera**

**PASO 1:**  Ir a [https://app.openswap.one](https://app.openswap.one)\
**PASO 2:** Haga clic en 'Más' en el menú superior\
**PASO 3:** Haga clic en 'Migrar'\
**PASO 4:** Ingrese la cantidad de oSwap para migrar. Sugerimos usar el botón 'máximo' para esta función.\
**PASO 5:** Haga clic en 'Aprobar'.\
**PASO 6:** Su billetera le pedirá que apruebe OpenSwap para realizar una transacción con este token, apruébelo. \
**PASO 7:** Haga clic en 'Migrar'\
**PASO 8:** Su billetera le pedirá que confirme la transacción, apruébela. Habrá dos notificaciones cuando envíe una transacción: transacción enviada y transacción exitosa.\
**PASO 9:** Agregue el token OpenX para que sea visible en su billetera (ver más abajo).

_**Migrar oSwap en staking único o LP**_

Si tiene oSwap en LP de participación única o participación doble, siga estos pasos para la migración.

**PASO 1:** Ir a [https://app.v1.openswap.one](https://app.v1.openswap.one)\
**PASO 2:** Haga clic en 'Farms' en el menú\
**PASO 3:** Haga clic en los detalles del LP\
**PASO 4:** Haga clic en 'Unstake' los LP\
**PASO 5:** Haga clic en 'Max' y luego haga clic en 'Unstake'\
**PASO 6:** Confirme en su billetera.\
**PASO 7:** Haga clic en 'Liquidez' en el menú superior\
**PASO 8:** Selecciona las dos tokens del LP\
**PASO 9:** Haga clic en Siguiente'\
**PASO 10:** Haga clic en 'Remover liquidez'\
**PASO 11:** Haga clic en 'Máx.’\
**PASO 12:** Haga clic en 'Aprobar' y confirme en su billetera\
**PASO 13:** Haga clic en 'Remover' y confirme en su billetera

_**!! Paso Importante!!**_\
_****_**PASO 14:** Ir a [https://app.openswap.one](https://app.openswap.one)\
**PASO 15:** Haga clic en 'Más' en el menú superior\
**PASO 16:** Haga clic en 'Migrar'\
**PASO 17:** Ingrese la cantidad de oSwap para migrar. Sugerimos usar el botón 'máximo' para esta función.\
**PASO 18:** Haga clic en 'Aprobar'.\
**PASO 19:** Su billetera le pedirá que apruebe OpenSwap para realizar una transacción con este token, apruébelo.\
**PASO 20:** Haga clic en 'Migrar'\
**PASO 21:** Su billetera le pedirá que confirme la transacción, apruébela. Habrá dos notificaciones cuando envíe una transacción: transacción enviada y transacción exitosa.\
**PASO 22:** Agregue el token OpenX para que sea visible en su billetera (ver más abajo).\
**PASO 23:** En este momento, puede recrear LP y depositar.

_**Agregar OpenX a su billetera:**_

_**Para una billetera Metamask:**_

**PASO 1:** Ingrese a su billetera Metamask y desplácese hasta la parte inferior de la ventana emergente.\
**PASO 2:** Haga clic en 'Importar tokens'.\
**PASO 3:** En la 'Dirección del contrato de token' ingrese la dirección OpenX 0x01A4b054110d57069c1658AFBC46730529A3E326.\
**PASO 4:** Haga clic en el botón 'Agregar token personalizado'.

_**Para una billetera Harmony:**_

\
**PASO 1:** Ingrese su billetera Harmony, haga clic en 'HRC20'.\
**PASO 2:** Haga clic en el signo más en la parte inferior de la ventana emergente.\
**PASO 3:** En la 'Dirección del contrato de token' ingrese la dirección OpenX _****_** one1qxjtq4q3p4tsd8qktzhmc3nnq5568cexh9c90j** . \
**PASO 4:** Haga clic en Agregar.

\
**Mejoras de V2**

**Plataforma de Votación de Gobernanza (por determinar)**

Los planes para crear una plataforma donde se llevará a cabo la votación de OpenSwap están en proceso. Esto permite que la comunidad vote sobre temas y orientación para el proyecto OpenSwap.

**Auto staking para la pool individual de OpenX (por determinar)**\
V2 permitirá que la pool individual de OpenX tenga auto staking automático. El marco de tiempo con respecto al lanzamiento de esta función aún no se ha determinado.

**Integraciones (por determinar)**

Con el lanzamiento de V2, habrá un esfuerzo coordinado para integrarse con sitios web de seguimiento como CoinMarketCap, Coin gecko, Defi Lama, etc. Si bien no hay promesas de una lista con estos sitios, se hará todo lo posible para completarlos.



**Contratos V2**:

UniswapV2Factory = 0x5d2F9817303b940C9bB4F47C8C566c5C034d9848

UniswapV2Router02 = 0x2F99992024DCC51324BA4956bB1c510F36FA54F5

Init code hash for UniswapV2Pair is: 0x613b6eaa34b43dcb7eb8881dd4b5af85805be104d5f2f385304ffa8bda5e219c

OpenSwapToken = 0x01A4b054110d57069c1658AFBC46730529A3E326

OPENxMaker = 0xff819FcdACf0bb69Cf4621340F85D7f20744d450

MasterChef = 0xb2E9B85FB43082F3148B0D13450E8BEB5C9B63f2

OpenBridge = 0x1A47E63DE006aa7aaFa5aB4DdFBfB6Ae0F8eD010
