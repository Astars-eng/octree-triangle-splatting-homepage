# Octree-guided Triangle Splatting Homepage

This repository contains the project homepage for **Octree-guided Triangle Splatting with Adaptive LoD**, a course final project built on top of the Triangle Splatting homepage template.

The page summarizes our method, including octree metadata, patch-aware triangle clustering, residual LoD hierarchy, adaptive view-dependent LoD selection, smooth residual transition, full-model distillation, and LoD-only inference.

## Local Preview

Run a static server from the repository root:

```powershell
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

If port `8000` is occupied, use another port:

```powershell
python -m http.server 8080
```

## Report PDF

The report button on the homepage points to:

```text
assets/repord.pdf
```

Place the final report PDF at that path before publishing. If the filename is changed, update the link in `index.html`.

## Deployment With GitHub Pages

Create a GitHub repository and push this folder:

```powershell
git init
git add .
git commit -m "Initial homepage"
git branch -M main
git remote add origin https://github.com/<username>/<repo-name>.git
git push -u origin main
```

Then enable GitHub Pages:

```text
Settings -> Pages -> Build and deployment
Source: Deploy from a branch
Branch: main
Folder: /root
```

For a project repository, the page will be available at:

```text
https://<username>.github.io/<repo-name>/
```

For a personal homepage repository named `<username>.github.io`, the page will be available at:

```text
https://<username>.github.io/
```

## Private Preview Note

Regular GitHub Pages sites are generally public. For private collaboration before release, keep the repository private and ask collaborators to preview locally with `python -m http.server`. Private Pages with repository-level access control require GitHub Enterprise Cloud organization features.

## Structure

```text
index.html          Main homepage
assets/             Images, videos, CSS, JavaScript, and report PDF
assets/repord.pdf   Final report PDF linked from the homepage
```
