# Baseball NZ Player Registrations

A dashboard of Baseball New Zealand national membership registrations by club, month, tier and region, comparing each season with the one before.

## Files

- `index.html`: the dashboard
- `data.js`: the built-in data (2025/26 and 2026/27 GameDay Player Registration exports, loaded 14 Oct 2026)

## Monthly updates

Use **Upload monthly CSV** on the dashboard with the GameDay Player Registration export. The month and season come from the transaction dates. Uploading a month again replaces it.

Uploads are saved only in the browser that made them. To give everyone the same numbers, update `data.js` with the new months.

## Notes

- Hamilton Raiders are counted under WaiBOP.
- Each national membership fee transaction counts as one registered player.
