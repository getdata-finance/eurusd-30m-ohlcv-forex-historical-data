# EURUSD 30m OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-56_430_rows-blue)](https://getdata.finance/datasets/eurusd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/eurusd)

### -> [**Download the full EURUSD dataset on getdata.finance**](https://getdata.finance/datasets/eurusd)

**EURUSD 30m OHLCV forex historical data** — ultra high-quality 30m OHLCV for **Euro / US Dollar**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 30m OHLCV** for **Euro / US Dollar** (Forex)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`30m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/eurusd) · **56,430** `30m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `30m` sample updated in sync

> **Sample on GitHub** · `EURUSD_30m.csv` (6,255 rows, `2026-03-10` -> `2026-09-09`, 609.95 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/eurusd)** — **56,430** `30m` rows (full `1m`: 1,685,501), **11 timeframes**, `2022-02-27` -> `2026-09-09`.

## Download sample

**[EURUSD_30m.csv](https://github.com/getdata-finance/eurusd-30m-ohlcv-forex-historical-data/blob/main/EURUSD_30m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/eurusd-30m-ohlcv-forex-historical-data/main/EURUSD_30m.csv)) · [GitHub Releases](https://github.com/getdata-finance/eurusd-30m-ohlcv-forex-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/eurusd-30m-ohlcv-forex-historical-data/](https://getdata-finance.github.io/eurusd-30m-ohlcv-forex-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/eurusd](https://getdata.finance/datasets/eurusd)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/eurusd))** |
|---|--:|---|
| Instrument | Euro / US Dollar · Forex | Euro / US Dollar · Forex |
| Timeframes | `30m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 30m rows | 6,255 | **56,430** |
| Size | 609.95 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/eurusd) |
| Period | `2026-03-10` -> `2026-09-09` | `2022-02-27` -> `2026-09-09` |
| File | `EURUSD_30m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/eurusd) |
| Coverage report | — | [EURUSD coverage](https://getdata.finance/coverage/eurusd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`30m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/eurusd)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `30m` sample · [getdata.finance](https://getdata.finance/datasets/eurusd) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `30m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`EURUSD_30m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-10T19:00:00+00:00 | 1.17068 | 1.17109 | 1.16982 | 1.16986 | 7250 |
| 2026-03-10T19:30:00+00:00 | 1.16986 | 1.17024 | 1.16898 | 1.16965 | 9637 |
| 2026-03-10T20:00:00+00:00 | 1.16965 | 1.16977 | 1.16902 | 1.1697 | 2973 |
| 2026-03-10T20:30:00+00:00 | 1.1697 | 1.16972 | 1.16902 | 1.16931 | 1839 |
| 2026-03-10T21:00:00+00:00 | 1.16931 | 1.16931 | 1.16879 | 1.16892 | 335.21598 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-09T00:00:00+00:00 | 1.16277 | 1.16317 | 1.16277 | 1.16314 | 2787 |
| 2026-09-09T00:30:00+00:00 | 1.16314 | 1.16324 | 1.16295 | 1.16324 | 2169 |
| 2026-09-09T01:00:00+00:00 | 1.16324 | 1.16324 | 1.16278 | 1.16287 | 2462 |
| 2026-09-09T01:30:00+00:00 | 1.16287 | 1.16314 | 1.16275 | 1.16312 | 1909 |
| 2026-09-09T02:00:00+00:00 | 1.16312 | 1.16312 | 1.1631 | 1.16311 | 23 |

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

df = pd.read_csv('EURUSD_30m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('EURUSD_30m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('EURUSD_30m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='30min')
print(pf.stats())
```

## Download full data

The complete **EURUSD** archive on **[getdata.finance](https://getdata.finance/datasets/eurusd)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **56,430** rows at `30m`, plus all other timeframes in the same ZIP.

**[-> Get the full EURUSD dataset on getdata.finance](https://getdata.finance/datasets/eurusd)**

---
*GetData · EURUSD 30m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/eurusd)*
