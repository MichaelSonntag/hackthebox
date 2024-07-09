# Pennyworth
So 7. Jul 23:54:20 CEST 2024

## Acronyme

|Acronym|Detail|
|:---:|:---:|
| CVE | Common Vulnerabilities and Exposures |
| CIA (triad in cybersecurity) | Confidentiality, Integrity, Availability | 

## Version von Jenkins
kann anhand des X-Jenkins Cookie erkannt werden ```2.289.1```

## Login bruteforce geraten!

## Groovy Scripte für Reverse Shell (Topfi Mode)
Bevor ich die Reverse Shell starte, muss ich netcat (nc) bei mir laufen lassen 

```nc -lvnp {{PORT}}```
- -l listening
- -v verbose
- -n numeric-only, no DNS
- -p Port, only listen to this port

## Flag gefunden
per Hand mit cd Navigation: 9cdfb439c7876e703e307864c9167a15

```find ./ -name flag.txt``` 
