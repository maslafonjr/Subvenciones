# Subvenciones — Vigilancia de ayudas a la fotovoltaica (CV / Castellón)

Repositorio de memoria persistente para la rutina semanal de vigilancia de subvenciones
de energía solar fotovoltaica (autoconsumo, almacenamiento, comunidades energéticas) en
la Comunitat Valenciana, con foco en la provincia de Castellón.

## Estructura

- `ULTIMO_INFORME.md`: informe completo de la ejecución más reciente (se sobrescribe cada semana).
- `NOVEDADES.md`: novedades detectadas en la ejecución más reciente respecto a la anterior (se sobrescribe cada semana).
- `historico/AAAA-MM-DD.md`: snapshot íntegro de cada ejecución semanal (no se sobrescribe, sirve de base de comparación).
- `informe_visual.html`: fuente del Artifact HTML (tabla filtrable) que se publica cada semana.
  **Importante para la próxima ejecución:** editar este mismo fichero (no crear uno nuevo) y volver a
  publicarlo con la herramienta Artifact usando la misma ruta, para que se actualice la misma URL en
  lugar de generar una nueva cada semana. URL publicada la última vez:
  https://claude.ai/code/artifact/cd85448d-c964-48a2-bdcd-632f40702cdf
