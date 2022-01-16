---
description: Auditorías realizadas sobre los contratos inteligentes para OpenSwap
---

# Auditorias

La seguridad es de suma importancia para OpenSwap y siempre será un factor determinante para nuestro desarrollo futuro. Revise las auditorías que se han realizado en los contratos inteligentes de OpenSwap.

### Auditoría V2

**Hecha por:** 0xGuard

**Fecha:** Octubre 2021

**Reporte de auditoría:** [https://github.com/0xGuard-com/audit-reports/blob/master/openswap\_v2/OpenSwapV2\_final-audit-report.pdf](https://github.com/0xGuard-com/audit-reports/blob/master/openswap\_v2/OpenSwapV2\_final-audit-report.pdf)

**Resumen**: Se completó una auditoría en V2 en octubre de 2021. Hay 0 defectos altos y 0 defectos medios con los contratos inteligentes V2. Todas las preocupaciones de V1 fueron eliminadas en esta auditoría. Lo que es más importante, la auditoría confirma que OpenSwap es 100 % a prueba de robos.&#x20;

Mientras lee la auditoría, preste atención al área de actualización para cualquiera de los problemas enumerados. &#x20;

### Auditoría V1

**Hecha por:** 0xGuard

**Fecha:** Septiembre 2021

**Reporte de auditoría:** [https://github.com/0xGuard-com/audit-reports/blob/master/openswap/OpenSwap\_final-audit-report\_v1.pdf](https://github.com/0xGuard-com/audit-reports/blob/master/openswap/OpenSwap\_final-audit-report\_v1.pdf)

**Resumen**: Comentarios de Alex con respecto a la Auditoría V1: “En general, estoy muy contento con la auditoría. Lo más importante, su dinero está seguro; nadie puede robarte tu dinero. Sin embargo, hay algunas cosas con las que debo tener mucho cuidado al mantener el protocolo para evitar errores en la emisión. Esta no es una responsabilidad que tomo a la ligera”. Expuso los errores de emisión al afirmar: “Algunos tokens ejecutan quemaduras por transferencia, lo que provoca un desbordamiento o subdesbordamiento que emitiría enormes cantidades de tokens en su lugar. Debemos tener mucho cuidado con cada token no nativo uni-LP o simple erc20. Cada token agregado a OpenSwap debe ser revisado. Consume mucho tiempo, pero vale la pena por la seguridad que brinda”.&#x20;

Los elementos destacados en la auditoría como riesgo están directamente relacionados con la confianza en el propietario del proyecto. Estas son las vulnerabilidades actuales que existen en Sushi hasta el día de hoy. Sin embargo, para Alex y su visión a largo plazo de OpenSwap; esto simplemente no encajaba. Si bien tiene la confianza de los miembros de la comunidad, el objetivo es eliminar cualquier duda. Su declaración exacta sobre el tema fue "No quiero que nadie tenga que confiar en que el propietario no usará el exploit". . Se creará V2 para eliminar los riesgos mencionados en esta auditoría.
