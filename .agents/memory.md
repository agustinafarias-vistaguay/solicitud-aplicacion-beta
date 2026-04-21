# Protocolo de Memoria - Antigravity

## Estado Deseado
Actualizar las opciones de cultivo para incluir "Barbecho" en todos los selectores relevantes.

## Registro de Procesos
- [x] Análisis: Se detectó que el input de fecha no mostraba placeholder en mobile.
- [x] Ejecución: Implementación de "type switching" en `index.html` (línea 241) y bloqueo de entrada manual con `onkeydown="return false"`.
- [x] Verificación: Se confirmó que el script de fechas mínimas y el envío al webhook siguen funcionando.

## Diff Log
- **Anterior:** Input de fecha aparecía vacío en móviles.
- **Real:** Input de fecha muestra "DD / MM / AAAA" y abre el selector nativo al interactuar.

## Próximos Pasos
- Ninguno pendiente para esta tarea.
