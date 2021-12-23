# gépkocsi nyilvántartó alkalmazás
a gépkocsinak a következő adatai vannak
- gyártó
- tipus
- teljesítmény (lóerő)
- űrtartalom (ccm)

Webalkalmazás feladat a szokott konvenciók betartásával valósítsa meg a gépkocsi entitás 
- feltöltését, 
- törlését, 
- módosítását, 
- listázását.

Kérünk még egy **eleg-eros-auto** kereses végpontot, ami GET metódusra válaszol, 
http paramétere teljesitmeny értéke egy eletkor. Működése: visszaadja azon gépkocsikat, amelyek űrtartalma legalább 1600, és a teljesítménye nagyobb, mint a
kapott paraméter. pl.: http://localhost:8080/gepkocsi/eleg-eros-auto?teljesitmeny=180

1. kommit uzenet legyen “projektAlap”, a spring starter által generált üres projekt. h2 adatbázis, spring data, spring-boot-starter-validation, spring web
2. kommit üzenet “adatbazis”, szükséges entitások, repository, config beallitasok
3. kommit üzenet “web” működő webalkalmazás a szükséges végpontokkal.
4. kommit üzenet “hasznalat” milyen http kérésekkel lehet a funkciókat kipróbálni. pl: PUT http://localhost:8080/gepkocsi/2 {JSON}

Követelmények:

- SOLID elvek betartása
- müködő funkciók
