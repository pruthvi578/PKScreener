[![MADE-IN-INDIA](https://img.shields.io/badge/MADE%20WITH%20%E2%9D%A4%20IN-INDIA-orange?style=for-the-badge)](https://en.wikipedia.org/wiki/India) [![GitHub release (latest by date)](https://img.shields.io/github/v/release/pkjmesra/PKScreener?style=for-the-badge)](#) [![GitHub all releases](https://img.shields.io/github/downloads/pkjmesra/PKScreener/total?color=Green&label=Downloads&style=for-the-badge)](#) [![MADE_WITH](https://img.shields.io/badge/BUILT%20USING-PYTHON-yellow?style=for-the-badge&logo=python&logoColor=yellow)](https://www.python.org/)

## What's New?
1. [v0.41.20230901.39] release

* Fixed several bugs in backtesting. Now, backtesting default is set to 30 periods in the past.
* You can now get html formatted outputs for backtesting results and summary of correctness of strategies.
* Backtest results and summary of backtests now available at https://pkjmesra.github.io/PKScreener/BacktestReports.html
* Backtests are now available for dates/days until as recent as yesterday.
* Several other warnings fixed.

## Older Releases
4. [v0.4.20230825.38] release

* The pkscreener Telegram bot (@nse_pkscreener_bot) can now respond to your on-demand requests for almost all scan results.
* Added 52-week low/high breakout screeners (X > 12 > 15, X > 12 > 17)
* Added 10-days low breakout screener (X > 12 > 16)
* Added Aroon(5) Bullish Crossover scanner
* Font bug fixes for Ubuntu so now you can send telegram notifications with attachments from Ubuntu as well.
* Stability and performance enhancements. Network requests default now to IPv4 only because IPv6 delays the requests.
* Added overall summary prediction of backtests.
* Fixed RSI screening to be evaluated for range 67 <= RSI <=71
* Many other bug fixes and improvement in [v0.4.x] weekly releases

3. [v0.3] release

* Now avaialble via pipy as a package. You can just run `pip install pkscreener` to get it working. After installation, just run `pkscreener` on your favorite command line.

2. [v0.2] release

* Backtests are now enabled. You can now choose any strategy and backtest for the past 1 year's data.
* Logging with option `-l` is now enabled for troubleshooting
* Telegram alerts for all major scanner strategies.
* Includes an option to create user's own telegram channel and receive alerts there.
* The application now runs without TA-Lib as well.

1. First release - [v0.01]

## Downloads
| Operating System                                                                                         | Executable File                                                                                                                                                                                                              |
| -------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white) | **[pkscreenercli.exe](https://github.com/pkjmesra/PKScreener/releases/download/0.41.20230901.39/pkscreenercli.exe)**                                                                                                         |
| ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)       | **[pkscreenercli.bin](https://github.com/pkjmesra/PKScreener/releases/download/0.41.20230901.39/pkscreenercli.bin)**                                                                                                         |
| ![Mac OS](https://img.shields.io/badge/mac%20os-D3D3D3?style=for-the-badge&logo=apple&logoColor=000000)  | **[pkscreenercli.run](https://github.com/pkjmesra/PKScreener/releases/download/0.41.20230901.39/pkscreenercli.run)** ([Read Installation Guide](https://github.com/pkjmesra/PKScreener/blob/main/INSTALLATION.md#for-macos)) |

## How to use?

[**Click Here**](https://github.com/pkjmesra/PKScreener) to read the documentation. You can also read it at https://pkscreener.readthedocs.io/en/latest/?badge=latest

## Join our Community Discussion

[**Click Here**](https://github.com/pkjmesra/PKScreener/discussions) to join the community discussion and see what other users are doing!

## Facing an Issue? Found a Bug?

[**Click Here**](https://github.com/pkjmesra/PKScreener/issues/new/choose) to open an Issue so we can fix it for you!

## Want to Contribute?

[**Click Here**](https://github.com/pkjmesra/PKScreener/blob/main/CONTRIBUTING.md) before you start working with us on new features!

## Disclaimer:
* DO NOT use the result provided by the software solely to make your trading decisions.
* Always backtest and analyze the stocks manually before you trade.
* The Author(s) and the software will not be held liable for any losses.

## License
* MIT: https://github.com/pkjmesra/PKScreener/blob/main/LICENSE
