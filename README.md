# eslint-config-premisehealth

Shareable ESLint config for Premise Health node projects. To use in your project, add `eslint-config-premisehealth` and [`eslint-plugin-premisehealth`](https://bitbucket.org/path/to/this/repo) to your `package.json`, then in your ESLint configuration add:

```
{
  "extends": "eslint-config-premisehealth"
}
```

ESLint will automatically insert the `eslint-config-`, so technically, you can just write `"extends": "premisehealth"`.

**Note:** `eslint-plugin-premisehealth` is a plugin containing custom Premise Health linting rules. It is a peer dependency because of the way ESLint handles shareable configs that include plugins and custom rules (see [eslint/eslint#3458](https://github.com/eslint/eslint/issues/3458) and [eslint/eslint#2518](https://github.com/eslint/eslint/issues/2518) for more background).
