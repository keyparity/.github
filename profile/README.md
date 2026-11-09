# keyparity

Your code reads `STRIPE_KEY`. Your `.env.example` forgot it, and so did the repo's GitHub Secrets. You find out when the deploy fails.

**[keyparity](https://github.com/keyparity/keyparity)** checks that every environment variable your code uses is in `.env.example` and set as a GitHub secret, and flags the ones nothing uses. It reads secret names only, never values.

```sh
npx keyparity audit
```

New here? Look for issues labelled [good first issue](https://github.com/search?q=org%3Akeyparity+label%3A%22good+first+issue%22+state%3Aopen&type=issues). Each one says which files to change and what "done" looks like.
