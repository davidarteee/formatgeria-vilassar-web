# La Formatgeria de Vilassar — web

Web estàtica (un sol `index.html` autònom) del client **La Formatgeria de Vilassar**.

- **Producció:** https://formatgeriavdm.dakerstudio.com (Hostinger)
- **Desplegament:** automàtic per FTP a cada `push` a la branca `main`
  (vegeu `.github/workflows/deploy.yml`).

## Com editar

1. Edita `index.html`.
2. `git add -A && git commit -m "descripció del canvi"`
3. `git push`
4. GitHub Actions puja els fitxers a Hostinger automàticament (~1 min).

## Flux de treball (DakerStudio)

Aquest repo és la plantilla del flux "un client = un repo = un subdomini".
Per a un client nou: carpeta neta amb `index.html`, repo nou a GitHub,
mateix workflow, i els 4 secrets d'FTP del nou hosting.
