# Taxonomy

An open source application built using the new router, server components and everything new in Next.js 13.

> **Warning**
> This app is a work in progress. I'm building this in public. You can follow the progress
> See the roadmap below.

## Demo

![screenshot-2](https://user-images.githubusercontent.com/124599/198038921-2b16b18b-cb4d-44b1-bd1d-6419d4a8d92c.png)

## About this project

Right now, I'm using this project as an experiment to see how a modern app (with features like authentication, subscriptions, API routes, static pages for docs ...etc) would work in Next.js 13 and server components.

I'll be posting updates and issues here.

A few people have asked me to turn this into a starter. I think we could do that once the new features are out of beta.

## Note on Performance

> **Warning**
> This app is using the canary releases for Next.js 13 and React 18. The new router and app dir is still in beta and not production-ready.
> NextAuth.js, which is used for authentication, is also not fully supported in Next.js 13 and RSC.
> **Expect some performance hits when testing the dashboard**.
> If you see something broken, you can ping me

## Features

- New `/app` dir,
- Routing, Layouts, Nested Layouts and Layout Groups
- Data Fetching, Caching and Mutation
- Loading UI
- Server and Client Components
- API Routes and Middlewares
- Authentication using **NextAuth.js**
- ORM using **Prisma**
- Database on **PlanetScale**
- UI Components built using **Radix UI**
- Documentation and blog using **MDX** and **Contentlayer**
- Subscriptions using **Stripe**
- Styled using **Tailwind CSS**
- Validations using **Zod**
- Written in **TypeScript**

## Roadmap

- [x] ~Add MDX support for basic pages~
- [x] ~Build marketing pages~
- [x] ~Subscriptions using Stripe~
- [x] ~Responsive styles~
- [x] ~Add OG image for blog using @vercel/og~
- [ ] Add tests
- [ ] Dark mode



## Why not tRPC, Turborepo or X?

I might add this later. For now, I want to see how far we can get using Next.js only.

If you have some suggestions, feel free to create an issue.

## Running Locally

1. Install dependencies using pnpm:

```sh
pnpm install
```

2. Copy `.env.example` to `.env.local` and update the variables.

```sh
cp .env.example .env.local
```

3. Start the development server:

```sh
pnpm dev
```

## License

Licensed under the [MIT license](https://github.com/shadcn/taxonomy/blob/main/LICENSE.md).
