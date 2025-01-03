# juletrade (Julia E-Trade API Wrapper)

**juletrade** is a Julia package that connects to the E-Trade API. It is designed to be fast and simple.

## What It Does

- **Get Set Up**: Authenticate with OAuth to access your E-Trade account.
- **Keep Tabs on Your Accounts**: Check balances, portfolios, and transactions.
- **Make Trades**: Place, preview, modify, or cancel orders for stocks and options.
- **Track the Market**: Fetch quotes, option chains, and other market data.

## How to Install

The easiest way to get juletrade is through Julia’s package manager:

```julia
using Pkg
Pkg.add("juletrade")
