# Contribuir a business-security

Gracias por interesarte en el proyecto.

## Antes de empezar

1. Revisá [README.md](README.md).
2. **No ejecutes scripts ofensivos** contra sistemas sin autorización.
3. Documentá el propósito de scripts nuevos.

## Cómo reportar bugs

1. Buscá si ya existe un [issue](https://github.com/ghcetraro/business_security/issues) similar.
2. Abrí uno nuevo con:
   - Versión / commit
   - Configuración relevante (**sin secretos**)
   - Comportamiento esperado vs actual

Para vulnerabilidades, seguí [SECURITY.md](SECURITY.md).

## Pull requests

1. Fork del repo y branch desde `main`:
   ```bash
   git checkout -b feature/mi-cambio
   ```
2. Cambios acotados y commits claros en español o inglés.
3. Probá en entorno controlado antes de abrir PR.
4. Actualizá README.md y CHANGELOG.md si cambiás comportamiento.
5. Abrí el PR describiendo el **por qué** del cambio.

## Estilo

- Scripts con comentario de uso y requisitos
- Sin credenciales embebidas

## Releases

Versiones etiquetadas (`v1.0.0`, …) documentadas en [CHANGELOG.md](CHANGELOG.md).

## Preguntas

Abrí un issue con etiqueta `question`.
