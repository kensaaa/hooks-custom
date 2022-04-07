# Hook - useCounter

counter   :  variable, me entrega el valor actual del counter  
increment :  funcion, aumenta en 1 el counter  
decrement :  funcion, resta en 1 el counter  
reset     :  funcion, establece el counter al valor inicial  

## Maneras de llamar al Hook

1. Estableciendo un valor inicial 
```javascript
// el counter toma el valor de 12
const { counter, increment, decrement, reset } = useCounter(12)
```

2. Por defecto
```javascript
 // el counter toma el valor de 1 
const { counter, increment, decrement, reset } = useCounter(12)
```
