# US30 1w OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-2_943_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full US30 dataset on ork.ad**](https://ork.ad/)

**US30 1w OHLCV Stock index historical data** — ultra high-quality 1w OHLCV for **Dow Jones 30**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 1w OHLCV** for **Dow Jones 30** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1w`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **2,943** `1w` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `1w` sample updated in sync

> **Sample on GitHub** · `US30_1w.csv` (105 rows, `2024-07-01` → `2026-06-29`). **Full archive on [ork.ad](https://ork.ad/)** — **2,943** `1w` rows (~0.16 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `1970-02-09` → `2026-06-29`.

## Download sample

**[US30_1w.csv](https://github.com/ork-ad/us30-1w-ohlcv-index-historical-data/blob/main/US30_1w.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/us30-1w-ohlcv-index-historical-data/main/US30_1w.csv)) · [GitHub Releases](https://github.com/ork-ad/us30-1w-ohlcv-index-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/us30-1w-ohlcv-index-historical-data/](https://ork-ad.github.io/us30-1w-ohlcv-index-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | Dow Jones 30 · Stock index | Dow Jones 30 · Stock index |
| Timeframes | `1w` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 1w rows | 105 | **2,943** |
| Size | 0.01 MB | ~0.16 MB |
| Period | `2024-07-01` → `2026-06-29` | `1970-02-09` → `2026-06-29` |
| File | `US30_1w.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`1w` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `1w` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `1w` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`US30_1w.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2024-07-01T00:00:00Z | 39218.37 | 39507.34 | 39046.08 | 39374.0 | 904454.0 |
| 2024-07-08T00:00:00Z | 39374.0 | 40308.48 | 39177.65 | 40064.36 | 1315863.0 |
| 2024-07-15T00:00:00Z | 40064.36 | 41427.41 | 40064.36 | 40297.59 | 2041224.0 |
| 2024-07-22T00:00:00Z | 40297.59 | 40796.84 | 39838.4 | 40665.73 | 1890382.0 |
| 2024-07-29T00:00:00Z | 40665.73 | 41252.26 | 39359.32 | 39633.24 | 2719524.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-06-01T00:00:00Z | 51021.4 | 51760.39 | 50679.78 | 50706.03 | 2493373.0 |
| 2026-06-08T00:00:00Z | 50756.3 | 51415.75 | 49723.25 | 51225.63 | 5679470.0 |
| 2026-06-15T00:00:00Z | 51209.24 | 52285.41 | 51209.24 | 51462.9 | 2906338.0 |
| 2026-06-22T00:00:00Z | 51462.9 | 52726.62 | 51304.0 | 51852.93 | 4053959.0 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('US30_1w.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1D').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('US30_1w.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('US30_1w.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1W')
print(pf.stats())
```

## Download full data

The complete **US30** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **2,943** rows at `1w`, plus all other timeframes in the same ZIP.

**[→ Get the full US30 dataset on ork.ad](https://ork.ad/)**

---
*GetData · US30 1w OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-06 UTC*