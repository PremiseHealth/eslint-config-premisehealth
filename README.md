# eslint-config-premisehealth

## What is linting?
Linting is the process of running a program that will analyse code using rules we create for potential errors and stylistic consistency.

Shareable ESLint config for Premise Health node projects. To use in your project, add `eslint-config-premisehealth` to your `package.json`, then in your ESLint configuration add:

```
{
  "extends": "eslint-config-premisehealth"
}
```

ESLint will automatically insert the `eslint-config-`, so technically, you can just write `"extends": "premisehealth"`.

Test: `npm run test`

Develop: make changes to the lib/index.js file and update tests.

