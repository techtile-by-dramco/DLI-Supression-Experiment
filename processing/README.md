### Processing

Helper scripts for preparing TX phases and visualizing measurements.

#### Plotting
- `plot-values-positions-2d.py`: per-folder matplotlib heatmap; set `FOLDER` inside the script.
- `plot_all_folders_heatmap.py`: aggregates folders under `../data`, saves `heatmap.png` into each folder, and shows the plot. Example:
  ```
  python plot_all_folders_heatmap.py --plot-all --plot-movement
  ```
- `plot_all_folders_heatmap_live.py`: Plotly/Dash heatmap that refreshes every 2s (defaults to newest folder).

#### Energy-ball post-processing
- `process-energy-ball.py`: summarizes `server/record/data/exp-*.yml`, plots iteration power, and rewrites `client/tx-phases-energy-ball.yml` with the best phases.

#### Phase generation
- `compute-tx-phases.py`: fetch tile geometry and write `client/tx-phases-friis.yml` and `client/tx-phases-benchmark.yml`.
- `compute-tx-weights-sionna.py`: generate Sionna-based weights/phases (`tx-weights-sionna.yml`, `tx-phases-sionna-<specular_order>SDR.yml`).
