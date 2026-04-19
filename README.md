# Conciliador · Total Home S.A.

Herramienta web para cruzar dos reportes financieros y generar la conciliación bancaria automáticamente.

**→ [Abrir herramienta](https://alexissirio.github.io/conciliador/)**

---

## Qué hace

- Carga dos archivos (CSV, XLSX o PDF) y los cruza por columnas clave
- Detecta coincidencias, partidas solo en A y partidas solo en B
- Genera un Excel de conciliación bancaria con el formato estándar del área (secciones ①②③④, control de diferencia, ✔ CONCILIADO)
- Todo corre en el browser — ningún dato sale del equipo

## Formatos soportados

| Formato | Soporte |
|---------|---------|
| CSV / TXT | ✅ Nativo |
| XLSX / XLS | ✅ Nativo |
| PDF texto | ✅ Detección automática |
| PDF complejo | ✅ Fallback con IA |

## Cómo usar

1. Subir **Reporte A** (libro banco, mayor contable, etc.)
2. Subir **Reporte B** (extracto bancario, otro sistema)
3. Elegir las columnas clave para el match (ej: Fecha + Importe)
4. Configurar tolerancia si los importes tienen diferencias de centavos
5. Ejecutar → revisar coincidencias y partidas sin match
6. Generar **Conciliación Bancaria (.xlsx)** con los datos del período

## Deploy

El archivo `index.html` es standalone — no requiere build ni servidor.
Está publicado via GitHub Pages en la rama `main`.

---

*GAF · Total Home S.A.*
