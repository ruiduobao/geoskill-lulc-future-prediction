# Land Cover Prediction (geoskill-lulc-future-prediction)

> Markov transition probabilities plus a simplified CA-Markov model to predict land cover for a target year, including urban expansion simulation and uncertainty

---

## 1. Overview

(Add 2-3 paragraphs of introduction here: features, application scenarios, core algorithms.)

## 3. Quick Start

```bash
pip install -r requirements.txt
python geoskill-lulc-future-prediction.py --bbox 116 39 117 40 --synthetic --output-dir ./out
```

## 4. CLI Parameters

Run `python <skill>.py --help` for the full list. Common parameters:

| Parameter | Type | Description |
|---|---|---|
| `--bbox` | `float[4]` | WGS84 bounding box `min_lon min_lat max_lon max_lat` |
| `--input` | `path` | Local input file (GeoJSON/GeoTIFF/etc.) |
| `--output-dir` | `path` | Output directory (default `./output`) |
| `--synthetic` | `flag` | Use synthetic data instead of real input |
| `--quiet` | `flag` | Suppress non-essential stdout |

## 5. Input / Output

| File | Format | Description |
|---|---|---|
| `result.tif` | GeoTIFF | Primary output |
| `output-manifest.json` | JSON | Run manifest |


## 6. Technical Principle

(See SKILL.md for details.)

## 8. License

MIT License. See [`LICENSE`](./LICENSE) for full text.

---

> 中文完整版：[references/SKILL.zh-CN.md](references/SKILL.zh-CN.md)
