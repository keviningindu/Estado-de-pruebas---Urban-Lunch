# Estado-de-pruebas---Urban-Lunch
Se valida la aplicación Movil Urban Lunch en fase de prueba en busca de errores antes de su liberacion.

## ✅ Resumen General
- **Total de casos probados:** 30  
- **Casos PASSED:** 24  
- **Casos FAILED:** 6  
- **Cobertura funcional:** ~80% de los flujos principales operan correctamente.  

## 🚨 Casos con Fallos
| ID | Descripción | Estado | Severidad | Enlace al bug |
|----|-------------|--------|-----------|---------------|
| 1  | El mapa muestra puntos de recogida y ubicación del usuario | FAILED | Baja | [ULAS-4](https://kibagud.atlassian.net/browse/ULAS-4) |
| 13 | Diseño en pantalla de detalles del platillo | FAILED | Media | [ULAS-5](https://kibagud.atlassian.net/browse/ULAS-5) |
| 15 | Botón "+" en detalles del platillo no agrega | FAILED | Baja | [ULAS-6](https://kibagud.atlassian.net/browse/ULAS-6) |
| 24 | Mapa en pantalla "El pedido ha sido enviado" | FAILED | Media | [ULAS-7](https://kibagud.atlassian.net/browse/ULAS-7) |
| 25 | Notificación en "El pedido ha sido enviado" no cumple requisitos | FAILED | Muy baja | [ULAS-8](https://kibagud.atlassian.net/browse/ULAS-8) |

## 🔎 Observaciones
- Los flujos principales de **selección de punto de recogida, pedido, confirmación y feedback** funcionan correctamente.  
- Los fallos afectan principalmente:
  - **Mapa y ubicación del usuario.**
  - **Pantalla de detalles del platillo.**
  - **Pantalla de confirmación de pedido enviado.**
- Se detectaron inconsistencias menores en textos (“Pedir” vs “Order”) y mensajes de botones inactivos.

## 📌 Conclusión
El producto está **funcional en un 80%**, con los procesos clave de pedido y confirmación operando correctamente.  
Los fallos identificados deben ser corregidos antes de considerar el producto listo para producción, ya que impactan en la **usabilidad** y la **experiencia del usuario**.
