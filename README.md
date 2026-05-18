# [📊 Estado de Reser](https://status.reser.app)

[![Uptime CI](https://github.com/afantiniv/reser-status/workflows/Uptime%20CI/badge.svg)](https://github.com/afantiniv/reser-status/actions?query=workflow%3A%22Uptime+CI%22)
[![Response Time CI](https://github.com/afantiniv/reser-status/workflows/Response%20Time%20CI/badge.svg)](https://github.com/afantiniv/reser-status/actions?query=workflow%3A%22Response+Time+CI%22)
[![Graphs CI](https://github.com/afantiniv/reser-status/workflows/Graphs%20CI/badge.svg)](https://github.com/afantiniv/reser-status/actions?query=workflow%3A%22Graphs+CI%22)
[![Static Site CI](https://github.com/afantiniv/reser-status/workflows/Static%20Site%20CI/badge.svg)](https://github.com/afantiniv/reser-status/actions?query=workflow%3A%22Static+Site+CI%22)
[![Summary CI](https://github.com/afantiniv/reser-status/workflows/Summary%20CI/badge.svg)](https://github.com/afantiniv/reser-status/actions?query=workflow%3A%22Summary+CI%22)

<!--start: description-->

Página de estado pública de [Reser](https://reser.app) — monitoreo en tiempo
real de la plataforma, generado con [Upptime](https://upptime.js.org) y servido
gratis desde GitHub Actions + Pages.

<!--end: description-->

## [📈 Estado en vivo](https://status.reser.app): <!--live status--> **🟩 Todos los sistemas operando con normalidad**

<!--start: status pages-->
<!-- Esta tabla la genera Upptime automáticamente — no la edites a mano. -->
<!--end: status pages-->

<!--start: docs-->

## ⭐ Cómo funciona

- GitHub Actions hace de monitor de uptime: cada 5 minutos visita los endpoints
  de Reser para verificar que estén en línea.
- El tiempo de respuesta se registra y se commitea a git para los gráficos
  históricos.
- GitHub Issues se usa para los reportes de incidentes: se abre un issue cuando
  un endpoint cae y se cierra automáticamente cuando vuelve.
- GitHub Pages sirve la página de estado pública en
  [status.reser.app](https://status.reser.app).

Toda la configuración vive en [`.upptimerc.yml`](./.upptimerc.yml).

<!--end: docs-->

---

_Hecho con [Upptime](https://upptime.js.org)._
