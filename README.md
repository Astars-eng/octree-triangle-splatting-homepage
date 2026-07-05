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

## Private Preview Note

Regular GitHub Pages sites are generally public. For private collaboration before release, keep the repository private and ask collaborators to preview locally with `python -m http.server`. Private Pages with repository-level access control require GitHub Enterprise Cloud organization features.

## Structure

```text
index.html          Main homepage
assets/             Images, videos, CSS, JavaScript, and report PDF
assets/repord.pdf   Final report PDF linked from the homepage
```
