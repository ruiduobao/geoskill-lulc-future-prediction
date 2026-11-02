---
name: geoskill-lulc-future-prediction
description: '马尔可夫转移概率 + 简化 CA-Markov 预测目标年土地覆被，含城市扩张模拟与不确定性'
---

# 土地覆被预测 | LULC Future Prediction

(Fill in 2-3 paragraphs of Chinese introduction here: functionality, application scenarios, core algorithm.)

## Dependencies / 依赖

```bash
pip install 'numpy' 'rasterio' 'scipy' 'scikit-learn'
```

## Usage / 使用方法

### Basic Usage

```bash
python geoskill-lulc-future-prediction.py --bbox 116.0 39.0 117.0 40.0 [other parameters]
```

### Example 1 (synthetic data, offline)

```bash
python geoskill-lulc-future-prediction.py --bbox 116.0 39.0 117.0 40.0 --synthetic --output-dir ./out
```

### Examples 2-5

(Add at least 4 real usage examples.)

## Output / 输出

| File | Format | Description |
|---|---|---|
| `result.tif` | GeoTIFF | Main deliverable |
| `output-manifest.json` | JSON | Run manifest |

## Data Source / 数据源 / Source

(Describe the data source: free satellite data / local input / synthetic.)

## Privacy / 隐私声明 / Privacy

- Runs offline by default; `--synthetic` mode requires no network at all.
- All processing is performed locally; no user data is uploaded.

## License / License

MIT

---

> 中文完整版：需要时再读 [references/SKILL.zh-CN.md](references/SKILL.zh-CN.md)，不要默认全量加载。
