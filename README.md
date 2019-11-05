# v-datatable-issue
This repository illustrates an issue (or confusion on my part) related to 
refreshing the data in a v-datatable.

## Issue Description
### Setup (See HelloWorld.vue component)
1. Create a single file component with a scoped style 
1. have a conditional style applied to each row
1. initialize the data to be an empty array.
1. populate the data 
### Expected Behavior
Each row should have the style applied
### Actual Behavior 
The first row is missing the style.  
The class is applied successfully, but the data-v-xxxx class is missing from the first row. 
  

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn run serve
```

### Compiles and minifies for production
```
yarn run build
```

### Run your tests
```
yarn run test
```

### Lints and fixes files
```
yarn run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
