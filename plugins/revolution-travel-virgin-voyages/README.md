# Revolution Travel: Virgin Voyages pricing (Claude plugin)

Connects Claude to Revolution Travel's live Virgin Voyages pricing, a public remote MCP server
(Streamable HTTP, no authentication): `https://virginvoyages.revolutiontravel.ca/api/mcp`

## Install

In Claude Code:

```
/plugin install revolution-travel-virgin-voyages --marketplace RevolutionTravelGroup/virgin-voyages-claude-plugin
```

In Claude (web or desktop), you can also add the server directly: Settings, then Connectors, then Add custom connector, with the URL `https://virginvoyages.revolutiontravel.ca/api/mcp`.

## Tools (read-only)
- `find_voyages`: search upcoming sailings by region, ship, port, dates, length, cabin type or budget
- `get_voyage_pricing`: every cabin type on one sailing, total for two in CAD with taxes, Bar Tab and Agency Loot
- `get_current_offers`: Virgin Voyages offers in effect and how Agency Loot works

## Skill
`virgin-voyages-quote` formats answers in Revolution Travel's standard quote layout.

## Example prompts
- "Find a Virgin Voyages Caribbean cruise in March with a balcony for two"
- "Price the Sea Terrace cabins on voyage RS2701106NMGO"
- "Which Virgin Voyages offers are in effect right now?"

## Data
Prices come from Virgin Voyages' live agency fare files (refreshed daily) and are subject to availability until booked.
Revolution Travel is a Canadian travel agency selling Virgin Voyages; it is not Virgin Voyages.

Support: https://virginvoyages.revolutiontravel.ca/support · Privacy: https://virginvoyages.revolutiontravel.ca/privacy
