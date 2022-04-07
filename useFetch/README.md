# Hook - useFetch

dependencias:
    - url a la que se hara la peticion
---

data : me entrega los datos de la peticion, por defecto es null
loading : esta en false cuando tengo los datos, en caso contrario en true
error: cuando existe un error se guarda aqui, en caso contrario es null

## Llamando al hook
```javascript
const { data, loading, error } = useFetch(url)
```
