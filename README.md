# Constitucional - Web de estudio

Web estática para estudiar Derecho Constitucional.

## Cómo publicarla en GitHub Pages

1. Crear un repositorio nuevo en GitHub, por ejemplo `constitucional-estudio`.
2. En esta carpeta, ejecutar:

```powershell
git remote add origin https://github.com/TU_USUARIO/constitucional-estudio.git
git branch -M main
git push -u origin main
```

3. En GitHub, abrir el repositorio y entrar a:

`Settings` -> `Pages` -> `Build and deployment`

4. Elegir:

- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/root`

5. Guardar. GitHub va a generar una URL parecida a:

`https://TU_USUARIO.github.io/constitucional-estudio/`

