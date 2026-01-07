# Data Heatmaps

Heatmaps saved alongside each measurement series. Generate them with:
```
cd ..
python processing/plot_all_folders_heatmap.py --plot-all
```

| Folder | Heatmap | Baseline vs RANDOM (dB) |
| --- | --- | --- |
| energy-ball-A | ![energy-ball-A](energy-ball-A/heatmap.png) | ![energy-ball-A vs RANDOM](energy-ball-A/heatmap_vs_RANDOM_dB.png) |
| RANDOM | ![RANDOM](RANDOM/heatmap.png) | ![RANDOM vs RANDOM](RANDOM/heatmap_vs_RANDOM_dB.png) |
| RECI-0 | ![RECI-0](RECI-0/heatmap.png) | ![RECI-0 vs RANDOM](RECI-0/heatmap_vs_RANDOM_dB.png) |
| sionna0-0 | ![sionna0-0](sionna0-0/heatmap.png) | ![sionna0-0 vs RANDOM](sionna0-0/heatmap_vs_RANDOM_dB.png) |

## Archived runs
- Older plots and runs with bad REF/LB sync were moved to `data/arxiv/`; associated plots were removed from this README.
