# Comparsa Moros Nómadas de Guardamar del Segura

Landing page oficial de la **Comparsa Moros Nómadas de Guardamar del Segura** (Bando Moro, fundada en 1979).

## Características

- **Multidioma:** Valenciano (por defecto), Castellano e Inglés, con selector en cabecera y persistencia en `localStorage`.
- **Secciones incluidas:**
  - Portada con cifras históricas (`1979`, `1981`, `4` generaciones, `2` presidentes de la Junta Central).
  - **Nuestra Misión:** Cometido cultural, social y festero de la asociación (preparado para validación de Google para ONG's).
  - **Historia:** Orígenes, hitos cronológicos (1979, Primera Capitanía Mora 1981, II Congreso Nacional en Ontinyent 1985) y fotografía del 40 Aniversario.
  - **Filadas:** Listado oficial de las 11 filadas (2027) y galería de desfile.
  - **Junta Directiva:** Cargos ejecutivos, Vocales y Representantes ante la Junta Central de Comparsas.
  - **Sede Social, Kábila y Contacto:** Ubicación de la Sede Social (`Casa del Mar`, C/ Colón 32, 2º), Kábila en fiestas, correo de secretaría y enlaces a redes sociales.
  - **Información Legal:** Denominación oficial, CIF (`G53092664`) y número de inscripción en el Registro Autonómico de Asociaciones (`5225`).
- **SEO:** Metadatos dinámicos por idioma, Open Graph, Twitter Card, `robots.txt` y datos estructurados `Schema.org` (`Organization`).

## Estructura del proyecto

```text
├── index.html                        # Web estática completa (HTML + Tailwind CDN + JS)
├── robots.txt                        # Directivas para buscadores
├── README.md                         # Documentación del proyecto
└── assets/
    └── 40-aniversario-escudo.jpg     # Fotografía del monumento 40 Aniversario
```

## Despliegue (GitHub Pages + DonDominio)

1. En GitHub: **Settings → Pages → Branch: `main` / `(root)` → Save**.
2. En **Custom domain**: configurar el dominio propio y marcar **Enforce HTTPS**.
3. En **DonDominio (Zona DNS)**:
   - 4 registros `A` (`@`) apuntando a `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`.
   - 1 registro `CNAME` (`www`) apuntando a `ShaneGooseman.github.io`.

## Datos de la Asociación

- **Denominación:** Asociación «MOROS NOMADAS DE GUARDAMAR DEL SEGURA»
- **CIF:** `G53092664`
- **Registro Autonómico (Generalitat Valenciana):** Sección Primera, nº `5225`
- **Sede Social:** «Casa del Mar», C/ Colón 32, 2º, 03140 Guardamar del Segura (Alicante)
- **Contacto:** `info@morosnomadasguardamar.es`
