# next-netlify-twin-ts

## Getting Started

Install the [Netlify CLI](https://github.com/netlify/cli) globally:

```bash
npm i -g netlify-cli
```

Run the development server:

```bash
ntl dev
```

The [tsconfig](tsconfig.json) is automatically setup with paths to the following common folders:

- `@components/*`
- `@constants/*`
- `@hooks/*`
- `@models/*`
- `@utils/*`

Your browser will automatically open [http://localhost:8888](http://localhost:8888).

## API Routes

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:8888/api/hello](http://localhost:8888/api/hello). This endpoint can be edited in `src/pages/api/hello.ts`.

The `src/pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!
