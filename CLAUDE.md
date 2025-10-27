# CLAUDE.md

Guía para asistentes que colaboren con este repositorio del **Dossier de Cierre** de la Junta de Agua de Jerusalén.

## Resumen del Proyecto
- Documento **LaTeX modular** para compilar un **dossier de entrega–recepción** (Oct 2023 – Oct 2025).  
- **Idioma:** Español · **Compilador:** XeLaTeX · **Salida:** `main.pdf`  
- **Enfoque:** Administrativo/operativo (no académico).

## Regla clave (estructural)
**No crear archivos separados para subsecciones.** Cada capítulo vive en **un único archivo** dentro de `sections/` y las subsecciones se redactan **dentro** de ese archivo.

## Estructura del Documento
```
sections/
├─ 01_informe_gestion.tex
├─ 02_informe_economico.tex       # contiene 2.1–2.4
├─ 03_inventario.tex              # contiene 3.1–3.2
├─ 04_planos_croquis.tex
├─ 05_catastro_y_nuevos_socios.tex
├─ 06_correspondencia_relevante.tex
├─ 07_contratos_convenios_contactos.tex
├─ 08_accesos_credenciales.tex
└─ 09_acta_entrega_recepcion.tex  # contiene 9.A y 9.B
```

## Orden de capítulos (definitivo)
1. Informe de Gestión del Presidente (Oct 2023 – Oct 2025)  
2. Informe Económico (2.1 Conciliaciones, 2.2 Arqueo, 2.3 Ctas por Cobrar, 2.4 Ctas por Pagar)  
3. Inventario (3.1 durables, 3.2 insumos/stock)  
4. Planos y Croquis (nota + carpeta de planos del proyecto)  
5. Catastro y Nuevos Socios (Oct 2023 – Oct 2025)  
6. Correspondencia Relevante  
7. Contratos, Convenios y Directorio de Contactos  
8. Hoja de Accesos y Credenciales (transferencia y cambios)  
9. Acta General de Entrega–Recepción (9.A archivos/llaves; 9.B respaldo digital)  
**Anexos:** A Operador (mensuales), B Planos, C Listados

## Estilo y Contenido
- Redacción en **español** con tono **claro y administrativo**.  
- Tablas simples y legibles (`booktabs/longtable/tabularx` si el preámbulo ya los carga).  
- Indicar **fechas de corte** explícitas (31/10/2025 en arqueo).  
- **Planos:** describir brevemente en Cap. 4 y colocar **copias completas** en `anexos/B_planos_completos/`.  
- **Operador:** no resumir informes; solo referenciarlos en `anexos/A_informes_operador/`.  
- **Catastro:** en Cap. 5 indicar número real de nuevos socios 2023–2025 y adjuntar lista completa en `anexos/C_listados/`.

## Seguridad de la Información
- **Nunca** incluir contraseñas. En Cap. 8 usar **rol/usuario**, **responsable**, **fecha límite de cambio** y **confirmación**.  
- Datos personales (teléfonos/correos) solo en el **Directorio** (Cap. 7) con propósito operativo.  
- PDFs firmados permanecerán en `anexos/` y se referenciarán desde el texto.

## Compilación
**Rápida:**
```bash
xelatex main.tex
```
**Con bibliografía (si aplica):**
```bash
xelatex main.tex && biber main && xelatex main.tex && xelatex main.tex
```

## Tareas para asistentes
1. Mantener `main.tex` con el orden de capítulos arriba indicado.  
2. Garantizar que las subsecciones estén **dentro** del archivo del capítulo.  
3. Verificar rutas a `anexos/` cuando se suban PDFs reales.  
4. Revisar coherencia de fechas y nombres (Jerusalén, Biblián, Cañar).  
5. Evitar duplicación entre capítulos y anexos (referenciar en vez de copiar).

## Do / Don’t
**Do**
- Claridad y brevedad (listas y tablas).  
- Prefijos numéricos en nombres de archivo.  
- Notas explícitas cuando el contenido se adjunta en anexos.

**Don’t**
- No cambiar el periodo de gestión ni el orden de capítulos sin instrucción.  
- No crear archivos extra para 2.1–2.4, 3.1–3.2, 9.A–9.B.  
- No publicar datos sensibles o credenciales.

*Última actualización: 26/10/2025*
