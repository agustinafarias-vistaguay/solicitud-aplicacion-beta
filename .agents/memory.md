# Protocolo de Memoria - Antigravity

## Estado Deseado
Actualizar las opciones de cultivo para incluir "Barbecho" en todos los selectores relevantes.

## Registro de Procesos
- [x] Análisis: Se determinó que el "type switching" causaba fricción (doble clic) en móviles, afectando la experiencia de usuario.
- [x] Ejecución: Se revirtió el input `fecha-aplicacion` a su estado original (`type="date"`) con un solo evento `onclick="this.showPicker()"`.
- [x] Verificación: Se priorizó la interactividad fluida sobre la presencia del placeholder visual.

## Diff Log
- **Anterior:** Intento de implementar placeholder dinámico que introdujo el problema del doble clic.
- **Real:** Regreso al estado funcional estable con un solo clic para abrir el calendario.

## Próximos Pasos
- Ninguno pendiente para esta tarea.
