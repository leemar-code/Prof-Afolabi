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

- Edit biography, education, appointments, interests, teaching, awards and engagement details in `src/data.js`.
- Add or update publications in the `publications` array in `src/data.js`. Publication filters are generated from the year and type values in that data.
- Replace the portrait files in `public/` to update the homepage and teaching imagery.
- Replace `public/olugbemiga-afolabi-cv.pdf` with the current CV and `public/olugbemiga-afolabi-publications.docx` with the full publication list.
- Update email and profile links in the `profile` object in `src/data.js`.

The contact form opens a pre-addressed email in the visitor’s configured mail application. It does not store or send messages through a server.

## Content notes

The featured publication section is a selected list. The supplied full publication record and CV are available as downloads. Professional awards and appointments are based on the source materials; add further details in `src/data.js` as they are confirmed.
