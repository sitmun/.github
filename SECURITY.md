# Security policy

*[Versión en castellano más abajo](#política-de-seguridad).*

## Supported versions

Only the latest release line of SITMUN receives security fixes.

| Version | Supported |
| --- | --- |
| 1.3.x | Yes |
| 1.2.x and earlier | No: no maintenance releases are planned |

The per-component repositories archived in 2026 (`sitmun-backend-core`, `sitmun-admin-app`, `sitmun-viewer-app` and the others) receive no changes. Their code now lives in [sitmun/sitmun](https://github.com/sitmun/sitmun), and fixes are released there.

## Reporting a vulnerability

**Do not open a public issue, discussion or pull request for a vulnerability.**

Report it privately through GitHub (you need a GitHub account):

1. Go to the [Security tab of sitmun/sitmun](https://github.com/sitmun/sitmun/security).
2. Click **Report a vulnerability**.
3. Describe the problem: the affected component (backend, proxy, administration app, viewer, MBTiles service or mobile apps), the version, the steps to reproduce it, and its impact.

Only the SITMUN security team can see the report. If the vulnerability is in the documentation site, report it the same way on [sitmun/sitmun.github.io](https://github.com/sitmun/sitmun.github.io/security).

## What happens next

- The security team acknowledges the report as soon as possible.
- It confirms the problem, agrees a severity with you, and prepares a fix in a private GitHub security advisory. You can be invited to take part in it.
- When the fix is released, the advisory is published, with a CVE where it applies. You are credited unless you prefer not to be.

Please give the team a reasonable time to release a fix before any public disclosure.

---

# Política de seguridad

## Versiones con soporte

Solo la última línea de versiones de SITMUN recibe correcciones de seguridad.

| Versión | Soporte |
| --- | --- |
| 1.3.x | Sí |
| 1.2.x y anteriores | No: no hay previstas versiones de mantenimiento |

Los repositorios por componente archivados en 2026 (`sitmun-backend-core`, `sitmun-admin-app`, `sitmun-viewer-app` y los demás) no reciben cambios. Su código está ahora en [sitmun/sitmun](https://github.com/sitmun/sitmun), y las correcciones se publican allí.

## Cómo notificar una vulnerabilidad

**No abras una incidencia, discusión o *pull request* públicos para notificar una vulnerabilidad.**

Notifícala de forma privada a través de GitHub (se necesita una cuenta de GitHub):

1. Ve a la [pestaña Security de sitmun/sitmun](https://github.com/sitmun/sitmun/security).
2. Pulsa **Report a vulnerability**.
3. Describe el problema: el componente afectado (backend, proxy, aplicación de administración, visor, servicio MBTiles o aplicaciones móviles), la versión, los pasos para reproducirlo y su impacto.

Solo el equipo de seguridad de SITMUN puede ver la notificación. Si la vulnerabilidad está en la web de documentación, notifícala del mismo modo en [sitmun/sitmun.github.io](https://github.com/sitmun/sitmun.github.io/security).

## Qué ocurre después

- El equipo de seguridad acusa recibo lo antes posible.
- Confirma el problema, acuerda contigo la gravedad y prepara la corrección en un aviso de seguridad privado de GitHub, en el que se te puede invitar a participar.
- Cuando se publica la corrección, se publica también el aviso, con un CVE si corresponde. Se te reconoce la notificación, salvo que prefieras que no.

Te pedimos que des al equipo un plazo razonable para publicar la corrección antes de difundir el problema.
