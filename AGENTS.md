> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Language

- This documentation is written entirely in **Dutch**. All page content, frontmatter (`title`, `description`), navigation labels in `docs.json`, and URL slugs are Dutch.
- Page slugs follow the Dutch app routes (for example `facturen/aanmaken`, `betalingen/sepa-incasso`).

## Style preferences

- Schrijf in vlot, natuurlijk, hedendaags Nederlands. Geen "vertaald-Engels".
- Gebruik de informele aanspreekvorm: "je/jij/jouw", nooit "u".
- Actieve schrijfstijl, korte zinnen, één gedachte per zin.
- Geen gedachtestreepjes (—). Gebruik komma's, haakjes of splits de zin.
- Koppen in zinskapitaal.
- App UI-labels vetgedrukt, in het Nederlands: klik op **Instellingen**.
- Bedragen in Nederlands formaat: €0,65 / €16,25. Schrijf "e-mail" en "btw".
- Mintlify-componentnamen blijven Engels; alleen de tekst erin is Nederlands.

## Content boundaries

- Document geen super-admin / systeembeheerfuncties (impersonatie, platformbeheer van organisaties).
- Document alleen functionaliteit die daadwerkelijk in de app bestaat.
