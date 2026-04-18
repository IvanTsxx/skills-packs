# skills-packs

[English](./README.md)

Una colección de packs de skills para agentes de IA, agrupados por tecnología y caso de uso. Creado para desarrolladores que se cansaron de escribir siempre los mismos comandos y quieren acceso rápido a sus skills esenciales.

## Motivación

¿Alguna vez te encontraste escribiendo los mismos comandos una y otra vez? Este proyecto lo soluciona agrupando tus skills más usados en unidades instalables. No más configuraciones repetitivas—solo instala lo que necesitas y listo.

## Instalación

Instala los skills usando la [CLI de Vercel Skills](https://github.com/vercel-labs/skills):

```bash
npx skills add ivanTsxx/skills-packs/skills/next
```

Esto te permitirá seleccionar qué skills del pack quieres instalar.

## Packs de Skills Disponibles

### Next.js (`skills/next`)

- **architect-nextjs** — Establecer arquitectura para aplicaciones Next.js 15+
- **next-best-practices** — Mejores prácticas para desarrollo con Next.js
- **next-cache-components** — Estrategias de caché y componentes

### React (`skills/react`)

- **vercel-react-best-practices** — Mejores prácticas de React por Vercel

### Paquetes (`skills/packages`)

- **ai-sdk** — Patrones de integración con AI SDK
- **shadcn** — Patrones de componentes de shadcn/ui
- **two-factor-authentication-best-practices** — Patrones de implementación de 2FA
- **email-and-password-best-practices** — Patrones de autenticación email/password
- **organization-best-practices** — Patrones de organización/autenticación
- **create-auth-skill** — Creación de skills de autenticación
- **better-auth-best-practices** — Patrones de la librería better-auth

### Diseño (`skills/design`)

- **brand-guidelines** — Guías de identidad de marca
- **emil-design-eng** — Patrones de design engineering
- **frontend-design** — Patrones de diseño frontend
- **interface-design** — Diseño de interfaces UI
- **theme-factory** — Generación y gestión de temas
- **ui-ux-pro-max** — Patrones avanzados de UI/UX
- **web-design-guidelines** — Mejores prácticas de diseño web

### General (`skills/general`)

- **find-skills** — Encontrar y descubrir skills disponibles
- **skill-creator** — Crear nuevos skills para agentes de IA
- **skills-cli** — Patrones de uso de la CLI de skills

### Accesibilidad (`skills/accessibility`)

- **accessibility-a11y** — Patrones de accesibilidad (a11y)

### SEO (`skills/seo`)

- **ai-seo** — Optimización SEO con IA
- **seo-audit** — Patrones de auditoría SEO

### Marketing (`skills/marketing`)

- **copy-editing** — Patrones de edición de textos
- **copywriting** — Patrones de copywriting

## Ejemplos de Uso

Instalar todos los skills de Next.js:
```bash
npx skills add ivanTsxx/skills-packs/skills/next
```

Instalar skills de React:
```bash
npx skills add ivanTsxx/skills-packs/skills/react
```

Instalar skills de diseño:
```bash
npx skills add ivanTsxx/skills-packs/skills/design
```

Instalar skills de SEO:
```bash
npx skills add ivanTsxx/skills-packs/skills/seo
```

Instalar skills de accesibilidad:
```bash
npx skills add ivanTsxx/skills-packs/skills/accessibility
```

Instalar skills de paquetes (shadcn, ai-sdk, patrones de auth):
```bash
npx skills add ivanTsxx/skills-packs/skills/packages
```

Instalar skills generales (skill creator, CLI):
```bash
npx skills add ivanTsxx/skills-packs/skills/general
```

Instalar skills de marketing:
```bash
npx skills add ivanTsxx/skills-packs/skills/marketing
```

## Categorías

| Categoría | Descripción |
|----------|-------------|
| **next** | Patrones de Next.js y Server Components |
| **react** | Mejores prácticas de React |
| **packages** | Integraciones con librerías de terceros (auth, AI, UI) |
| **design** | Patrones de sistemas de diseño y UI/UX |
| **general** | Skills para crear y administrar skills |
| **accessibility** | Patrones y técnicas de accesibilidad (a11y) |
| **seo** | Optimización y auditoría de SEO |
| **marketing** | Patrones de copywriting y contenido |

## Recursos

- [CLI de Vercel Skills](https://github.com/vercel-labs/skills)
- [Skills.sh](https://skills.sh/)
- [Documentación de Skills](https://github.com/vercel-labs/skills#readme)