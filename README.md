# vue-test-code

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

Expected Output :
![expected](./src/assets/Expected.png)

penjelasan embetulan
setData(data) {
      this.$store.dispatch("setDatas", data) 
      
},

state: {
    lists: null
  },

// memanggil setDatas karena action yang di deklarasikan pada store adalah setDatas;
    // return set state "list" -> seharusnya "lists"
    
    // 

context.commit('SET_DATA', data)
// seharusnya SET_DATA buka "setData" karena Mutation yang untuk set state list berupa string "SET_DATA" 
     