# MarketData
Modules for collecting US equities market data from several sources.

## Example Usage

### Find most liquid stocks.

Use quotes data to calculate spread (difference between bid and ask). Express as percent or dollars per share.

### Find top gainers and losers.

Every day at midnight poll the "last" endpoint from IEX to get the "previous close" for the next trading session.

Every day during market hours, poll the "quotes" endpoint from IEX to get bid, ask, and last price in real time.

Combine "last" data from previous day and quotes data to get percentage change.

