# Dossier de Cierre – Junta Administradora de Agua Potable y Saneamiento de Jerusalén

## 📋 Información General
- **Entidad:** Junta Administradora de Agua Potable y Saneamiento de **Jerusalén**  
- **Ubicación:** Parroquia **Jerusalén**, Cantón **Biblián**, Provincia **Cañar**  
- **Período de Gestión:** **Octubre 2023 – Octubre 2025**  
- **Presidenta saliente:** Sra. **María Justa Jerez Tenecela**  
- **Presidente entrante:** Dr. **Gonzalo Castro Jerez**  
- **Propósito del repositorio:** Mantener un **dossier modular en LaTeX** (con anexos) para la **entrega–recepción** y continuidad operativa de la Junta.

## 🎯 Entregables
1. **PDF maestro** del dossier (carátula, índice y capítulos).  
2. **Carpeta de anexos** (planos, informes, listados, copias de oficios/contratos).  
3. **Acta General de Entrega–Recepción** (se redacta como capítulo y se **anexa** la versión firmada).  

> El **operador** permanece en funciones. Sus **informes mensuales** se **referencian** como **anexo** (no se resumen dentro del dossier).

---

## 🧩 Índice de Capítulos (definitivo)
> **Importante:** No se crean archivos separados para subsecciones. Las subsecciones van **dentro** del archivo del capítulo.

- **Portada (Carátula)**

**Capítulo 1 — Informe de Gestión del Presidente (Oct 2023 – Oct 2025)**

**Capítulo 2 — Informe Económico**  
• 2.1 *Conciliaciones* (Nov 2024 – Oct 2025)  
• 2.2 *Acta de Arqueo de Caja* (31/10/2025)  
• 2.3 *Cuentas por Cobrar* – Morosidad al corte  
• 2.4 *Cuentas por Pagar* – Proveedores/servicios y vencimientos

**Capítulo 3 — Inventario de Bienes y Herramientas**  
• 3.1 *Bienes y herramientas (durables)*  
• 3.2 *Insumos y stock operativo* (cloro, tubería, abrazaderas; **mínimos sugeridos**)

**Capítulo 4 — Planos y Croquis de Infraestructura**  
*Nota: gracias al nuevo proyecto se cuenta con **planos técnicos**; se **adjuntan** en carpeta.*

**Capítulo 5 — Catastro de Usuarios y Nuevos Socios (Oct 2023 – Oct 2025)**  
*Mencionar crecimiento (p. ej., “10 nuevos socios” como marcador) y **adjuntar** el listado completo impreso y digital.*

**Capítulo 6 — Correspondencia Relevante (oficios enviados/recibidos)**  
*Índice (N°, fecha, asunto, remitente/destinatario, estado), copias PDF y **ruta** a carpeta digital.*

**Capítulo 7 — Contratos, Convenios y Directorio de Contactos**  
*Vigencias, obligaciones pendientes y **contactos clave** (operador, fontanero, proveedores, GAD, tenencia política, emergencias).*

**Capítulo 8 — Hoja de Accesos y Credenciales**  
*Banca, correo, nube, redes; **nuevo responsable**; **fecha límite** de cambio de claves; constancia de recepción.*

**Capítulo 9 — Acta General de Entrega–Recepción**  
• 9.A *Entrega de archivos y llaves* (oficina, bodega, planta, cloración; libros y carpetas; recomendación de cambiar cerraduras críticas en 48h).  
• 9.B *Respaldo digital (Drive + USB)* (transferencia de propiedad del Drive y entrega de USB sellado).

**Anexos**  
A. **Informes mensuales del Operador** (solo referencia a carpeta)  
B. **Planos completos del proyecto** (PDF/DWG)  
C. **Listas completas** (padrón/catastro, nuevos socios, etc.)

---

## 🗂️ Estructura del Proyecto (carpetas y archivos)
```
.
├─ main.tex
├─ cover.tex
├─ FORMAT.md
├─ figures/
│  └─ logo.png
├─ sections/
│  ├─ 01_informe_gestion.tex
│  ├─ 02_informe_economico.tex       # incluye 2.1–2.4 como subsecciones
│  ├─ 03_inventario.tex              # incluye 3.1–3.2
│  ├─ 04_planos_croquis.tex
│  ├─ 05_catastro_y_nuevos_socios.tex
│  ├─ 06_correspondencia_relevante.tex
│  ├─ 07_contratos_convenios_contactos.tex
│  ├─ 08_accesos_credenciales.tex
│  └─ 09_acta_entrega_recepcion.tex  # incluye 9.A y 9.B
└─ anexos/
   ├─ A_informes_operador/
   ├─ B_planos_completos/
   └─ C_listados/
```

---

## 🧭 Contenido mínimo por capítulo (guía rápida)
- **1. Informe de Gestión:** logros, obras/mantenimientos (qué–dónde–cuándo–costo si aplica), gestiones con instituciones, atención al usuario, recomendaciones.  
- **2. Informe Económico:** resumen (ingresos/egresos, saldo), indicadores (% morosidad, rubros). Subapartados: conciliaciones, arqueo 31/10/2025, ctas por cobrar/pagar.  
- **3. Inventario:** 3.1 durables (tabla + fotos); 3.2 insumos/stock (cloro, tubería, abrazaderas) con mínimos sugeridos.  
- **4. Planos:** croquis general (válvulas críticas y sectores); **nota** de que los planos técnicos van a **Anexos B**.  
- **5. Catastro y nuevos socios:** altas/bajas; crecimiento (n° de nuevos socios reales) y lista completa en **Anexos C**.  
- **6. Correspondencia:** índice + PDFs y rutas.  
- **7. Contratos/Convenios/Contactos:** tabla de vigencias y obligaciones; directorio (operador, fontanero, proveedores, GAD, tenencia política, emergencias).  
- **8. Accesos y Credenciales:** sistema, usuario/rol, nuevo responsable, **fecha límite de cambio**, confirmación. *Nunca contraseñas en claro.*  
- **9. Acta Entrega–Recepción:** alcance y fecha de corte; referencia a 1–8; 9.A archivos/llaves; 9.B respaldo digital (Drive + USB).

---

## 🔧 Requisitos y Compilación
- Compilador recomendado: **XeLaTeX** (Arial y español).  
- Si no usas bibliografía:  
  ```bash
  xelatex main.tex
  ```
- Si usas bibliografía (`biblatex`/`biber`):  
  ```bash
  xelatex main.tex && biber main && xelatex main.tex && xelatex main.tex
  ```

## ✅ Buenas Prácticas
- Mantén nombres con prefijo numérico: `NN_titulo.tex`.  
- No almacenar **contraseñas** ni datos sensibles. Usa roles y constancias en Cap. 8.  
- PDFs firmados deben ir en `anexos/` y ser referenciados desde el capítulo correspondiente.  
- Actualiza rutas de anexos cuando subas archivos reales.

*Última actualización: 26/10/2025*
