# 🗺️ Domain Map

A fast, searchable reference for all 1,200+ ICANN-registered top-level domains (TLDs) — including origin, type, and pricing from German hosting providers.

## Features

- **1,286 TLDs** directly from the IANA Root Zone Database (updated June 2026)
- Filter by type: gTLD, ccTLD, Brand
- Search by TLD name or country of origin
- Paginated table (50 per page) for smooth performance
- Price comparison for selected TLDs across German hosting providers
- Curated "cool TLD" combinations with example domains
- Dark mode support

## Tech Stack

- [React](https://react.dev/) + [Vite](https://vitejs.dev/)
- No external dependencies beyond React itself
- Deployed via GitHub Pages

## Getting Started

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build
```

## Data Source

TLD data sourced from the official [IANA Root Zone Database](https://data.iana.org/TLD/tlds-alpha-by-domain.txt).

Pricing data from [prepaid-host.com](https://prepaid-host.com/domain/order) (verified June 2026, incl. 19% VAT).

## License

MIT
