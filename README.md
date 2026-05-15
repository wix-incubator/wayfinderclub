# Wayfinder Club

Wayfinder Club is a travel club onboarding site for expedition registration, attendee details, structured submissions, validation, and success routing.

This website is powered by Wix Headless and built using [wix-headless.dev](https://www.wix-headless.dev).

## Links

- Live site: [https://wayfinder-4d3d233d-gonenj.wix-site-host.com](https://wayfinder-4d3d233d-gonenj.wix-site-host.com)
- Source: [https://github.com/wix-incubator/wayfinderclub](https://github.com/wix-incubator/wayfinderclub)
- Wix site ID: `fa2f4252-81e5-4f1d-a826-36a4935dcfa7`

## What It Showcases

- A custom Astro travel onboarding flow backed by Wix Forms.
- Wix-hosted form schema loading with custom expedition UI rendering.
- Traveler details submitted through Wix Headless APIs.
- Branded confirmation routing after submission.
- Public `robots.txt` and `llms.txt` configured through Wix SEO txt APIs.
- Deployment with `wix release`.

## Wix Solutions Used

- Wix Headless Site for the managed site/runtime foundation.
- Wix Forms for travel club onboarding fields and submissions.

## Wix SDKs And Packages

- `@wix/astro`
- `@wix/astro-pages`
- `@wix/sdk`
- `@wix/forms`

## Local Development

Create a local env file from `.env.example` or run the Wix CLI env setup for the connected site.

```bash
npm install
npm run dev
```

## Build And Release

```bash
npm run build
npm run release
```
