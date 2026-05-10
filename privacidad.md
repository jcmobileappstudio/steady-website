---
title: Política de Privacidad
description: Cómo Steady maneja tus datos, en lenguaje claro.
permalink: /privacidad/
---

# Política de Privacidad

**Última actualización: 10 de mayo de 2026**

Steady es una aplicación de seguimiento del sueño para trabajadores por turnos, desarrollada y operada por **JC Mobile App Studio LLC** ("nosotros"). Esta política explica qué datos recopila Steady, cuáles no recopila, y las opciones que tienes.

En español sencillo: Steady es una app local-first. Tus datos de sueño, horario, e información personal se quedan en tu iPhone (y en tu Apple Watch e iCloud, si tienes la sincronización de iCloud activada en los Ajustes de iOS). No operamos ningún servidor. No vemos tus datos. No vendemos, compartimos, ni analizamos tus datos.

Si eso era todo lo que necesitabas saber, puedes detenerte aquí. El resto de la página cubre detalles, casos especiales, y tus derechos bajo las leyes de privacidad.

---

## 1. Qué datos almacena Steady en tu dispositivo

Steady almacena lo siguiente en tu iPhone, solo en tu dispositivo:

- **Sesiones de sueño**: hora de acostarte, hora de despertar, duración del sueño, calificación de calidad opcional, notas opcionales, fuente (entrada manual o Apple HealthKit), indicador de siesta.
- **Patrón de turno**: el patrón de trabajo que escogiste o construiste durante el onboarding (DuPont, 4-en-4-fuera, personalizado, etc.) incluyendo hora de inicio, fecha ancla, y duración del turno.
- **Cambios de calendario**: cualquier excepción por día que hayas hecho a tu horario por defecto (vacaciones, intercambio, PTO, etc.).
- **Registro de cafeína**: cantidad en miligramos y hora de cada entrada que registres.
- **Historial de Smart Wake**: la configuración de la ventana de despertar y la puntuación de alerta derivada del movimiento de cada sesión.
- **Puntuaciones de fatiga calculadas**: derivadas de tus datos de sueño + turno.
- **Configuraciones y preferencias**: alternancias de notificaciones, objetivo de sueño, preferencias de recordatorios de luz, idioma, tema.
- **Estado de suscripción**: si tu compra dentro de la app está activa o en periodo de prueba. Apple maneja el cobro real.

Steady no recopila ni almacena nada de lo siguiente: tu nombre, correo, teléfono, fotos, ubicación, contactos, eventos del calendario fuera de la app, audio del micrófono, cámara, identificadores biométricos, identificador de publicidad, ni ninguna huella del dispositivo.

## 2. Apple HealthKit

Si le das permiso a Steady para leer datos de sueño de Apple HealthKit, la app importa tus sesiones de sueño desde HealthKit al almacenamiento local de Steady para que las veas junto con las sesiones registradas manualmente.

Nunca escribimos datos de regreso a HealthKit. Solo leemos.

Puedes revocar el acceso a HealthKit en cualquier momento en Ajustes de iOS > Privacidad y seguridad > Salud > Steady. Si lo haces, Steady deja de sincronizar nuevos datos de inmediato. Las sesiones que Steady ya importó se quedan en la base de datos local de Steady hasta que las elimines.

No transmitimos datos de HealthKit a ningún lado. El framework de HealthKit de Apple nos lo impide aunque quisiéramos. Los datos de HealthKit se quedan dentro de los límites de tu dispositivo, tu Apple ID, y los servicios cifrados de Apple.

## 3. Apple Watch (opcional)

Si tienes Apple Watch y la app Steady Watch instalada, Steady sincroniza una pequeña foto de tus datos actuales al reloj (puntuación de fatiga, próximo turno, último sueño, total de cafeína de hoy). Esta sincronización usa el framework WatchConnectivity de Apple y se queda dentro del canal cifrado dispositivo-a-dispositivo de Apple. Nunca vemos esos datos.

Si registras una siesta rápida desde el reloj, el reloj manda un mensaje de regreso al iPhone usando el mismo framework, el iPhone registra la siesta en tu base de datos local. Lo mismo aplica para cualquier complicación que pongas en la carátula del reloj.

## 4. iCloud (opcional)

Steady no usa un contenedor de iCloud personalizado. Si tienes Backup de iCloud activado en Ajustes de iOS, tu iPhone puede incluir los datos de Steady en tu Backup de iCloud cifrado, este es comportamiento de Apple, no nuestro. Apple controla y cifra ese backup.

## 5. Notificaciones

Steady envía notificaciones locales para recordatorios de siesta, recordatorios de hora de dormir, recordatorios de exposición a la luz, y alertas de riesgo al manejar a casa. Estas las programa tu iPhone usando el framework estándar UserNotifications de iOS. No salen de tu dispositivo. No recibimos ninguna señal cuando una notificación aparece o cuando interactúas con ella.

Puedes desactivar notificaciones globalmente en Ajustes de iOS > Notificaciones > Steady, o por categoría dentro de los Ajustes de Steady.

## 6. Compras dentro de la app (suscripción)

Steady ofrece una suscripción Pro opcional procesada completamente por StoreKit de Apple. Cuando compras una suscripción:

