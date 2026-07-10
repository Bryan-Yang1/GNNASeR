# Data

This directory contains JSON files with TSP instance IDs used for the train/test splits and filtering settings in the experiments.

The full TSP instances and solver execution logs are not stored in this Git repository. They are available from Google Drive:

https://drive.google.com/drive/folders/1RABzr-qS9OKF5Za1G1IUxUO5WgjK-BPq?usp=sharing

After downloading the full dataset, place or symlink the following directories under `data/`:

- `tsp_instances_training/`
- `tsp_instances_testing/`
- `tsp_executions/`

The training scripts use these directories by default through `--data_root data`.
