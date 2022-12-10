# PokemonProyecto

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.0.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

================================================================================================================================================

### API REST 
Una API de REST, o API de RESTful, es una interfaz de programación de aplicaciones (API o API web) que se ajusta a los límites de la arquitectura REST y permite la interacción con los servicios web de RESTful. El informático Roy Fielding es el creador de la transferencia de estado representacional (REST).

Las API son conjuntos de definiciones y protocolos que se utilizan para diseñar e integrar el software de las aplicaciones.Suele considerarse como el contrato entre el proveedor de información y el usuario, donde se establece el contenido que se necesita por parte del consumidor (la llamada) y el que requiere el productor (la respuesta).Por ejemplo, el diseño de una API de servicio meteorológico podría requerir que el usuario escribiera un código postal y que el productor diera una respuesta en dos partes: la primera sería la temperatura máxima y la segunda, la mínima.

En otras palabras, las API le permiten interactuar con una computadora o un sistema para obtener datos o ejecutar una función, de manera que el sistema comprenda la solicitud y la cumpla. 

#### Fetch
Esta es un metodo del objeto en javascript llamado window, o sea que para utilizarlo no necesitamos instalar nada extra. Simplemente hacemos el llamado escribiendo fetch(url) y esto nos devuelve una promise con la respuesta. En el caso de hacer una petición http GET, el único parámetro obligatorio que recibe fetch es la URL.

####Axios
Axios por otro lado es una libreria de javascript . Hay que en importarla en nuestro proyecto por cdn o instalarla. Al igual que fetch, axios se basa en promises. Si vamos a hacer una petición GET, sólo debemos llamar al método desde axios agregandole ..get(url) :

##### POKE API CONSUMIDA

END POINTS
 https://pokeapi.co/api/v2/{endpoint}/

count:248
next:"https://pokeapi.co/api/v2/ability/?limit=20&offset=20"
previous:null
name:"stench"
url:"https://pokeapi.co/api/v2/ability/1/"

Se consumieron los nombres, estadisticas de poderes, descripcion, estado e imagenes de los 151 Pokemones de la primera generacion. 

###### SERVICIOS CREADOS
Una poke api con los 150 pokemones de la primera generacion desplegados en una lista, donde se puede apreciar su imagen, descripcion, estados, poderes, y estadistica la cual esta conformada por caracteristicas como Hp, Defense, attack, speed, entre otros valores. A su vez podras encontrar suel nombre de cada uno de ellos en japones. 

//Observable
import { Observable } from 'rxjs';
import { map, tap } from 'rxjs/operators';



