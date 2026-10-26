# Trámites en España con Claude

**Seis skills gratuitas para Claude que te ayudan a reclamar tus derechos en España**: devolver una compra online, exigir la garantía de un producto, reclamar a tu banco un pago que no hiciste, ejercer tus derechos sobre tus datos, saber qué hacer si te estafan por internet y reclamar un vuelo retrasado.

Cada skill está **escrita a partir del texto oficial** (BOE, Reglamento europeo, INCIBE, Banco de España, Your Europe), con los artículos citados y una plantilla de carta lista para copiar. Los textos legales están copiados tal cual en la carpeta [`fuentes/`](fuentes/) con la fecha en que se comprobaron.

> **Esto no es asesoramiento jurídico.** Es información general, comprobada el 26 de octubre de 2026. Las leyes cambian: verifica siempre la versión vigente en el enlace de cada fuente. Para casos de importe alto o con disputa, consulta a una asociación de consumidores o a un abogado.

## Las skills

| Skill | Para qué sirve | Fuente principal |
|---|---|---|
| [`desistimiento-compra-online`](skills/desistimiento-compra-online/SKILL.md) | Devolver una compra online o por teléfono en 14 días y exigir el reembolso | TRLGDCU (arts. 68, 76, 103-108) |
| [`garantia-producto-defectuoso`](skills/garantia-producto-defectuoso/SKILL.md) | Reclamar la garantía legal (3 años) de un producto que falla | TRLGDCU (arts. 118-122) |
| [`pago-no-autorizado-banco`](skills/pago-no-autorizado-banco/SKILL.md) | Reclamar al banco una operación que no autorizaste | RDL 19/2018 (arts. 43-46) y Banco de España |
| [`derechos-rgpd-datos-personales`](skills/derechos-rgpd-datos-personales/SKILL.md) | Acceder, corregir, borrar o llevarte tus datos; impugnar decisiones automáticas | RGPD (arts. 12, 15-22) y AEPD |
| [`estafa-online-que-hacer`](skills/estafa-online-que-hacer/SKILL.md) | Qué hacer en las primeras horas si te han estafado | INCIBE (017) y Policía Nacional |
| [`vuelo-retrasado-cancelado`](skills/vuelo-retrasado-cancelado/SKILL.md) | Reclamar compensación por un vuelo retrasado, cancelado o con embarque denegado | Reglamento (CE) 261/2004 (vía Your Europe) |

## Cómo usarlas

**Claude Code:** copia la carpeta de la skill dentro de `~/.claude/skills/` (o de `.claude/skills/` en tu proyecto). Después pídele, con tus palabras: "me han cobrado 300 € en mi tarjeta que no hice yo" o "quiero devolver unas zapatillas que compré online".

**Claude (web o app):** en los ajustes de Claude, activa las Skills y sube la carpeta de la skill comprimida en `.zip`. Los nombres de los ajustes pueden cambiar.

La skill te irá haciendo las preguntas que necesita antes de redactar nada, calculará plazos y te dará el escrito para enviar.

## Cómo se ha comprobado cada dato

- Los artículos del BOE y del RGPD están descargados de la publicación oficial y copiados literalmente en [`fuentes/`](fuentes/).
- Los datos de INCIBE (teléfono 017, horario, WhatsApp y Telegram), de la Oficina Virtual de Denuncias de la Policía Nacional, del Portal del Cliente Bancario del Banco de España y de Your Europe se leyeron en sus webs oficiales.
- Donde no he podido verificar algo (por ejemplo, el plazo para reclamar un vuelo), la skill lo dice en lugar de inventarlo.
- Si encuentras un dato desfasado o erróneo, abre una *issue*: se corrige el mismo día y se anota en el historial.

## Licencia

[Creative Commons Atribución 4.0 (CC BY 4.0)](LICENSE). Puedes copiar, adaptar y compartir, incluso con fines comerciales, **citando a El Telar con un enlace a [eltelar.es](https://eltelar.es)**.

Hecho por [El Telar](https://eltelar.es): guías prácticas de inteligencia artificial en español.
