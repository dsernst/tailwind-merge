<div align="center">
    <br />
    <a href="https://github.com/dcastil/tailwind-merge">
        <img src="https://github.com/dcastil/tailwind-merge/raw/v1.12.0/assets/logo.svg" alt="tailwind-merge" height="150px" />
    </a>
</div>

# tailwind-merge

Utility function to efficiently merge [Tailwind CSS](https://tailwindcss.com) classes in JS without style conflicts.

```ts
import { twMerge } from 'tailwind-merge'

twMerge('px-2 py-1 bg-red hover:bg-dark-red', 'p-3 bg-[#B91C1C]')
// → 'hover:bg-dark-red p-3 bg-[#B91C1C]'
```

-   Supports Tailwind v3.0 up to v3.3 (if you use Tailwind v2, use [tailwind-merge v0.9.0](https://github.com/dcastil/tailwind-merge/tree/v0.9.0))
-   Works in all modern browsers and Node >=12
-   Fully typed
-   [Check bundle size on Bundlephobia](https://bundlephobia.com/package/tailwind-merge)

## Get started

-   [What is it for](https://github.com/dcastil/tailwind-merge/tree/v1.12.0/docs/what-is-it-for.md)
-   [Features](https://github.com/dcastil/tailwind-merge/tree/v1.12.0/docs/features.md)
-   [Configuration](https://github.com/dcastil/tailwind-merge/tree/v1.12.0/docs/configuration.md)
-   [Recipes](https://github.com/dcastil/tailwind-merge/tree/v1.12.0/docs/recipes.md)
-   [API reference](https://github.com/dcastil/tailwind-merge/tree/v1.12.0/docs/api-reference.md)
-   [Writing plugins](https://github.com/dcastil/tailwind-merge/tree/v1.12.0/docs/writing-plugins.md)
-   [Versioning](https://github.com/dcastil/tailwind-merge/tree/v1.12.0/docs/versioning.md)
-   [Contributing](https://github.com/dcastil/tailwind-merge/tree/v1.12.0/docs/contributing.md)
-   [Similar packages](https://github.com/dcastil/tailwind-merge/tree/v1.12.0/docs/similar-packages.md)