- Apple procesa el pago usando tu Apple ID.
- Apple, no Steady, tiene acceso a tu información de pago (tarjeta de crédito, dirección de facturación, etc.).
- Steady recibe un token de derecho verificado de Apple confirmando que tu suscripción está activa. Este token no incluye información de pago personal.
- Usamos el token solo para desbloquear funciones Pro dentro de la app en tu dispositivo.

La política de privacidad de Apple aplica a la parte de pago de esta transacción: [https://www.apple.com/legal/privacy/](https://www.apple.com/legal/privacy/)

No operamos un servidor de suscripciones. No tenemos una base de datos de quién está suscrito.

## 7. Análisis, rastreo, y SDKs de terceros

Steady no contiene ningún SDK de análisis, ningún SDK de reporte de fallas, ningún SDK de publicidad, ningún SDK de marketing, ni ningún otro kit de desarrollo de terceros que recopile o transmita datos. La app está construida solo con frameworks de Apple (SwiftUI, SwiftData, HealthKit, StoreKit, WatchConnectivity, UserNotifications, WidgetKit, ActivityKit).

No usamos Facebook Pixel, Google Analytics, Firebase, Mixpanel, Amplitude, AppsFlyer, Adjust, Branch, ni ninguna herramienta similar.

No te rastreamos a través de otras apps o sitios web. No usamos el Identificador para Anunciantes (IDFA). Steady no presenta el aviso de App Tracking Transparency porque no hay nada que rastrear.

## 8. Exportar tus datos

Puedes exportar todos tus datos de Steady en cualquier momento desde Ajustes > Exportar tus datos. La exportación es un archivo CSV que puedes guardar, enviar por correo, o compartir con cualquier app de iOS. La exportación contiene tus sesiones de sueño y el historial de cambios de turno. Se genera en tu dispositivo, nosotros no la vemos.

## 9. Eliminar tus datos

Para eliminar todos tus datos de Steady, tienes dos opciones:

1. **Borrar la app Steady de tu iPhone.** Esto elimina todos los datos locales de Steady de inmediato. (Los datos de HealthKit, que viven en la app Salud de Apple, no se ven afectados.)
2. **Reiniciar dentro de la app** vía la pantalla de recuperación si encuentras un error de base de datos, esto borra el almacén local SwiftData de Steady.

Como Steady no tiene servidor, no hay una cuenta separada o base de datos en la nube que eliminar. Borrar la app borra los datos.

## 10. Tus derechos bajo GDPR, CCPA, y otras leyes de privacidad

Aunque Steady no recopila información personal identificable que normalmente activaría estas leyes, queremos que sepas los derechos que tienes:

- **Derecho a saber qué recopilamos**: toda esta política.
- **Derecho a acceder a tus datos**: usa Ajustes > Exportar tus datos.
- **Derecho a eliminar tus datos**: borra la app.
- **Derecho a portabilidad**: la exportación CSV es portable a cualquier otra herramienta.
- **Derecho a no discriminación**: no condicionamos el acceso a la app a compartir datos porque no hay nada que compartir.
- **Derecho a optar por no vender información personal**: no vendemos ningún dato, nunca.

Si eres residente de la Unión Europea, Reino Unido, California, Colorado, Virginia, Connecticut, Utah, o cualquier otra jurisdicción con leyes de privacidad, los derechos arriba aplican para ti sin importar la jurisdicción.

## 11. Niños

Steady no está dirigido a niños menores de 13 años (o menores de 16 en jurisdicciones donde esa es la edad aplicable de consentimiento digital). No recopilamos a sabiendas datos de niños. Si un padre o tutor descubre que un niño ha estado usando Steady, simplemente puede borrar la app para eliminar todos los datos asociados.

## 12. Seguridad

Como todos los datos de Steady viven en tu iPhone, la seguridad de esos datos depende de la seguridad de tu iPhone. Recomendamos fuertemente:

- Usa un código de acceso (o Face ID / Touch ID) en tu iPhone.
- Activa Buscar mi iPhone.
- Mantén iOS actualizado.

Para los datos que pasan brevemente entre tu iPhone y Apple Watch vía WatchConnectivity, ese canal está cifrado por Apple de extremo a extremo. No tenemos acceso a él.

## 13. Cambios a esta política

Podemos actualizar esta política de privacidad cuando la app cambie o cuando las leyes cambien. La fecha de "Última actualización" en la parte superior refleja el cambio más reciente. Para cambios materiales, mostraremos un aviso dentro de la app Steady en el siguiente lanzamiento.

## 14. Contacto

Si tienes preguntas sobre esta política de privacidad, quieres ejercer cualquiera de los derechos arriba, o crees que Steady ha manejado tus datos de forma inadecuada, contáctanos:

- Correo: **jcmappstudio@gmail.com**
- Dirección postal disponible bajo solicitud: escríbenos al correo anterior y la proporcionaremos.

Responderemos a solicitudes verificables dentro de 30 días.

---

*Steady es operada por JC Mobile App Studio LLC. Esta política se rige por las leyes de los Estados Unidos y el estado donde JC Mobile App Studio LLC está registrada. Escrita para humanos primero.*
