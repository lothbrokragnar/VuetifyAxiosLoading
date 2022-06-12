# axios-vuetify

Se realiza el deploy en netlify. https://heartfelt-baklava-70f677.netlify.app/

App que se desarrolla con Vuetify y Axios, para consumir el valor del dolar de la api https://mindicador.cl/api/dolar Utilizando los componentes de Vuetify como el Grid System y un template de calendario, configurando las fechas y las vistas en es-cl. Incluye validaciones, como una fecha mínima y la fecha máxima, la cual no puede ser superior a la actual. En el caso que se consulte una fecha que sea un sabádo o domingo, entrega un mensaje "Sin resultados", en caso contrario trae la información del valor del dolar para dicha fecha consultada.
Se agrega el componente loading, para que mientras carga la información, aparezca un mensaje emergente que dice "Accediendo a información"

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
