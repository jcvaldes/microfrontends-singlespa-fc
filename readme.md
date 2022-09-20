## CLI para crear aplicaciones microfrontend

```
npx create-single-spa
```

## Material UI

https://mui.com/components/tabs/

### Aplicacion de angular

```
npx @angular/cli@14 new <APP_NAME>
yarn add @angular-builders/custom-webpack
ng add single-spa-angular
npm run serve:single-spa:footer
```

### Crear Root

npx create-single-spa
? Directory for new project root
? Select type to generate single-spa root config
? Which package manager do you want to use? yarn
? Will this project use Typescript? Yes
? Would you like to use single-spa Layout Engine Yes
? Organization name (can use letters, numbers, dash or underscore) mfe

Aplicacion react
npx create-single-spa
? Directory for new project navbar
? Select type to generate single-spa application / parcel
? Which framework do you want to use? react
? Which package manager do you want to use? yarn
? Will this project use Typescript? Yes
? Organization name (can use letters, numbers, dash or underscore) mfe
? Project name (can use letters, numbers, dash or underscore) navbar

## Crear aplicacion angular

https://single-spa.js.org/docs/ecosystem-angular

 npx create-single-spa
? Directory for new project . (aca no se pone nada sino crea 2 carpetas)
? Select type to generate single-spa application / parcel
? Which framework do you want to use? angular
? Project name (can use letters, numbers, dash or underscore) footer
? Would you like to add Angular routing? Yes
? Which stylesheet format would you like to use? SCSS [

```
yarn add -D @angular-builders/custom-webpack
```

En navbar

```
Deprecado
# yarn add @material-ui/core
```

yarn add react-swipeable-views

para styled components
yarn add @mui/material @mui/styled-engine-sc styled-components

sino emotion engine
yarn add @mui/material @emotion/react @emotion/styled

### Levantar el proyecto de react separado del root

```
npm run start:standalone
```

## Vue

```
npm install -g @vue/cli
npx create-single-spa --framework vue
```

### Levantar el proyecto de vue separado del root

`npm run serve:standalone`
