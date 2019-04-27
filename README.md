# gatsby-theme-typescript

This is a gatsby theme that enables users to automatically configure Typescript in their gatsby projects.

## Usage

```
yarn add gatsby-theme-typscript
```

And in your `gatsby-config.js` file: 

```
module.exports = {
  __experimentalThemes: [`gatsby-theme-typescript`]
}
```

Once you do that, you should be able to just go ahead writing TypeScript. 


## Tsconfig Options

```json
{
  "compilerOptions": {
    "allowJs": true,
    "allowSyntheticDefaultImports": true,
    "baseUrl": ".",
    "jsx": "react",
    "lib": ["dom", "esnext", "dom.iterable", "scripthost"],
    "module": "esnext",
    "moduleResolution": "node",
    "noEmit": true,
    "skipLibCheck": true,
    "target": "es6"
  }
}
```
