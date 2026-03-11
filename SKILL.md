# Skill: Ofertas Trabajo

## Que hace
Busca ofertas de empleo REALES de codigo/tech para Pau. Empleado, 100% remoto, España.

## Filtros OBLIGATORIOS — si falla UNO se descarta, sin excepciones

1. **100% remoto** — nada de hibrido, nada de presencial, nada de "2 dias oficina". SOLO 100% remoto
2. **Empresa en España** — sede o contrato español
3. **Max 2 años de experiencia**
4. **Min 700 EUR/mes**
5. **NO pide grado universitario** — FP/grado superior SI vale, "formacion relacionada" OK
6. **Contrato de empleado** — no freelance, no autonomo
7. **Trabajo tecnico** — codigo, APIs, automatizacion, desarrollo web, diseño de apps/webs, integraciones

## PROHIBIDO incluir

- Teleoperador, call center, atencion al cliente, ventas
- Community manager, social media (salvo que sea tecnico)
- Soporte N1 basico tipo "resetear contraseñas"
- Cualquier cosa que no sea tecnica

## 3 tipos de puesto a buscar

### 1. Desarrollador web junior (frontend o fullstack)
- HTML, CSS, JS, React, Next.js, WordPress con codigo, PHP
- Maquetacion, desarrollo de webs, landing pages, ecommerce
- Palabras clave: "desarrollador web junior remoto", "frontend junior teletrabajo", "maquetador web remoto codigo"

### 2. Diseñador/desarrollador UI de apps y webs
- Diseño + codigo de interfaces (Figma → codigo, prototipado funcional)
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

## Metodo de verificacion — CRITICO

### Regla de oro: si NO puedo entrar a la pagina y ver la oferta real, NO la incluyo

### Paso 1: Busqueda
- WebSearch con palabras clave de los 3 tipos
- Filtrar por titulo (descartar senior, 5 años, presencial, LATAM, freelance)

### Paso 2: Verificacion VISUAL obligatoria
Para CADA oferta, hacer WebFetch de la URL y comprobar VISUALMENTE:

- [ ] Es 100% remoto — TEXTO LITERAL de la oferta lo confirma
- [ ] Max 2 años experiencia — TEXTO LITERAL confirma
- [ ] No pide universidad — TEXTO LITERAL confirma
- [ ] Es trabajo tecnico (codigo/APIs/automatizacion/diseño)
- [ ] Empresa en España
- [ ] Salario >= 700 EUR/mes (si lo dice)
- [ ] Contrato empleado
- [ ] Link funciona y la oferta esta ABIERTA

**Si WebFetch da 403/405/error → NO incluir la oferta. Buscar en otro portal donde SI se pueda verificar.**

**Si la oferta esta cerrada o expirada → NO incluir.**

### Paso 3: Registro
Solo ofertas que PASEN todos los checks con verificacion visual:

```
## [Titulo] — [Empresa]

| Campo | Detalle |
|-------|---------|
| Empresa | Nombre |
| Puesto | Titulo |
| Modalidad | 100% remoto (TEXTO LITERAL: "...") |
| Jornada | Completa/Parcial |
| Salario | Cantidad (TEXTO LITERAL) |
| Experiencia | TEXTO LITERAL |
| Estudios | TEXTO LITERAL |
| Tech stack | Herramientas |
| Contrato | Tipo |
| URL oferta | Link directo que FUNCIONA |
| Verificado | SI — WebFetch confirmado |

### Que haria Claude
Como Claude haria el trabajo tecnico del dia a dia.
```

## Archivo de salida
- Nombre: `YYYY-MM-DD-busqueda.md`
- Subir al repo `Pauvepe/ofertas-trabajo`
- SOLO ofertas 100% verificadas visualmente
- Si no hay NINGUNA que pase todos los filtros, decirlo y NO inventar
