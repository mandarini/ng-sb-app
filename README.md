## Steps ran

```
ng new my-app
cd my-app
npx sb@latest init
```

and added targets in `angular.json` as per the [docs](https://storybook.js.org/docs/angular/get-started/install)

## using ng run

```
ng run sbngts:build-storybook
```

or

```
ng run sbngts:storybook
```

you get

```
ERR! Module not found: Error: Can't resolve '/Users/katerina/Projects/nrwl/test_nx_workspaces/sbngts/storybook-init-framework-entry.js' in '/Users/katerina/Projects/nrwl/test_nx_workspaces/sbngts'
```

## using yarn

```
yarn storybook
```

you get

```
ModuleNotFoundError: Module not found: Error: Can't resolve '/Users/katerina/Projects/nrwl/test_nx_workspaces/sbngts/.storybook/preview.js-generated-config-entry.js' in '/Users/katerina/Projects/nrwl/test_nx_workspaces/sbngts'
```
