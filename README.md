# Baseball Dating

A one-off joke made for a friend who thought tinder felt too much like collecting baseball cards and reading stats.

Check it out at http://frankballcard.surge.sh/

## How it's made

I used postcss to compile tailwindcss. Tailwind is overkill for something this small, but let me work quickly without having to worry about css files and modules

## Make your own

Change `index.html` and `css/base.css` (or add [tailwind](https://tailwindcss.com) classes to html elements)

Run Locally
```
npm i
npm run serve
```

Production build

```
npm build
```

[Surge](https://surge.sh) used to deploy quickly straight from the project