# G. V. Sunder — Next.js Website

## Requirements

- Node.js 20+ recommended
- npm

## Run locally

```bash
npm install
npm run dev
```

Open http://localhost:3000

## Production build

```bash
npm run build
npm run start
```

## Replace before publication

1. Replace `public/images/candidate.svg` with an appropriately licensed portrait.
2. Replace `public/images/meeting-01.svg` with an appropriately licensed photograph.
3. Replace placeholder contact details.
4. Replace placeholder event/media information with verified information.
5. Connect the public-contact form to a secure server-side endpoint.
6. Add the applicable privacy, consent, data-retention and election/campaign disclosures.
7. Verify all public claims, dates, constituency information and social-media accounts.

## Language

English/Telugu strings are in:

- `content/en.ts`
- `content/te.ts`

The header demonstrates the language-switching architecture. Extend the same content pattern to all sections for a complete bilingual site.

## Notes

The supplied form is intentionally frontend-only. Do not collect real personal information until a secure backend, validation, rate limiting, spam controls, consent and appropriate storage/retention controls are implemented.
