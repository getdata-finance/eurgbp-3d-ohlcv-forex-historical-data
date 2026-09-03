# EURGBP 3d OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-6_244_rows-blue)](https://getdata.finance/datasets/eurgbp) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/eurgbp)

### -> [**Download the full EURGBP dataset on getdata.finance**](https://getdata.finance/datasets/eurgbp)

**EURGBP 3d OHLCV forex historical data** — ultra high-quality 3d OHLCV for **Euro / British Pound**. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3d`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/eurgbp) · **6,244** `3d` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3d` sample updated in sync

> **Sample on GitHub** · `EURGBP_3d.csv` (18 rows, `2026-07-12` -> `2026-09-01`, 1.35 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/eurgbp)** — **6,244** `3d` rows (full `1m`: 5,322,882), **11 timeframes**, `1975-01-02` -> `2026-09-01`.

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
| 3d rows | 18 | **6,244** |
| Size | 1.35 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/eurgbp) |
| Period | `2026-07-12` -> `2026-09-01` | `1975-01-02` -> `2026-09-01` |
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

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-12T00:00:00+00:00 | 0.85113 | 0.85446 | 0.84547 | 0.84645 | 623034 |
| 2026-07-15T00:00:00+00:00 | 0.84645 | 0.85268 | 0.84612 | 0.85128 | 659116 |
| 2026-07-18T00:00:00+00:00 | 0.84877 | 0.85385 | 0.84832 | 0.85206 | 291218 |
| 2026-07-21T00:00:00+00:00 | 0.85206 | 0.85539 | 0.85157 | 0.85307 | 628542 |
| 2026-07-24T00:00:00+00:00 | 0.85307 | 0.85596 | 0.85161 | 0.85537 | 320717 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-08-20T00:00:00+00:00 | 0.85672 | 0.85763 | 0.85504 | 0.85532 | 175824 |
| 2026-08-23T00:00:00+00:00 | 0.85573 | 0.85635 | 0.85463 | 0.85566 | 209375 |
| 2026-08-26T00:00:00+00:00 | 0.85566 | 0.85688 | 0.85435 | 0.85482 | 195755 |
| 2026-08-29T00:00:00+00:00 | 0.85512 | 0.8578 | 0.85485 | 0.85763 | 295652 |
| 2026-09-01T00:00:00+00:00 | 0.85763 | 0.85781 | 0.85691 | 0.85739 | 18653 |

## Schema

| Column | Description |
| --- | --- |
| `time` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('EURGBP_3d.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('EURGBP_3d.csv', parse_dates=['time'])
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

df = pd.read_csv('EURGBP_3d.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3d')
print(pf.stats())
```

## Download full data

The complete **EURGBP** archive on **[getdata.finance](https://getdata.finance/datasets/eurgbp)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **6,244** rows at `3d`, plus all other timeframes in the same ZIP.

**[-> Get the full EURGBP dataset on getdata.finance](https://getdata.finance/datasets/eurgbp)**

---
*GetData · EURGBP 3d OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/eurgbp)*
