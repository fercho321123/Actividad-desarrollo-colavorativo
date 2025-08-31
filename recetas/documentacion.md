# Documentación del flujo de trabajo

## 1. Ramas creadas y responsables
- feature/recetas-colombianas → A (fernando jimenez, fercho321123)
- feature/recetas-mexicanas → B (fernando jimenez, fercho321123)
- feature/recetas-italianas → C (felipe bernal, ScissorSevens)

## 2. Comandos ejecutados (principales)
```bash
git init
git commit -m
git lg
ls -la
git status
git clone ...
git checkout -b feature/recetas-colombianas
git add .
git commit -m "feat: ..."
git push -u origin feature/recetas-colombianas
# PRs, merges, resolución de conflictos
git fetch origin
git merge origin/main
git tag -a v1.0.0 -m "Versión 1.0.0"
git push origin v1.0.0