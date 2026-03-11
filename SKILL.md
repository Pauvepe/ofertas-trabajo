# Skill: Ofertas Trabajo

## Que hace
Busca ofertas de empleo REALES de codigo/tech para Pau. Empleado, 100% remoto, España.

## Filtros OBLIGATORIOS — si falla UNO se descarta, sin excepciones

1. **100% remoto** — nada de hibrido, nada de presencial, nada de "2 dias oficina". SOLO 100% remoto
2. **Empresa en España** — sede o contrato español
3. **Max 3 años de experiencia** — si pide mas, FUERA
4. **Min 700 EUR/mes**
5. **NO pide grado universitario** — FP/grado superior SI vale, "formacion relacionada" OK, Grado Superior en Diseño de Productos Interactivos vale
6. **Contrato de empleado** — no freelance, no autonomo
7. **Trabajo tecnico** — codigo, APIs, automatizacion, desarrollo web, diseño de apps/webs, integraciones
8. **Empresa pequeña** — PYME, startup, agencia, 5-50 empleados aprox. NO multinacionales, NO empresas gigantes
9. **Oferta NUEVA** — publicada en los ultimos 15 dias maximo. Si es mas vieja, FUERA
10. **Oferta ABIERTA** — que acepte candidatos. Si dice "cerrada" o "ya no se aceptan", FUERA

## PROHIBIDO incluir

- Teleoperador, call center, atencion al cliente, ventas
- Community manager, social media (salvo que sea tecnico)
- Soporte N1 basico tipo "resetear contraseñas"
- Cualquier cosa que no sea tecnica
- Ofertas que NO se hayan verificado visualmente con WebFetch
- Ofertas donde WebFetch dio error (403, 405, etc) — buscar en OTRO portal donde SI se pueda ver
- Ofertas cerradas o expiradas
- Ofertas de empresas gigantes (+500 empleados)

## 3 tipos de puesto a buscar

### 1. Desarrollador web junior (frontend o fullstack)
- HTML, CSS, JS, React, Next.js, WordPress con codigo, PHP
- Maquetacion, desarrollo de webs, landing pages, ecommerce
- Palabras clave: "desarrollador web junior remoto", "frontend junior teletrabajo", "maquetador web remoto codigo"

### 2. Diseñador/desarrollador UI de apps y webs
- Diseño + codigo de interfaces (Figma a codigo, prototipado funcional)
- Apps moviles, dashboards, webs interactivas
- Palabras clave: "diseñador UI developer remoto", "product designer junior remoto", "UX/UI developer"

### 3. Tecnico de automatizacion / integraciones
- Conectar APIs, flujos n8n/Make/Zapier, automatizar procesos
- Integrar herramientas: CRM + ads + email + ecommerce
- Palabras clave: "automation specialist junior remoto", "tecnico integraciones remoto", "no-code developer"

## Donde buscar

1. LinkedIn — es.linkedin.com/jobs (filtrar 100% remoto + España)
2. InfoJobs — infojobs.net (teletrabajo + informatica)
3. TecnoEmpleo — tecnoempleo.com/ofertas-trabajo/teletrabajo
4. Glassdoor — glassdoor.es
5. Arc.dev — arc.dev/remote-jobs
6. RemotoList — remotolist.com
7. Jooble — es.jooble.org
8. Workable — jobs.workable.com
9. Indeed — es.indeed.com
10. Domestika Jobs — domestika.org/es/jobs
11. GetOnBrd — getonbrd.com
12. Manfred — manfred.tech
13. Talent.com — es.talent.com

## Metodo de verificacion — CRITICO

### Regla de oro: si NO puedo entrar a la pagina y ver la oferta real, NO la incluyo. PUNTO.

### Paso 1: Busqueda
- WebSearch con palabras clave de los 3 tipos
- Filtrar por titulo (descartar senior, 5 años, presencial, LATAM, freelance, multinacional)

### Paso 2: Verificacion VISUAL obligatoria
Para CADA oferta, hacer WebFetch de la URL y comprobar VISUALMENTE:

- [ ] Es 100% remoto — TEXTO LITERAL de la oferta lo confirma
- [ ] Max 3 años experiencia — TEXTO LITERAL confirma (o no pide experiencia)
- [ ] No pide universidad ni ingenieria — TEXTO LITERAL confirma
- [ ] Es trabajo tecnico (codigo/APIs/automatizacion/diseño)
- [ ] Empresa en España y pequeña (no multinacional)
- [ ] Salario >= 700 EUR/mes (si lo dice)
- [ ] Contrato empleado (no freelance)
- [ ] La oferta esta ABIERTA y acepta candidatos
- [ ] Publicada hace menos de 15 dias
- [ ] Link funciona

**Si WebFetch da error → NO incluir. Buscar la misma oferta en otro portal.**
**Si ALGUN check falla → NO incluir. Sin excepciones.**
**Si no se puede confirmar un dato critico → NO incluir.**

### Paso 3: Registro
Solo ofertas que PASEN TODOS los checks con verificacion visual:

```
## [Titulo] — [Empresa]

| Campo | Detalle |
|-------|---------|
| Empresa | Nombre (tamaño aprox) |
| Puesto | Titulo |
| Modalidad | 100% remoto — TEXTO LITERAL: "..." |
| Experiencia | TEXTO LITERAL: "..." |
| Estudios | TEXTO LITERAL: "..." |
| Tech stack | Herramientas |
| Contrato | Tipo |
| Salario | TEXTO LITERAL (o "no indicado") |
| Fecha publicacion | DD/MM/YYYY |
| URL oferta | Link directo VERIFICADO |
| Estado | ABIERTA — verificado visualmente |

### Que haria Claude
Como Claude haria el trabajo tecnico del dia a dia.
```

## Si no hay NINGUNA oferta que pase todos los filtros
Decirlo claramente: "No he encontrado ofertas que cumplan el 100% de los criterios."
NO inventar. NO poner ofertas a medias. NO poner "verificar tu".
