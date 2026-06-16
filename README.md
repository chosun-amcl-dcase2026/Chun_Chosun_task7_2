# Chun_Chosun_task7_2 — OR-KDL LoRA Selective Augment (OR-KDL-LS)

DCASE 2026 Challenge **Task 7**, System 2 (Chosun University).

Same OR-KDL + LoRA pipeline as System 1 with **class-selective augmentation**,
plus orthogonal gradient projection, distillation, and k-fold ensembling.

## Model checkpoints

Weights are not stored in this repo due to size. Download from Google Drive:

**https://drive.google.com/drive/folders/1RZOGw4nUFIsj8NDBRuKDV8oiI3SBQH4D**

Use the archive **`Chun_Chosun_task7_2_checkpoints.tar.gz`** (30 checkpoints:
D2 dictionary 5-fold + D3 dictionary 25). Extract into the repo root:

```bash
tar -xzf Chun_Chosun_task7_2_checkpoints.tar.gz -C .
```

This restores `Chun_Chosun_task7_2_D2_dictionary/` and `Chun_Chosun_task7_2_D3_dictionary/`.
