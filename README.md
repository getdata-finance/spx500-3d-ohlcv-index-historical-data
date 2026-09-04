# SPX500 3d OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-2_148_rows-blue)](https://getdata.finance/datasets/spx500) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/spx500)

### -> [**Download the full SPX500 dataset on getdata.finance**](https://getdata.finance/datasets/spx500)

**SPX500 3d OHLCV index historical data** — ultra high-quality 3d OHLCV for **S&P 500**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 3d OHLCV** for **S&P 500** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3d`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/spx500) · **2,148** `3d` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3d` sample updated in sync

> **Sample on GitHub** · `SPX500_3d.csv` (244 rows, `2024-09-02` -> `2026-09-01`, 18.82 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/spx500)** — **2,148** `3d` rows (full `1m`: 5,815,518), **11 timeframes**, `2008-12-31` -> `2026-09-01`.

## Download sample

**[SPX500_3d.csv](https://github.com/getdata-finance/spx500-3d-ohlcv-index-historical-data/blob/main/SPX500_3d.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/spx500-3d-ohlcv-index-historical-data/main/SPX500_3d.csv)) · [GitHub Releases](https://github.com/getdata-finance/spx500-3d-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/spx500-3d-ohlcv-index-historical-data/](https://getdata-finance.github.io/spx500-3d-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/spx500](https://getdata.finance/datasets/spx500)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/spx500))** |
|---|--:|---|
| Instrument | S&P 500 · Index | S&P 500 · Index |
| Timeframes | `3d` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 3d rows | 244 | **2,148** |
| Size | 18.82 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/spx500) |
| Period | `2024-09-02` -> `2026-09-01` | `2008-12-31` -> `2026-09-01` |
| File | `SPX500_3d.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/spx500) |
| Coverage report | — | [SPX500 coverage](https://getdata.finance/coverage/spx500) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3d` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/spx500)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `3d` sample · [getdata.finance](https://getdata.finance/datasets/spx500) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3d` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`SPX500_3d.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2024-09-02T00:00:00+00:00 | 5641.6 | 5657.13 | 5495.65 | 5512.75 | 467970.60353 |
| 2024-09-05T00:00:00+00:00 | 5512.75 | 5546.55 | 5388.72 | 5390.2 | 485930 |
| 2024-09-08T00:00:00+00:00 | 5390.2 | 5499.53 | 5390.2 | 5491.94 | 305230 |
| 2024-09-11T00:00:00+00:00 | 5491.94 | 5637 | 5406.72 | 5623.16 | 579044 |
| 2024-09-14T00:00:00+00:00 | 5623.16 | 5638.02 | 5605.76 | 5632.43 | 179552 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-08-20T00:00:00+00:00 | 7722.28 | 7727.3 | 7640.03 | 7673.37 | 527485.72866 |
| 2026-08-23T00:00:00+00:00 | 7673.37 | 7701.49 | 7640.79 | 7670.46 | 515398 |
| 2026-08-26T00:00:00+00:00 | 7670.46 | 7772.43 | 7659.46 | 7713.36 | 806894 |
| 2026-08-29T00:00:00+00:00 | 7713.36 | 7715.62 | 7666.65 | 7695.51 | 227951 |
| 2026-09-01T00:00:00+00:00 | 7695.51 | 7700.02 | 7613.55 | 7629.85 | 249415 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('SPX500_3d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('SPX500_3d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

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

df = pd.read_csv('SPX500_3d.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3d')
print(pf.stats())
```

## Download full data

The complete **SPX500** archive on **[getdata.finance](https://getdata.finance/datasets/spx500)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **2,148** rows at `3d`, plus all other timeframes in the same ZIP.

**[-> Get the full SPX500 dataset on getdata.finance](https://getdata.finance/datasets/spx500)**

---
*GetData · SPX500 3d OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/spx500)*
