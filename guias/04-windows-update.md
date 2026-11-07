# Windows Update falla

## Síntomas

- Una descarga o instalación falla, o el mismo paquete vuelve a ofrecerse después de reiniciar.

## Causas posibles

Reinicio pendiente, espacio insuficiente, conexión inestable, problema de los componentes de actualización o política de un equipo administrado.

## Solución paso a paso

1. Abre **Configuración → Windows Update → Historial de actualizaciones**. Anota el código de error, el identificador KB si aparece y si falló al descargar o al instalar.
2. Comprueba la conexión y el espacio libre de la unidad del sistema. Si Windows solicita liberar espacio, usa la [guía de almacenamiento](09-espacio-en-disco.md).
3. Si Windows pide reiniciar, guarda el trabajo y coordina el reinicio. Deja el portátil conectado a la corriente durante la instalación.
4. Abre **Obtener ayuda** y ejecuta el solucionador de **Windows Update**. También puedes buscar **Otros solucionadores de problemas** en Configuración.
5. Vuelve a **Windows Update**, selecciona **Buscar actualizaciones** y reintenta. En equipos administrados, conserva los ajustes de la organización.

## Verificación

Busca el paquete en el historial y comprueba que figure como instalado. Si el sistema solicita otro reinicio, completa ese paso y revisa el estado de nuevo.

## Escalar si

Se repite el mismo error, aparece un mensaje de política o el PC entra en un ciclo de reinicios. Entrega código, KB, versión de Windows y pasos probados.

[Microsoft · Solucionador de problemas de Windows Update](https://support.microsoft.com/es-es/windows/experience/windows-update-troubleshooter)
