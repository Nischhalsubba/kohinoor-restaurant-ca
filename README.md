# Kohinoor Restaurant CA

A retained concept repository for a restaurant website project.

## Current repository state

The current branch contains project documentation, a repository thumbnail, and the license. It does **not** contain the static HTML/CSS/JavaScript implementation described by the historical project notes, so it should not be presented as a runnable restaurant website or a deployed business property until source code is restored or rebuilt.

## Repository structure

```text
kohinoor-restaurant-ca/
├── docs/
│   ├── assets/
│   │   └── kohinoor-restaurant-thumbnail.svg
│   └── REPOSITORY_OVERVIEW.md
├── LICENSE
└── README.md
```

## Business-data requirements

Any future implementation must verify restaurant information with the business before publication, including:

- restaurant name and address;
- map location;
- phone number and email;
- opening hours;
- menu items and prices;
- taxes and allergen information;
- reservation details;
- ordering links and availability.

Treat unverified content as conceptual. Do not invent reviews, awards, menu prices, opening hours, customer outcomes, or real-time availability.

## Future implementation guidance

For a small static restaurant site, keep the source structure proportional to the project:

```text
src/
├── index.html
├── styles/
│   └── main.css
├── scripts/
│   └── main.js
└── assets/
    ├── images/
    └── icons/
```

Add additional folders only when real pages, modules, or data require them.

Menu information should remain accessible as HTML rather than image-only text. Mobile users should have obvious access to call, map, menu, reservation, and ordering actions. Reservation forms must make clear whether a booking is confirmed or merely requested, and the site must not imply live table availability without a real booking integration.

## Source documentation standard

When runtime code is introduced:

- start every authored HTML, CSS, and JavaScript file with a concise human-readable description of its purpose and responsibilities;
- document meaningful functions with their purpose, important inputs and outputs, side effects, and non-obvious assumptions;
- keep comments focused on intent and constraints rather than repeating syntax.

## Verification before launch

1. Load all pages and assets without console or network errors.
2. Test menu navigation, gallery, map, phone, reservation, and ordering links.
3. Check narrow mobile layouts and touch targets.
4. Review keyboard focus, color contrast, and image alternatives.
5. Validate metadata and any structured data.
6. Confirm photography ownership and permission.
7. Confirm every published business detail with the owner.

The repository thumbnail under `docs/assets/` is a concept asset, not a browser screenshot.

## License

See [LICENSE](./LICENSE) for license terms.
