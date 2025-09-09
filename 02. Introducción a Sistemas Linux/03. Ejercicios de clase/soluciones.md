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

## Ejercicio 5 – Primeras líneas
```
cat log.txt | head -5
```

## Ejercicio 6 – Últimas líneas
```
cat log.txt | tail -3 > ultimos.txt
```

## Ejercicio 7 – Combinando comandos
```
awk '{ print length, $0 }' documento.txt | sort -nr | head -n 2 | cut -d" " -f2-
```