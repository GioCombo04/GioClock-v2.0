Cambios realizados GioClock-v3.0:

1- Verificación individual de canales: • Ahora, el script verifica si cada canal está configurado y existe antes de intentar actualizarlo. • Si un canal no está configurado o no existe, simplemente se omite y el script continúa funcionando con los canales disponibles.

2- Eliminación de bloqueo: • Se eliminó la lógica que deshabilitaba el script si algún canal no existía. En su lugar, el script simplemente omite los canales faltantes.

3- Actualización condicional: • Cada canal se actualiza solo si está configurado y existe.
