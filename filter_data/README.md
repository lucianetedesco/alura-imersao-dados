## Geração de dataset com filtro (ENEM 2019)

Esta aplicação gera um dataset filtrado baseando-se em uma query passada por argumento.

**Exemplo:**
```
$ python3 generateSample.py --query-expr "CO_ESCOLA == 25061720"

downloading...
MICRODADOS_ENEM_2019.c 100%[===========================>] 402,35M  3,33MB/s    em 2m 9s
extracting...
generating dataset...
done
```

O dataset filtrado é salvo em **MICRODADOS_ENEM_2019_FILTERED.csv**.
