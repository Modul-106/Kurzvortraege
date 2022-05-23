# Kurzvortraege

## Vergleichsoperatoren

### `<` and `>`
Die beiden Vergleichsoperatoren `<` und `>` können dazu verwendet werden um 2 Werte nach ihrer Grösse miteinandern zu vergleichen. Kann man z.B. dazu verwenden um alle Prüfungen auszugeben welche eine Note haben die über 5 liegt.
``` 
SELECT * FROM exames WHERE grate > 5;
```
### `<=` and `>=`
Die Vergleichsoperatoren `<=` und `>=` können auch dazu verwendet werden um 2 Werte nach ihrer Grösse zu vergleichen. Der Unterschied besteht darin, dass `<=` auch den wert mit dem es vergleicht wird beinhaltet. Kann z.B. Dazu verwendet werden um  alle Noten zu bekommen welche grösser oder gleich als 5 sind. In diesem Beispiel würden im Ggensatz zum obrigen auch Prüfungen mit der Note 5 ausgegeben werden.
```
SELECT * FROM exames WHERE grate >= 5;
```
### `!=` or `<>`
Kann dazu verwendet werden um 2 Werte daruf zu überpürfen ob sie **NICHT** gleich sind. Z.B. wenn man alle Prüfungen haben möchte bei denen die Note nicht 5 ist.
```
SELECT * FROM exames WHERE grate != 5;
```
