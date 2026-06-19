# User stories — CitaSalud

> Historias INVEST derivadas de `requisitos.md`, priorizando el núcleo de
> valor: el registro centralizado de paciente (sesiones, informes, pagos)
> que reemplaza el trabajo manual disperso reportado por las tres personas
> primarias. R-08 (visibilidad financiera avanzada) queda fuera de esta
> primera tanda — ver `mvp-canvas.md`, sección "Fuera de alcance".

- **[US-01]** Como psicóloga clínica, quiero centralizar las notas e
  informes de cada paciente en un solo lugar, para no perder información ni
  tener que buscarla en carpetas distintas del escritorio o el teléfono.
  - Criterios de aceptación:
    - Dado que registro una nota o informe de una sesión, cuando lo
      guardo, entonces queda asociado a ese paciente y disponible para
      consultarlo después sin buscar en otro lugar.
  - Fuente: doctora.md (R-01, R-02)

- **[US-02]** Como psicóloga clínica, quiero ver cuántas sesiones acordé
  con un paciente y cuántas lleva realizadas, para saber si cumple el plan
  sin tener que contar manualmente.
  - Criterios de aceptación:
    - Dado un paciente con un plan acordado (p. ej. "3 horas semanales
      durante 6 meses"), cuando consulto su ficha, entonces veo sesiones
      acordadas vs. realizadas.
  - Fuente: doctora.md, gestor_administrativo.md (R-03)

- **[US-03]** Como recepcionista, quiero gestionar la agenda de citas
  evitando choques de horario y notificando cambios automáticamente, para
  no tener que reacomodar todo a mano cada vez que algo cambia.
  - Criterios de aceptación:
    - Dado un cambio de horario de una cita, cuando lo registro, entonces
      el sistema detecta si choca con otra cita del mismo paciente o
      profesional y me avisa antes de confirmarlo.
    - Dado que confirmo el cambio, cuando se guarda, entonces el paciente
      recibe la notificación sin que yo tenga que escribirla a mano.
  - Fuente: recepcionista.md (R-04, R-05)

- **[US-04]** Como recepcionista, quiero ver el estado de envío de un
  informe (enviado / pendiente), para responder a un paciente sin tener que
  buscar en mails viejos ni preguntarle a la psicóloga.
  - Criterios de aceptación:
    - Dado un informe marcado como enviado, cuando un paciente pregunta si
      le llegó, entonces puedo confirmar su estado de envío sin abrir su
      contenido.
  - Fuente: recepcionista.md (R-06)

- **[US-05]** Como psicóloga clínica, quiero que la recepcionista pueda
  gestionar el envío de informes sin poder ver su contenido, para proteger
  la confidencialidad del diagnóstico de cada paciente.
  - Criterios de aceptación:
    - Dado un informe cargado por la psicóloga, cuando la recepcionista
      accede a la ficha del paciente, entonces solo ve que el informe
      existe y su estado de envío, nunca su contenido.
  - Fuente: doctora.md, recepcionista.md (R-11, R-12)

- **[US-06]** Como gestor administrativo, quiero registrar el estado de
  pago de cada paciente (por sesión, paquete o cuotas) en un solo lugar,
  para dejar de depender de un Excel que se actualiza a medias.
  - Criterios de aceptación:
    - Dado un pago registrado para un paciente, cuando consulto su ficha,
      entonces veo su estado de pago actualizado sin tener que cruzar
      datos con la recepcionista.
  - Fuente: gestor_administrativo.md (R-07)

- **[US-07]** Como gestor administrativo, quiero que el sistema envíe
  recordatorios automáticos de pago cuando se acerca o vence una fecha,
  para no depender de un reporte mensual y de que la recepcionista llame
  uno por uno con retraso.
  - Criterios de aceptación:
    - Dado un pago próximo a vencer o atrasado, cuando se cumple la fecha
      configurada, entonces el sistema envía un recordatorio automático al
      paciente sin intervención manual.
  - Fuente: gestor_administrativo.md, recepcionista.md (R-09)

- **[US-08]** Como gestor administrativo, quiero un registro centralizado
  del estado de cada paciente (activo/inactivo, fecha de inicio,
  recurrencia, datos de contacto básicos), para no tener que pedírselos a
  la psicóloga cada vez que los necesito.
  - Criterios de aceptación:
    - Dado un paciente registrado en el sistema, cuando consulto su
      ficha, entonces veo su estado y datos básicos sin pedirlos a otro
      colega.
  - Fuente: gestor_administrativo.md (R-10)
