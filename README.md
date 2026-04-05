# claudeproject

# Demo de Calidad y Gobierno del Dato  
## Sindicato de Comptes de la Comunitat Valenciana

## Objetivo
Demostrar capacidades de Calidad y Gobierno del Dato mediante una solución basada en Qlik, aplicada a datasets financieros y operacionales.

## Alcance de la Demo

La demo se centra en los siguientes dominios de datos:

- Ventas (Pedidos)
- Clientes
- Productos
- Empleados
- Proveedores
- Categorías

## Reglas de Calidad del Dato

Ejemplos implementados:

- DIAS_PAGO <= 30
- ESTADO_PAGO en {Pagado, Pendiente, Bloqueado}
- Si ESTADO_PAGO = Pagado, IMPORTE_PAGADO es obligatorio
- Validación de MEDIO_PAGO

Se han simulado porcentajes de ruptura para analizar impacto en KPIs.

## Arquitectura

- Origen de datos: MySQL
- Captura de cambios: CDC basado en logs
- Transformación: Qlik
- Visualización: Qlik dashboards

## KPIs de Calidad

- Porcentaje de registros válidos
- Porcentaje de registros con errores
- Score de calidad por dataset
- Evolución de la calidad en el tiempo

## Casos de Uso

- Auditoría de datos financieros
- Control de pagos y cumplimiento
- Gobierno del dato
- Soporte a reporting del área financiera

## Valor para la Organización

- Mejora de la confianza en los datos
- Reducción de errores operativos
- Trazabilidad y control
- Base para decisiones estratégicas

## Tecnologías

- Qlik
- MySQL
- SQL

## Autor

Demo realizada por [Tu nombre o equipo]
