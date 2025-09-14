# Contributing Guidelines

Gracias por querer contribuir 🎉

## Flujo de trabajo
1. Haz fork del repo.
2. Crea una rama desde `main`:
   - `feature/<nombre>` para nuevas funcionalidades.
   - `fix/<nombre>` para bugs.
   - `chore/<nombre>` para mantenimiento o docs.
3. Haz commits siguiendo [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/).
   - Ejemplo: `feat(api): add JWT auth middleware`
4. Abre un Pull Request hacia `main`.

## PR Checklist
- [ ] PR basado en `feature/*`, `fix/*` o `chore/*`.
- [ ] Incluye al menos 1 label (`feature`, `fix`, `chore`, `security`).
- [ ] Tests/lint ejecutados si aplica.
- [ ] Al menos 1 aprobación de revisor.

## Estilo de código
- Mantén consistencia con el código existente.
- Usa `pre-commit` o linters si están configurados.

## Seguridad
- Nunca subas credenciales o secretos.
- Si encuentras vulnerabilidades, sigue [SECURITY.md](./SECURITY.md).
