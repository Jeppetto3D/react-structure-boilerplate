# generate-react-cli

This folder contains the templates for `generate-react-cli`. Read more here: [generate-react-cli](https://www.npmjs.com/package/generate-react-cli)

## Generate Component

The following command will generate a functional component in the `./src/components/` folder.

```bash
npx generate-react-cli component <Component Name>
```

### Config File
`./generate-react-cli.json`

### Component Types

| **Type**  | **--type=** | **Template src**       | **Notes**                          |
|-----------|-------------|------------------------|------------------------------------|
| Component | n/a         | ./templates/component/ | _Default_ Can leave `--type=` off. |
| Datagrid  | datagrid    | ./templates/datagrid/  |                                    |
| Form      | form        | ./templates/form/      |                                    |
| Layout    | layout      | ./templates/layout/    |                                    |
| Hook      | hook        | ./templates/hook/      |                                    |
| Service   | service     | ./templates/service/   |                                    |
| View/Page | view        | ./templates/view/      |                                    |

Examples with type flag

```bash
npx generate-react-cli component --type=datagrid GridName
npx generate-react-cli component --type=form FormName
npx generate-react-cli component --type=layout LayoutName
npx generate-react-cli component --type=hook HookName
npx generate-react-cli component --type=service ServiceName
npx generate-react-cli component --type=view ViewName
```
