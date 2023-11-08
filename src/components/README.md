# /components

Folder containing all reusable components.  If the component can/will/should be used in more than one location
it should go in this folder.

Components that are specific to a single page should be in a `/_components` folder in the page directory.  

## Creating a new component

### Naming components

### Storybook First approach

### Generating from the CLI
All components should be generated from the command line with `generate-react-cli`.

*See the `README.md` file in the `/teamplats` directory for detailed instructions on how to build a component from the CLI.

You can use the following command to create a component

```bash
npx generate-react-cli component <Component Name>
```

## Component Architecture

```
+-- <ComponentName>
|  |-- <ComponentName>.txs
|  |-- <ComponentName>.module.scss
|  |-- <ComponentName>.stories.tsx
|  |-- <ComponentName>.spec.jsx
|  |-- README.md
|  |-- index.ts
```
