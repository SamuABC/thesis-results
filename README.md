# thesis-results

Static GitHub Pages site that displays training results for the C-T2M model.

## Live site

Enable GitHub Pages (Settings → Pages → Source: **Deploy from a branch** → `main` / `(root)`) to host the site at `https://<username>.github.io/thesis-results/`.

## Expected folder structure

Place the training data next to `index.html` before pushing:

```
C-T2M_trainings/
├── Training 1/
│   ├── 1_metrics_plot.png
│   └── visualizations_best_epoch/
│       ├── 1.gif
│       ├── 2.gif
│       ├── 3.gif
│       ├── 4.gif
│       ├── 5.gif
│       └── 6.gif
├── Training 2/
│   ├── 2_metrics_plot.png
│   └── visualizations_best_epoch/
│       └── ...  (6 gifs)
...
└── Training 15/
    ├── 15_metrics_plot.png
    └── visualizations_best_epoch/
        └── ...  (6 gifs)
```

> **Note:** If your GIF filenames differ from `1.gif – 6.gif`, update the `GIF_NAMES` array near the top of `index.html`.