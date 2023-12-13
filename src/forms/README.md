# /forms

Folder containing all forms

### Generating from the CLI
All forms should be generated from the command line with `generate-react-cli`.

*See the `README.md` file in the `/teamplats` directory for detailed instructions.

You can use the following command to create a component

```bash
npx generate-react-cli component --type=form <FormName>
```

## Form Architecture

```
+-- <FormName>
|  |-- <FormName>.txs
|  |-- <FormName>.d.ts (optional)
|  |-- <FormName>.module.scss
|  |-- <FormName>.spec.jsx
|  |-- README.md
|  |-- index.ts
```
