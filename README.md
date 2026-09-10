# EURGBP 3d OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-1_739_rows-blue)](https://getdata.finance/datasets/eurgbp) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/eurgbp)

### -> [**Download the full EURGBP dataset on getdata.finance**](https://getdata.finance/datasets/eurgbp)

**EURGBP 3d OHLCV forex historical data** — ultra high-quality 3d OHLCV for **Euro / British Pound**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 3d OHLCV** for **Euro / British Pound** (Forex)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3d`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/eurgbp) · **1,739** `3d` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3d` sample updated in sync

> **Sample on GitHub** · `EURGBP_3d.csv` (244 rows, `2024-09-08` -> `2026-09-07`, 27.84 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/eurgbp)** — **1,739** `3d` rows (full `1m`: 5,322,800), **11 timeframes**, `2012-05-23` -> `2026-09-07`.

## Download sample

**[EURGBP_3d.csv](https://github.com/getdata-finance/eurgbp-3d-ohlcv-forex-historical-data/blob/main/EURGBP_3d.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/eurgbp-3d-ohlcv-forex-historical-data/main/EURGBP_3d.csv)) · [GitHub Releases](https://github.com/getdata-finance/eurgbp-3d-ohlcv-forex-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/eurgbp-3d-ohlcv-forex-historical-data/](https://getdata-finance.github.io/eurgbp-3d-ohlcv-forex-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/eurgbp](https://getdata.finance/datasets/eurgbp)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/eurgbp))** |
|---|--:|---|
| Instrument | Euro / British Pound · Forex | Euro / British Pound · Forex |
| Timeframes | `3d` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 3d rows | 244 | **1,739** |
| Size | 27.84 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/eurgbp) |
| Period | `2024-09-08` -> `2026-09-07` | `2012-05-23` -> `2026-09-07` |
| File | `EURGBP_3d.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/eurgbp) |
| Coverage report | — | [EURGBP coverage](https://getdata.finance/coverage/eurgbp) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3d` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/eurgbp)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `3d` sample · [getdata.finance](https://getdata.finance/datasets/eurgbp) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3d` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`EURGBP_3d.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2024-09-08T00:00:00+00:00 | 0.84354 | 0.84469 | 0.83929 | 0.84009 | 364170.7609 |
| 2024-09-11T00:00:00+00:00 | 0.84009 | 0.84394 | 0.83947 | 0.84052 | 655155.92604 |
| 2024-09-14T00:00:00+00:00 | 0.84052 | 0.84173 | 0.8392 | 0.83985 | 175051.09376 |
| 2024-09-17T00:00:00+00:00 | 0.83985 | 0.84281 | 0.83645 | 0.83799 | 796702.63423 |
| 2024-09-20T00:00:00+00:00 | 0.83799 | 0.83842 | 0.83541 | 0.83738 | 237297.17935 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-08-26T00:00:00+00:00 | 0.85551 | 0.85788 | 0.85518 | 0.85565 | 446060 |
| 2026-08-29T00:00:00+00:00 | 0.85512 | 0.85753 | 0.85485 | 0.85753 | 158714 |
| 2026-09-01T00:00:00+00:00 | 0.85753 | 0.86079 | 0.856 | 0.8595 | 475621 |
| 2026-09-04T00:00:00+00:00 | 0.8595 | 0.85976 | 0.85818 | 0.85917 | 164969 |
| 2026-09-07T00:00:00+00:00 | 0.85917 | 0.85954 | 0.85704 | 0.85865 | 233824 |

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

df = pd.read_csv('EURGBP_3d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('EURGBP_3d.csv', parse_dates=['datetime'])
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

df = pd.read_csv('EURGBP_3d.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3d')
print(pf.stats())
```

## Download full data

The complete **EURGBP** archive on **[getdata.finance](https://getdata.finance/datasets/eurgbp)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **1,739** rows at `3d`, plus all other timeframes in the same ZIP.

**[-> Get the full EURGBP dataset on getdata.finance](https://getdata.finance/datasets/eurgbp)**

---
*GetData · EURGBP 3d OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/eurgbp)*
