# Cedar Design

An editorial studio website built with React, TypeScript, Vite, and Motion.

## Development

```sh
npm ci
npm run dev
```

## Production

```sh
npm run build
npm run preview
```

The static production site is generated in `dist/`. Project views use hash-based navigation and support browser history without server rewrites. Photography is served by Unsplash and fonts by Google Fonts, with system font fallbacks. The three case studies are clearly labeled concepts. The contact action uses `hello@cedar.design`; confirm this address before public launch.

Motion respects the system reduced-motion preference. Mobile navigation, process accordions, project stories, and contact links are implemented. Build validation is separate from browser-based visual and interaction testing.
