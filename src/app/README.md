# /app

folder containing all the pages

## folder structure and naming conventions

Folder structure should match exactly the names of the routes of the app.  This eliminates ambiguity for what belongs to 
what page.

## Page Architecture

### /page-name

File name should match the route.

### /__snapshots__

Auto generate snapshots used for testing.  

### /components

Items should only be placed in this folder if they are specific to this page and not used elsewhere in the app.  Always
opt to use components from the component lib where you can.

### /hooks

Items should only be placed in this folder if they are specific to this page and not used elsewhere in the app.  Always
opt to use components from the component lib where you can.

```
+--+ <page-name>
|  |--+ __snapshots__
|  |  |-- <page-name>.test.tsx.snap
|  |--+ components
|  |  |--+ <ComponentName>
|  |  |  |-- <ComponentName>.tsx
|  |--+ hooks
|  |  |--+ use<HookName>
|  |  |  |-- use<HookName>.tsx
|  |-- <page-name>.txs
|  |-- <page-name>.module.scss
|  |-- <page-name>.spec.jsx
```

## Page Architecture (NextJS)

See https://nextjs.org/docs/pages/building-your-application/routing

```
+-- <page-name>
|  |--+ __snapshots__
|  |  |-- <page-name>.test.tsx.snap
|  |-- page.txs
|  |-- error.txs
|  |-- layout.txs
|  |-- loading.txs
|  |-- <page-name>.module.scss
|  |-- <page-name>.spec.jsx
```