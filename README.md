# Desafio Clase 47: Servidor en Deno

### Para usar en local ejecutar:

``` deno run --allow-net server.ts ``` --- o --- ``` denon run --allow-net server.ts ```

### Para probar, se puede usar Thunder Client o Postman  importando el archivo: ``` collection_deno-sample.json ```

* Luego de importar hay dos endpoints: 
  -> GET llamado `getColores` que trae una lista de colores almacenados en LocalStorage
  -> POST llamado `postColor` donde se le pasa por body un color para guardar en localStorage.