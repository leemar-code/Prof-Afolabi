# Professor Olugbemiga Samuel Afolabi — Academic Portfolio

Responsive academic portfolio built with React, Vite, Tailwind CSS and Lucide React.

## Run locally

Use Node.js 20.19+ (or 22.12+) and pnpm:

```bash
pnpm install
pnpm dev
```

Open the local address printed by Vite. To create a production build, run `pnpm build`; use `pnpm preview` to preview that build.

## Updating the portfolio

- Edit biography, education, academic appointments, interests, teaching, awards and engagement details in `src/data.js`.
- Add or update publications in the `publications` array in `src/data.js`. Publication filters are generated from the year and type values in that data.
- Add or update professional engagements in `src/consultancy.js`. Each entry holds the organization, project, dates, sector, role, scope, contribution and documented deliverables or impact note. The file also supplies the sector filters and homepage highlights.
- Replace the portrait files in `public/` to update the homepage and teaching imagery.
- Replace `public/olugbemiga-afolabi-cv.pdf` with the current CV and `public/olugbemiga-afolabi-publications.docx` with the full publication list.
- Update email and profile links in the `profile` object in `src/data.js`.

The contact form opens a pre-addressed email in the visitor’s configured mail application. It does not store or send messages through a server.

## Content notes

The featured publication section is a selected list. The consultancy portfolio is built from engagements described in the supplied CV. If a source entry does not specify a measurable outcome, the card identifies that gap for later updating. The supplied full publication record and CV are available as downloads. Professional awards and appointments are based on the source materials; add further details in `src/data.js` as they are confirmed.
