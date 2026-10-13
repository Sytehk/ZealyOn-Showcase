# ZealyOn

**Discover, compare, and follow crypto and forex strategies**

ZealyOn is a strategy app that helps people examine rule-based crypto and forex strategies, compare their records, and follow their signals. People can explore strategies without connecting a trading account, then choose alerts or a supported connection to their own broker or exchange.

## Main product areas

- **Dashboard:** overview and shortcuts into the main workspaces.
- **Discover:** request a search using criteria such as market, timeframe, and risk or performance limits, then review matching candidates.
- **Strategy Hub:** browse, filter, compare, and inspect strategy records, available analysis, and account activity.
- **More:** manage account settings, notifications, referrals, security, and support.

## Strategy records and signals

ZealyOn presents different kinds of results with distinct labels, including historical backtests, forward-tracked strategy records, Demo activity, and a user's own connected-account history. These records have different sources and should not be treated as interchangeable. Past performance does not guarantee future results.

Alerts and supported External Live execution use signals from the same strategy engine. Alerts can be delivered through configured Telegram or Discord destinations. When users connect External Live, orders go to their own supported account. ZealyOn does not hold their trading funds and does not provide personalized financial advice.

## Engineering scope

The product combines Flutter mobile and desktop clients, web experiences, Rust strategy services, and account-provider integrations. Supabase and PostgreSQL support application data and account workflows. The product keeps shared strategy activity separate from each user's account and execution route.

## Technology

Flutter and Dart, Rust, Supabase, PostgreSQL, market-data and account-provider integrations.

## About this repository

This is a documentation-only public showcase. It describes the product without publishing private implementation code, proprietary strategy rules, credentials, customer information, or operational configuration.

[Explore AceNetics](https://acenetics.dev)
