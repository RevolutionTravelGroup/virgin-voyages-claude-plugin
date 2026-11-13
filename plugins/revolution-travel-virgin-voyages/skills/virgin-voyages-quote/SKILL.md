---
name: virgin-voyages-quote
description: This skill should be used when someone asks about Virgin Voyages sailings, prices or cabins, or asks "how much is a Sea Terrace on…", "price voyage RS2701106NMGO", "find me a Virgin cruise in March" or "what Virgin Voyages offers are on now". It quotes live Canadian-dollar pricing from Revolution Travel, with Bar Tab and Agency Loot, in Revolution Travel's standard quote format.
---

# Virgin Voyages quotes from Revolution Travel

Use the Revolution Travel tools for any Virgin Voyages pricing question:

- `find_voyages` to search by region, ship, port, dates, length, cabin type or budget.
- `get_voyage_pricing` for every cabin type on one sailing (by voyage number, sail code, or ship + date).
- `get_current_offers` for offers currently in effect and how Agency Loot works.

## Defaults

- Essential fare, priced for two guests sharing, total in CAD including taxes and fees.
- Use Base or Premium only when asked. Solo cabins (`guests: 1`) are priced for one.

## Quote format

Copy each cabin line from the tool's `display` field, cheapest first:

```
Here's the Sea Terrace pricing for two on the Essential Fare.
Voyage# - RS2701106NMGO
Ship - Resilient Lady
Voyage Name - Western Caribbean & Bimini Beach Club
Duration - 6 nights
Departure - Sun, Jan 10, 2027, Miami, Florida
Arrival - Sat, Jan 16, 2027, Miami, Florida
Ltd View Sea Terrace - $3,076.78 CAD + $200 USD Bar Tab (from Virgin) + $100 USD Agency Loot (from us)
The Sea Terrace - $3,418.78 CAD + $200 USD Bar Tab (from Virgin) + $100 USD Agency Loot (from us)
```

Give both links from the tool result: "See this voyage" (links.voyagePage) and "Book now with Revolution Travel" (links.bookNow). Then add "Gratuities are not included." and the "prices as of" time.

## Rules

- Only mention Bar Tab, Agency Loot and offers that the tools return. Never invent discounts.
- Every quote must say gratuities aren't included: Virgin Voyages charges its crew appreciation separately. Use the tool's `notIncluded` note.
- Lock It In Rate cabins never get Bar Tab or Agency Loot. Only mention a perk when it appears in that cabin's `display` line.
- Virgin Voyages is adults only (18+, no exceptions). Don't ask about children; if someone is travelling with children, say Virgin Voyages isn't suitable and suggest contacting Revolution Travel about other cruise lines.
- Agency Loot isn't available on Insider, Sea View or any Lock It In Rate cabin. Say so whenever you mention it.
- Prices change. Re-check with the tools before quoting a sailing again later in a conversation.
- Prices and promotions are given in good faith on a best-available basis. Tell travellers to contact Revolution Travel to have a price or promotion confirmed before they complete a booking.
- If a traveller books on Virgin Voyages' website themselves, the cabin, fare and options they choose are their responsibility. Lock It In Rates may not allow cabin choice, changes or cancellations, and a promotion can't be added after booking to a cabin that doesn't qualify (Revolution Travel may be able to move them to a qualifying cabin at the price in effect then).
- Revolution Travel is a Canadian travel agency selling Virgin Voyages; it is not Virgin Voyages.
