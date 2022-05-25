# [EveryTrade](https://everytrade.io/) - Release Notes
NOTE: To get notified quickly about new releases and other important information join our EVERY TRADE Telegram channel [https://t.me/everytrade](https://t.me/everytrade).
   
## Version 2022-05-25T0916      
### New Features   
ETD-477 [pairs] Add new currencies 22/05.   
APE, BABY, CFI, CVC, EBST, EXP, HT, MXC, OCN, SRN, SUPER, UBQ, XEL   
   
### Improvements   
ETD-454 [portfolio] A clickable link to the data manager from an empty portfolio.   
ETD-421 [reports] Account Statemets report translations.   
   
### Bug Fixes   
ETD-487 [organizations] Changing Organization is not reflected in the asset accounts page.   
ETD-486 [organization] Useless scrollbar in organization detail.   
ETD-461 [portfolio] Values of initial asset account balances in non-edit mode are not formatted.   
ETD-459 [pairs] Pair selection interface performance optimization.   
ETD-453 [portfolio] Limitation of writing to the Accounting period input.   
ETD-395 [transactions] For BUY / SELL transactions, remove pairs with the same BASE / QUOTE.   
ETD-348 [accounts] Portfolio tags don't filter asset account transactions.   
ETD-301 [reports] Correction of diacritics in report file names.   
ETD-136 [containers] Diacritics in CSV file name.   
   
## Version 2022-05-12T1136   
### New Features   
ETD-447 [organizations] Organization settings.   
ETD-252 [containers] KRAKEN ledgers CSV import. Only DEPOSIT & WITHDRAWAL transactions.   
   
### Improvements   
ETD-471 [asset acccounts] Adding XPUB to the input name of the asset account address.   
ETD-428 [portfolio] For Walkthrough Portfolio activate conversion to Accounting currency.   
   
### Bug Fixes   
ETD-473 [transactions] Filter content position.   
ETD-470 [transactions] Invalid action from address field name.   
ETD-469 [reports] Confusing boxes with FIAT summarization for end-users.   
ETD-468 [reports] Adjust reporting numbers under columns Revenue and Cost for opening balance.   
ETD-466 [connectors] Changing the connector name disconnects asset accounts.   
ETD-463 [buckets] Typos and formatting issues in dialog when connecting transfers.   
ETD-462 [reports] CSV report of asset accounts has problems with czech letters.   
ETD-459 [pairs] Pair selection interface performance optimization.   
ETD-456 [transactions] Remove input addresses in BUY / SELL transaction detail.   
ETD-451 [organizations] List of organizations in main menu isn't sorted alphabetically.   
ETD-420 [portfolio] Error copying AVCO balances without portfolio time limitation.   
ETD-395 [transactions] For BUY / SELL transactions, remove pairs with the same BASE / QUOTE.   
ETD-266 [connectors] Mining fees associated with DEPOSIT or WITHDRAWAL aren't imported by blockchain connectors.   
   
## Version 2022-05-07T0651      
### Bug Fixes   
ETD-460 [portfolio] Setting initial pair balances doesn't work.   
   
## Version 2022-05-06T1235   
### New Features   
ETD-446 [organizations] Management of Organizations.  
ETD-445 [navigation] New menu item Organizations.  
ETD-435 [reports] New report: TAX Statement in Accounting Currency. (Only available when calculating the portfolio in accounting currency.)  
   
### Improvements   
ETD-444 [portfolio] Accounting currencies flags.   
ETD-443 [accounts] Rename "Accounts" to "Asset Accounts".   
ETD-437 [reports] Edit interface page Reports.   
   
### Bug Fixes   
ETD-433 [connectors] Some API connectors do’nt do automatic synchronization.   
ETD-425 [FEE] Under portfolio the buy fee not included in sumarization.   
ETD-412 [reports] Confusing boxes with FIAT summarization for end-users.   
ETD-411 [reports] Adjust reporting numbers under columns Proceeds and Cost basis.   
ETD-381 [reports] Totals for realized profit/loss for use in tax return.   
   
## Version 2022-04-27T1616  
This update brings many new pairs, fixes for API connectors and CSV imports. To maintain the health of your portfolios, we recommend performing manual maintenance. Re-sync your API connectors, and re-import your CSVs. Make sure your portfolios have Accounting Currency Conversion turn on. Delete and reload new opening balances for pairs and accounts in your portfolios. Load the balances in the direction from the oldest portfolio to the newest. Your results may change. Contact our support whenever you need help.  
  
### New Features  
ETD-436 [pairs] Add new crypto quotes 22/04.  
ADA, CRO, FRAX, HUSD, LINK, LTC, LUNA, LUSD, MANA, SOL, TUSD, USDN, UST  
ETD-434 [portfolio] Extension of the list of accounting currencies.  
ALL, ARS, BAM, BGN, BRL, BSD, BYN, CLP, CNY, COP, CRC, CUP, DKK, ECS, HRK, HUF, CHF, ILS, INR, ISK, JMD, JPY, KZT, MDL, MKD, MXN, NOK, PEN, PLN, RSD, SEK, TRY, UAH, VEF, ZAR  
ETD-419 [pairs] Add new currencies 22/04.  
1ST, ACH, AE, AEON, ALPACA, ANY, APE, APPC, AR, ARN, ARRR, ASR, AST, ATLAS, AUTO, BAR, BAY, BC, BCD, BCHA, BCN, BEPRO, BIA, BSW, BUY, CFX, CHAT, CHESS, CLOAK, CMT, CND, CSX, CVC, CWAR, DCT, DEXE, DGD, DLT, DNXC, DPI, DUSK, EDO, EMC2, EPS, EQZ, EVX, FARM, FIS, FLM, FRAX, FTX, FUEL, GAME, GEO, GMT, GO, GVT, HARD, HC, HORD, HUSD, INS, ISP, KCS, KDA, LEND, LUN, LUSD, MCO, MDA, MDX, MONA, MORE, MTH, MXM, NAS, NCASH, NXT, OAX, OG, OK, OST, PAY, PHB, POA, POE, POLS, PPT, PTOY, QLC, QRL, QSP, QWARK, RAY, RCN, RDD, RIF, RNDR, ROOK, RUB, SANTOS, SNGLS, SNM, SNT, SOLR, SPELL, STOPELON, STORM, STPT, SUB, SUPER, TNT, TRIBE, TRY, TUBE, UNFI, USDN, VIB, VIBE, VIDT, VRC, WIN, WRX, XCP, XTZ, XYM, ZCL  
  
### Improvements  
ETD-430 [portfolio] Edit the appearance of the portfolio.  
ETD-418 [help] Exchanges logos update.  
ETD-416 [connectors] Renaming OKEX to OKX.  
ETD-283 [containers] Add Bitstamp CSV support for DEPOSIT and WITHDRAWAL transactions. (Re-import your CSVs)  
  
### Bug Fixes  
ETD-438 [connectors] Bitstamp API downloads duplicate DEPOSIT & WITHDRAWAL transactions. (Re-sync your APIs)  
ETD-432 [connectors] Binance API duplicates transactions. (Re-sync your APIs)  
ETD-431 [connectors] Binance API does'nt download DEPOSIT & WITHDRAWAL older than 90 days. (Re-sync your APIs)  
ETD-423 [connectors] Coinbase Pro API reads pending transactions. (Re-sync your APIs)  
ETD-422 [portfolio] DOP accounting currency doesn't work.  
ETD-417 [portfolio] Scroll bar in the chart & crypto positions.  
ETD-415 [connectors] Kraken API "EGeneral:Internal error". (Re-sync your APIs)  
ETD-414 [connectors] Coinbase API "Unable to acquire JDBC Connection". (Re-sync your APIs)  
ETD-192 [connectors] Coinbase Pro API fix for DEPOSIT & WITHDRAWAL transaction downloads. (Re-sync your APIs)  
   
## Version 2022-04-01T0824   
### Improvements   
ETD-407 [reports] Third-party fee in reports and portfolio calculation.   
ETD-404 [containers] Enable third currency fee on CSV import.   
ETD-402 [reports] Delete lines in the report where 0 appears in all columns.   
   
## Version 2022-03-30T1523   
### Improvements   
**Please follow the instructions in the newsletter on how to properly migrate to the new features.**   
ETD-405 [account] Exclude all FEE transactions from the transaction limit by subscription type.   
ETD-397 [pairs] Extending the list of cryptocurrency pairs in BASE with QUOTE /BUSD, /USDT, /USDC, /DAI, /XRP. (We recommend re-synchronizing the API connectors or re-importing the CSV files. For API connectors with downloaded pairs, add new pairs.)   
ETD-390 [portfolio] Copying balances reflect DEPOSIT and WITHDRAWAL transactions. (We recommend deleting the portfolio balances and reloading them from the previous period.)   
ETD-394 [connectors] Optimizing the mobile API connector interface.   
ETD-391 [portfolio] Account sorting in balance copying.   
ETD-346 [connectors] Kraken API optimization "EAPI:Rate limit exceeded" + download address from DEPOSIT & WITHDRAWAL transactions. (Operation of overloaded connectors will be automatically bypassed.)   
ETD-286 [accounts] Quick account switching. (From the account details.)   
   
## Version 2022-03-29T1209   
### New Features   
**Please follow the instructions in the newsletter on how to properly migrate to the new features.**   
ETD-398 [portfolio] Switch to convert traded pairs to accounting currency.   
ETD-396 [connectors] Allow Binance API & CSV to load a fee in a third trade currency.   
ETD-392 [transactions] Third currency trade FEE transactions.   
ETD-305 [transactions] Last used pairs.   
   
### Improvements   
ETD-401 [help] EveryTrade CSV 3.1.1 specification expanded to include third currency fees.      
   
## Version 2022-03-24T0856   
### Improvements   
ETD-400 [reports] Amount of fee in the currency of the trade.   
ETD-399 [reports] Rename transactions of initial balance as opening balance. Originally Deposit.   
ETD-370 [connectors] Bittrex API v3 support - correct reporting of API invalid key to the log.   
   
### Bug Fixes   
Minor improvements and corrections to changes in the previous release.   
ETD-357 [portfolio] Invalid value for EpochDay - Error when copying FIFO portfolio balances.   
   
## Version 2022-03-22T1454   
### New Features   
ETD-329 [pairs] Convert pairs to accounting currency. (Requires manual activation in portfolio settings. More information in the newsletter.)   
ETD-310 [portfolio] Last used portfolio.   
   
### Improvements   
ETD-370 [connectors] Bittrex API v3 support.   
ETD-96 [pairs] Closing crypto positions.   
   
### Bug Fixes   
ETD-389 [transactions] Division 0 in transaction detail.   
ETD-387 [transactions] Transaction filter is active but shows no entries.   
ETD-358 [fee] Under portfolio the sell fee not recognized.   
ETD-328 [reports] Incorrect currency and quantity is displayed for deposits and withdrawals in one of the reports.   
ETD-327 [portfolio] Your Fiat assets are ignoring deposits and withdrawals.   
   
## Version 2022-03-11T1058   
### Improvements   
ETD-341 [transactions] Improved control of the mobile transaction statement.   
   
### Bug Fixes   
ETD-383 [connectors] Transaction count flashes when resynchronizing the connector.   
   
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
ETD-297 [pairs] Kraken CSV import symbol XDG as DOGE.   
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
