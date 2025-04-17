# work-well-landing

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) to make the TypeScript language service aware of `.vue` types.

## Customize configuration

See [Vite Configuration Reference](https://vite.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Run End-to-End Tests with [Playwright](https://playwright.dev)

```sh
# Install browsers for the first run
npx playwright install

# When testing on CI, must build the project first
npm run build

# Runs the end-to-end tests
npm run test:e2e
# Runs the tests only on Chromium
npm run test:e2e -- --project=chromium
# Runs the tests of a specific file
npm run test:e2e -- tests/example.spec.ts
# Runs the tests in debug mode
npm run test:e2e -- --debug
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```

# Deployment

## Deploying with Netlify

* Install Netlify CLI
```sh
npm install netlify-cli -g
```

Initialize a new Netlify site
```sh
ntl init
```

Build the project
```sh
npm run build
```

Deploy the project
```sh
netlify deploy --prod --dir=dist
```

# Color Palette
Usage	Hex Code	Sample	Notes
Page Background	#ffffff / #f7f9fa		Clean and light, keeps design spacious and readable
Body Text	#2e2e2e		Deep gray for high readability on light background
Headings	#045fa2		Strong deep blue; establishes trust and structure
Hero Background	#1aa3a7		Bright, optimistic teal — adds vibrance
Hero Text	#ffffff		White on teal ensures high contrast
Primary CTA Button	#045fa2		Deep blue for strong call-to-action
CTA Hover	#0460a3		Slight variation adds feedback without clashing
Links / Accent Items	#1aa4a7		Teal as a secondary action or detail element
Section Background (Alt)	#f7f9fa		Light neutral to break up sections
Border / Divider	#045fa3		Optional darker blue for thin separators or icons

# Illustration Ideas

Section, Suggested Keywords

Hero, teamwork, consulting, office, business meeting, HR services, teamwork, consultation, business growth

Services, onboarding, payroll, resume, job interview, compliance, interview, hiring, payroll, onboarding, compliance

Why Choose Us, business growth, success, partnership, collaboration, teamwork, business growth, partnership, collaboration, trust, success, partnership, expertise, performance

Testimonials, conversation, review, client, feedback, feedback, review, support, happy clients

Contact/About, customer support, handshake, business communication, conversation, reach out, email support, business communication


# Vector Arts Libraries

* [unDraw](https://undraw.co/): A constantly updated collection of beautiful svg images that you can use completely free and without attribution. You can use them in your marketing, business presentations, educational materials, websites, and anywhere else you need illustrations.
* [storyset](https://storyset.com/illustration/asian-family/rafiki)
* [Manypixels](https://www.manypixels.co/gallery)
* [drawkit](https://www.drawkit.com/illustration-types/2d?page=3)
* [svgrepo](https://www.svgrepo.com)
