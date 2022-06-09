# Auto-deployed Resume Static Website

```
Built using:
- Astro
- CloudFlare
- GitHub
```

## Astro Commands

All commands are run from the root of the project, from a terminal:

| Command           | Action                                       |
|:----------------  |:-------------------------------------------- |
| `npm install`     | Installs dependencies                        |
| `npm run dev`     | Starts local dev server at `localhost:3000`  |
| `npm run build`   | Build your production site to `./dist/`      |
| `npm run preview` | Preview your build locally, before deploying |

## CloudFlare

1- Setup a CloudFlare page
2- Point the page to your repo & select Astro framework
3- Configure a custom domain

## GitHub

Pushing commits to your repo will automatically build and deploy to CloudFlare Pages
