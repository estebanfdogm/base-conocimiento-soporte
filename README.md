# Base de conocimiento de soporte técnico N1

Diez guías para diagnosticar incidencias comunes de Windows 11, Android y acceso remoto con AnyDesk. Cada guía reúne síntomas, causas posibles, pasos de diagnóstico, una comprobación final y criterios de escalamiento.

Material de práctica para portafolio, redactado con asistencia de IA y a partir de documentación oficial. Los escenarios son genéricos. Las comprobaciones describen cómo verificar cada solución en el equipo atendido.

## Guías

| Incidencia | Qué revisar primero |
|---|---|
| [PC lento](guias/01-pc-lento.md) | Alcance del problema y uso de recursos |
| [Wi-Fi sin conexión o sin Internet](guias/02-wifi.md) | Estado de la red y prueba desde otro dispositivo |
| [Impresora sin conexión o con cola atascada](guias/03-impresora.md) | Conexión, impresora seleccionada y cola |
| [Windows Update falla](guias/04-windows-update.md) | Código de error, reinicio pendiente y espacio |
| [AnyDesk no conecta o no permite controlar](guias/05-anydesk.md) | Disponibilidad, solicitud y permisos de sesión |
| [Windows sin audio](guias/06-audio.md) | Dispositivo de salida y volumen de la app |
| [Dispositivo USB no reconocido](guias/07-usb.md) | Puerto, cable y Administrador de dispositivos |
| [Una app de Android se cierra o no abre](guias/08-app-android.md) | Alcance, actualizaciones y caché |
| [Unidad del sistema sin espacio](guias/09-espacio-en-disco.md) | Espacio disponible y categorías de almacenamiento |
| [Monitor externo sin imagen](guias/10-monitor-externo.md) | Entrada de video, cable y modo de proyección |

## Cómo usar la base

1. Identifica si falla una app, un dispositivo o varios equipos. Anota qué cambió antes de la falla.
2. Empieza por comprobaciones reversibles. Guarda el trabajo antes de reiniciar y coordina cualquier cambio que pueda cortar una sesión remota.
3. Cambia una cosa a la vez y repite la acción que fallaba. Si funciona, documenta qué paso la recuperó.
4. Si debes escalar, registra sistema y versión, síntoma, código de error, pruebas y resultados. Omite datos de contacto, credenciales e identificadores privados.

**Ejemplo simulado de nota de cierre**

> Windows 11. El audio funcionaba en el sistema, pero no en una aplicación de videollamadas. Cambié la salida de audio dentro de esa aplicación. Confirmé la corrección con su prueba de altavoces.

Las rutas pueden variar por versión de Windows, idioma, fabricante de Android o políticas del equipo.
