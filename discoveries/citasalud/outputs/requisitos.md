# Requisitos candidatos — CitaSalud

> Cada requisito cita el archivo de entrevista y la persona/stakeholder de
> origen. Numeración correlativa R-01…

## Funcionales

- **[R-01]** Centralizar las notas e informes de sesión de cada paciente en
  un solo lugar accesible para el profesional.
  - Tipo: funcional
  - Origen: doctora.md · Psicóloga clínica

- **[R-02]** Mantener un historial accesible de diagnósticos e informes
  generados, evitando que se pierdan.
  - Tipo: funcional
  - Origen: doctora.md · Psicóloga clínica

- **[R-03]** Registrar las sesiones acordadas con cada paciente (p. ej.
  "3 horas semanales durante 6 meses") y mostrar su cumplimiento/avance.
  - Tipo: funcional
  - Origen: doctora.md, gestor_administrativo.md · Psicóloga clínica, Gestor
    administrativo

- **[R-04]** Gestionar el calendario de citas evitando choques de horario y
  reflejando cambios de último momento.
  - Tipo: funcional
  - Origen: recepcionista.md · Recepcionista

- **[R-05]** Enviar recordatorios de citas a los pacientes y notificar
  cambios por un canal centralizado.
  - Tipo: funcional
  - Origen: recepcionista.md · Recepcionista

- **[R-06]** Permitir confirmar y trazar el envío de informes a pacientes,
  para responder si un informe fue enviado o llegó sin depender de
  búsquedas manuales.
  - Tipo: funcional
  - Origen: recepcionista.md · Recepcionista

- **[R-07]** Registrar el estado de pago de cada paciente (por sesión, por
  paquete, por cuotas) de forma centralizada, reemplazando el control en
  Excel.
  - Tipo: funcional
  - Origen: gestor_administrativo.md · Gestor administrativo

- **[R-08]** Mostrar visibilidad de horas vendidas vs. horas entregadas, y
  de lo facturado vs. lo cobrado.
  - Tipo: funcional
  - Origen: gestor_administrativo.md · Gestor administrativo

- **[R-09]** Enviar recordatorios automáticos de pago a los pacientes
  cuando se acerca o vence una fecha de pago.
  - Tipo: funcional
  - Origen: gestor_administrativo.md, recepcionista.md · Gestor
    administrativo, Recepcionista

- **[R-10]** Mantener un registro centralizado del estado del paciente
  (activo/inactivo, fecha de inicio, recurrencia, datos de contacto
  básicos).
  - Tipo: funcional
  - Origen: gestor_administrativo.md · Gestor administrativo

## No funcionales

- **[R-11]** Restringir el acceso al contenido de los informes/diagnósticos
  por rol, de modo que la recepcionista pueda gestionar su envío sin poder
  ver su contenido.
  - Tipo: no funcional (seguridad / control de acceso)
  - Origen: doctora.md, recepcionista.md · Psicóloga clínica, Recepcionista

- **[R-12]** Garantizar la confidencialidad de los diagnósticos y datos
  sensibles de los pacientes frente a pérdida o acceso no autorizado.
  - Tipo: no funcional (seguridad / confidencialidad)
  - Origen: doctora.md · Psicóloga clínica
