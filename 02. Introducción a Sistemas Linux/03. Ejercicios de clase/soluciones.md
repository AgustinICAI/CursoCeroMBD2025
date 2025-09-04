## Ejercicio 1 – Contar líneas
```
cat texto.txt | wc -l > lineas.txt
wc -l < texto.txt > lineas.txt
```

## Ejercicio 2 – Filtrar palabras
```
cat texto.txt | grep -i error
```

## Ejercicio 3 – Contar ocurrencias
```
cat texto.txt | grep -i error | wc -l
```

## Ejercicio 4 – Ordenar y eliminar duplicados
```
sort < nombres.txt | uniq
```