# The Regulation Receipt (prototype)

A Consumer Choice Center tool that shows what state and local government adds to a normal month's shopping in the largest city of each of the 50 states.

**Status:** draft prototype for internal review. Not for publication until data review is complete.

## Data

All rates are embedded in `index.html` (the `DATA` array). Sources:

- City combined sales tax: Avalara city rate pages, retrieved September 24, 2026
- State sales tax: Tax Foundation, State and Local Sales Tax Rates, Midyear 2026
- Gasoline: Tax Foundation, Gas Taxes by State, July 2026
- Wireless: Tax Foundation, Taxes on Wireless Services, 2025
- Beer: Tax Foundation, Beer Taxes by State, January 1, 2026
- Cigarettes: Tax Foundation, Cigarette Taxes by State, July 2026; local cigarette taxes from Campaign for Tobacco-Free Kids, December 2025
- Vaping: Tax Foundation, Vaping Taxes by State, 2026

## Known gaps before launch

1. Local grocery taxes are not yet included for 15 cities (marked ◇ in the tool).
2. Local fuel and meals taxes are not included.
3. Wireless data is the July 2025 edition.
4. Excise lines exclude the general sales tax on those items.
5. Official CCC logo assets still need to be added.
