# Repository Instructions

## Setup

Serve the static site after confirming its entry HTML file:

```bash
python -m http.server 8000
```

## Business-data rules

- Verify restaurant name, address, map, phone, email, hours, menu, prices, taxes, allergens, and reservation details before publishing.
- Treat current content as conceptual until confirmed by the business.
- Keep menu information accessible as HTML rather than image-only text.
- Record photography ownership and permission.
- Add Restaurant structured data only with accurate public information.

## Interaction rules

- Make call, map, reservation, ordering, and menu actions obvious on mobile.
- Keep forms labeled and disclose whether a booking is confirmed or only requested.
- Do not imply real-time table availability without an integrated booking service.
- Keep essential information available without animation.

## Verification

1. Load all pages and assets.
2. Test menu navigation, gallery, map, phone, reservation, and ordering links.
3. Check narrow mobile layouts and touch targets.
4. Review keyboard focus, contrast, and alt text.
5. Validate metadata and structured data.
6. Confirm every business detail with the owner before launch.

## Do not

- Do not invent reviews, awards, menu prices, or opening hours.
- Do not publish unlicensed food photography.
- Do not call a reservation request confirmed unless a backend confirms it.
- Do not present the repository thumbnail as a browser screenshot.