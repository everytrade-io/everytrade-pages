# EveryTrade - Release Notes
NOTE: To get notified quickly about new releases and other important information join our EVERY TRADE Telegram channel [https://t.me/everytrade](https://t.me/everytrade).
   
## Version 2022-03-08T1405   
### New Features   
ETD-342 [portfolio] Calendar filters.   
   
### Improvements   
ETD-378 [transactions] Default view of all transactions in datamanager.   
ETD-373 [support] Kraken API help update.   
ETD-372 [containers] Update Binance CSV format.   
ETD-350 [support] Update communication channel links from the footer.   
ETD-345 [containers] EveryTrade format import symbol XDG as DOGE.   
ETD-285 [accounts] Change the order of tabs in the account detail.   
ETD-284 [connectors] Sort accounts by name in connector.   
   
### Bug Fixes   
ETD-375 [transactions] Deleting the WITHDRAWAL transaction returns error 500.   
ETD-371 [containers] CSV container shows bad portfolio inclusion.   
ETD-369 [containers] EveryTrade CSV import errors.   
ETD-192 [connectors] Coinbase PRO - deposits and withdrawals.   
ETD-191 [connectors] Coinbase - deposits and withdrawals.   
   
## Version 2022-02-28T0919   
### New Features   
ETD-52 [languages] Add Spanish and German language support.   
ETD-251 [portfolio] Portfolio time period and movement calculations.   
ETD-309 [support] EveryTrade Release Notes.   
ETD-336 [containers] Anycoin exchange exports CSV in native EveryTrade format.   
   
### Improvements   
ETD-191 [connectors] Coinbase API - support deposits and withdrawals transactions.   
ETD-192 [connectors] Coinbase Pro API - support deposits and withdrawals transactions.   
ETD-324 [transactions] Address from / to in transaction details.   
ETD-338 [account] Crypto-accounting support query.   
ETD-350 [support] Update communication channel links from the footer.   
ETD-352 [pairs] Add new symbols and tokens 22/02.   
0xBTC, ARAW, AZ, BSOV, CPRO, CWV, CYFM, DREP, DTA, EKT, ELEC, ETHMNY, ETHPLO, EVC, FLOT, GVE, HEX, KICK, LPT, LXT, MNE, ODEX, POPCOIN, POWR, PYRO, RNT, SHE, SHIT, SHR, SINGH, SLV, ZLA, ADC, ADX, AGIX, AION, AMB, ANC, ATM, AUDIO, BADGER, BELT, BNC, BRD, BTS, BURGER, BZRX, CDT, CELO, CHR, COCOS, CREAM, CTXC, CVP, DATA, ELF, ETHOS, FLUX, FOR, GNO, HIGH, HODL, IDEX, IQ, JASMY, JST, JUV, KEY, LAZIO, LPT, MBL, MC, MDT, MINA, MLN, NBS, NFT, NKN, NULS, NXS, OHM, OHMv2, OM, PERL, POKT, PORTO, POWR, PSG, QI, RAMP, RARI, REPV2, SFP, SKY, STX, SUN, TBTC, TRU, TUSD, TVK, VR, VRT, WBTC, WTC, YFII, ACA, ALPINE, BCPT, BOBA, BSD, BTCST, BTTC, COP, DON, GRS, MEETONE, ONG, PURSE, SCRT, SGB, TKO, UST, VGX, WAXP, XN.   
ETD-353 [transactions] Receiver and sender address resolution in the transaction input.   
ETD-367 [portfolio] Update portfolio help.   
ETD-368 [portfolio] Rename Portfolio currency to Accounting currency.   
   
### Bug Fixes   
ETD-235 [connectors] Coinbase API block non-standard transactions.   
ETD-265 [portfolio] When you hover over the portfolio chart, the page content disappears.   
ETD-343 [connectors] Binance API duplicates DEPOSIT, WITHDRAWAL, FAILED transactions. (Fix automatically removes duplicate transactions.)   
ETD-344 [containers] EveryTrade CSV v3.1 import crashes when reading the transactions address.   
ETD-354 [transactions] Saving a bundled fee and discount returns error 400 for DEPOSIT and WITHDRAWAL transactions.   
ETD-363 [layout] Alignment of fees in the mobile version.   
ETD-365 [portfolio] Clicking on the end of the time period chart resets the time period.   
ETD-366 [portfolio] The portfolio chart shows the previous day of the selected portfolio time period.   
   
## Version 2022-02-03T1528   
### New Features   
ETD-321 [connectors] Support for reading ERC-20 tokens from the Ethereum Blockchain. (Resync your APIs. Support for additional tokens in currency pairs will be gradually added.)   
ETD-309 [support] EveryTrade Release Notes and link from navigation.   
  
### Improvements   
ETD-326 [reports] Trading statement in accounting currency returns total profit / - loss for the reporting period.   
ETD-300 [support] Documentation disclosure of EveryTrade [API](https://everytrade.io/help/api#everytrade) & [CSV](https://everytrade.io/help/csv#everytrade) format v3.1   
ETD-234 [containers] CoinMate CSV support for DEPOSIT & WITHDRAWAL transactions. (re-import your CSVs)   
ETD-225 [connectors] CoinMate API DEPOSIT & WITHDRAWAL have no address. (resync your APIs)   
ETD-205 [accounts] CoinMate CSV imports transaction addresses. (re-import your CSVs)   
   
### Bug Fixes   
ETD-319 [transactions] Cannot save REBATE changes.   
ETD-265 [portfolio] While hovering with mouse on ET portfolio dashboard page contains disappears. (Linux)   
ETD-254 [portfolio] Empty portfolio with balances not showing values.   
ETD-27 [connectors] Blockchain ETH limited API response to 10 000 transactions. (resync your APIs)   
   
## Version 2022-01-27T1409
### Bug Fixes   
ETD-318 [transactions] Downloaded deposit from Kraken API does not appear in transactions.   
ETD-317 [portfolio] Incorrect calculation of the purchase price in the AVCO model & Errors downloading reports.   
ETD-315 [transactions] Incorrectly identified additionally added commitment fee.   
ETD-311 [transactions] Binding fee is included 2 times in the purchase price.   
ETD-308 [portfolio] Shared portfolio will not display accounts without login.   
ETD-307 [portfolio] Portfolio sharing returns a 401 error.   
ETD-297 [pairs] Import symbol XDG as DOGE.   
ETD-287 [portfolios] Stretched portfolio currency switcher.   
   
## Version 2022-01-24T1532
### New Features   
ETD-196 [audit] Inclusion of fees in the purchase price.   
ETD-148 [accounts] Report account movements to CSV file.   
ETD-209 [connectors] Extension EveryTrade CSV v3.1 format, DEPOSIT & WITHDRAWAL transactions.   
ETD-256 [pairs] Support for new 139 symbols.   
ACE, AGLD, AIOZ, ALICE, ALPHA, AMP, ANCT, AOA, ARDR, ARK, ARPA, ATA, AVAX, AWC, AXS, BAKE, BETA, BETH, BNT, BNX, BOND, BTG, BTR, BUNNY, C98, CLV, COTI, CSPR, CTK, DAR, DCR, DEGO, DERC, DOCK, DODO, DYDX, EFI, ELA, ELON, ELONGATE, ENG, ENJ, ENS, EURS, EWT, FIO, FORTH, FOX, FTM, FXS, GALA, GAS, GNT, GRIN, GTO, HBAR, HIVE, HNT, IGNIS, INJ, IOTX, KAR, KAU, KEEP, KLAY, LCX, LINA, LIT, LOCG, LOOM, LTO, MAID, MBOX, MEPAD, MFT, MIR, MITH, MOVR, MTL, NAV, NEAR, NEBL, NEXO, NPXS, NU, OCEAN, OMI, ORN, OXT, PHA, PIVX, POLY, QKC, QNT, QUICK, RAD, RDN, REEF, REQ, REVV, RLY, ROSE, RSR, RUNE, SAFEMOON, SALT, SDN, SHIB, SIB, SKL, SLP, SOLO, SPARTA, STEEM, STMX, STRAX, STRONG, SYS, TCT, TFUEL, TLM, TONCOIN, TRB, TWT, UOS, VIA, VITE, VOXEL, VRM, VTHO, WABI, WAN, WIN, WING, WPR, XCH, XHV, XMY, XVS.   
   
### Improvements   
ETD-197 [portfolio] The purchase price of the portfolio includes commitment fees and shows their amount.   
ETD-198 [portfolio] Portfolio history chart includes commitment fees.   
ETD-200 [portfolio] Inclusion and display of commitment fees in open and closed positions.   
ETD-218 [portfolio] Correct naming of revenues.   
ETD-217 [reports] Reports correctly calculate bundled fees.   
ETD-28 [connectors] EveryTrade API supports V3.1 format.   
ETD-219 [VR] Support for displaying portfolio accounts on VR.   
   
### Bug Fixes   
ETD-299 [containers] Downloading the wrong transaction log file from CSV container.   
ETD-290 [reports] Changes to report names and calculations with fees.   
ETD-289 [reports] Limit the list of reported accounts by portfolio.   
ETD-281 [connectors] Coinmate API does not load transactions before 1.1.2019. (Official connector feature. Older transactions must be imported from CSV files.)   
ETD-275 [portfolio] Error 500 FIFO portfolio caused by a fee.   
ETD-273 [connectors] Coinmate API connector duplicates deposit transactions when updating.   
ETD-269 [transactions] Firefox browser creates duplicate transactions.   
ETD-268 [transactions] Cannot update fee and dicount transaction in data manager.   
ETD-253 [datamanager] The Remove Container from Portfolio flag is not saved.   
ETD-245 [connectors] Add support Mtub prefix Litecoin xpup adress wallet.   
ETD-240 [reports] Broken report generation after AVCO / FIFO model changes.   
ETD-210 [datamanager] Random display of duplicate container during CSV import.   
ETD-139 [connectors] Incomplete synchronization and its status in the database.   
