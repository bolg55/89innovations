# Instructions to get started with the project

This starter project is meant to be cloned and re-used when starting new web development projects. It includes a basic setup for a web project with the following features:

> [!IMPORTANT]
> Remember to update the `site` property in the `astro.config.mjs` file with your site's url. This is important for SEO purposes.

## Components

- Navbar component with mobile responsiveness
- Footer component
- Link/Button component
- Social media icons
- SEO component
- Logo component

## Data

- Populate the footer with data inside the `data/footerData.ts` file
- Populate the navbar with data inside the `data/menuItems.ts` file
- Populate general SEO data inside the `data/siteData.json` file. This data will be used to populate the SEO component, and the jsonLD generator.
- Make a `.env` file based on the example; fill out your social media and site info. This data will be used to generate the jsonLD for the website, as well as SEO, and for the footer icons in `components/ui/footer-icons.astro`.

> [!WARNING]
> The jsonLD file does not have linting enabled, so make sure to follow the correct format when adding data.

The current template should work, but you can add more data if needed. Use the [Google Structured Data Testing Tool](https://search.google.com/structured-data/testing-tool) to validate the jsonLD.

## Styles

- The project uses Tailwind for styling. Add your brand colors and fonts to the `tailwind.config.mjs` file. Example colors and fonts are already included.
- The project uses fontsource for fonts, as recommended by Astro in their documentation.

## Pages

- Index page just to show the navbar and footer
- (Coming soon) Contact page with submission form
- (Coming soon) Blog page with markdown support and pagination
- (Coming soon) Sample blog posts
