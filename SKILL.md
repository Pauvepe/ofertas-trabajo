# Skill: Ofertas Trabajo

## Que hace
Busca ofertas de empleo REALES para Pau. Empleado con nomina, 100% remoto, media jornada, en Espana.

## Filtros OBLIGATORIOS (si falla UNO se descarta)

1. **100% remoto / teletrabajo** — nada de hibrido, nada de "remoto con visitas puntuales"
2. **Empresa en Espana** — la empresa tiene que estar en Espana. No empresas de LATAM, no USA, no UK
3. **Max 2 anos de experiencia** — si pide 3+ anos = FUERA. Si pide "experiencia demostrable" sin numero = OK
4. **Min 700 EUR/mes** — si dice el salario y es menos de 700 = FUERA. Si no dice salario = OK (se asume que cumple)
5. **NO pide titulo universitario** — ni grado, ni ingenieria, ni master. FP/grado superior SI vale. "Formacion relacionada" = OK
6. **NO pide Elementor, Divi, page builders** — si el puesto es "maquetador Elementor" = FUERA. WordPress con codigo SI
7. **Contrato de empleado** — no freelance, no autonomo, no "colaboracion". Contrato laboral

## Que tipo de puestos buscar

Palabras clave para buscar (combinar con "remoto", "teletrabajo", "media jornada"):
- Soporte tecnico / helpdesk
- Marketing operations / digital ops
- Webmaster
- Tecnico digital
- Especialista CRM (HubSpot, Salesforce, Pipedrive)
- Tecnico de automatizacion (n8n, Zapier, Make)
- Programador web junior
- Desarrollador WordPress (solo si es codigo, no page builders)
- WooCommerce developer
- Tecnico integraciones / APIs
- Community manager tecnico
- Administrador de sistemas junior
- Soporte e-commerce

## Donde buscar

### Portales Espana (PRIORIDAD)
1. InfoJobs — infojobs.net (filtrar teletrabajo + media jornada + informatica)
2. LinkedIn — es.linkedin.com/jobs (filtrar remoto + Espana)
3. TecnoEmpleo — tecnoempleo.com/ofertas-trabajo/teletrabajo
4. Indeed — es.indeed.com (teletrabajo + media jornada)
5. Jooble — es.jooble.org
6. Glassdoor — glassdoor.es

### Portales remotos con empresas espanolas
7. KiwiRemoto — kiwiremoto.com
8. RemotoList — remotolist.com
9. RemotoJob — remotojob.com

## Metodo de verificacion (CRITICO — como en /prospectos)

**NUNCA fiarse del titulo ni del resumen.** Siempre entrar a la oferta real.

### Paso 1: Busqueda rapida
- WebSearch con las palabras clave de arriba
- Filtrar resultados por titulo (descartar obvios: "senior", "5 anos", "presencial", "LATAM")
- Quedarse con los candidatos que parecen cumplir

### Paso 2: Verificacion de cada oferta
Para CADA oferta candidata, hacer WebFetch de la URL de la oferta y comprobar:

- [ ] **Experiencia**: Leer el texto REAL. Si dice "3 anos minimo" o "5+ years" = FUERA aunque el titulo diga junior
- [ ] **Modalidad**: Confirmar que dice "100% remoto" o "teletrabajo total". Si dice "hibrido" o "2 dias oficina" = FUERA
- [ ] **Ubicacion empresa**: Confirmar que la empresa esta en Espana. Si la empresa es de Mexico, Colombia, Argentina = FUERA
- [ ] **Estudios**: Si pide "Grado en Informatica", "Ingenieria", "Carrera universitaria" = FUERA. Si pide FP, ciclo formativo, o nada = OK
- [ ] **Herramientas**: Si el puesto es de WordPress, confirmar que NO es "experto en Elementor/Divi". Buscar "codigo", "PHP", "custom", "desarrollo"
- [ ] **Tipo contrato**: Confirmar que es contrato laboral, no freelance ni autonomo
- [ ] **Salario**: Si lo indica, confirmar que es >= 700 EUR/mes (o >= 10.000 EUR/ano bruto aprox)
- [ ] **Jornada**: Media jornada o jornada parcial. Si solo hay completa pero el salario es bueno, incluir marcandolo

### Paso 3: Registro
Si la oferta PASA todos los checks, guardar en archivo markdown con formato:

```
## [Titulo del puesto] — [Empresa]

| Campo | Detalle |
|-------|---------|
| Empresa | Nombre (ubicacion) |
| Puesto | Titulo exacto |
| Modalidad | 100% remoto |
| Jornada | Media jornada / Completa |
| Salario | Lo que diga (o "No indicado") |
| Experiencia requerida | Lo que diga exactamente |
| Estudios requeridos | Lo que diga exactamente |
| Herramientas | Lista de tech stack |
| URL oferta | Link directo |
| Portal | InfoJobs / LinkedIn / etc |
| Fecha publicacion | Si aparece |

### Verificacion
- [x] Experiencia <= 2 anos: TEXTO REAL DICE "..."
- [x] 100% remoto: TEXTO REAL DICE "..."
- [x] Empresa Espana: SI — [ciudad]
- [x] Sin titulo universitario: TEXTO REAL DICE "..."
- [x] Sin page builders: OK / N/A
- [x] Contrato empleado: TEXTO REAL DICE "..."
- [x] Salario >= 700: TEXTO REAL DICE "..." / No indicado

### Que haria Claude
Breve descripcion de como Claude haria el trabajo del dia a dia.
```

## Archivo de salida
- Nombre: `YYYY-MM-DD-busqueda.md` (fecha del dia)
- Subir al repo `Pauvepe/ofertas-trabajo` via API de GitHub
- Si ya existe archivo del dia, ANADIR las nuevas ofertas al final (no sobreescribir)

## Resumen final
Al terminar, mostrar tabla resumen:

```
| # | Puesto | Empresa | Salario | Jornada | URL |
```

Y decir cuantas ofertas se encontraron, cuantas se descartaron y por que.
