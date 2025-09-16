# Juha Jouppi
## Perhe
### Vaimo
*Hallituksen puheenjohtaja*
### Lapset
1. Poika
2. Tyttö
### Karvalapset
| Laji | Nimi |
| -------- | -------- |
| koira | Manu |
| kissa | Tellu |
| koira | Masi |

---
## Harrastukset
- Omakotitalon remontointi
- [Insinööri**opinnot**](https://net.centria.fi/koulutukset/insinoori-amk-tieto-ja-viestintatekniikka/)
- Järvipelastus
![Heinolan järvipelastajat](https://meripelastus.fi/heinola/wp-content/uploads/sites/11/2024/09/IMG_8463-2048x1365.jpg)

---
## Työ

Tietovarastotyöntekijä

```sql
SELECT tab.table_schema AS Skeema, tab.table_name AS Taulu, tab.table_type AS Tyyppi, count(col.column_name) as Sarake_lkm
FROM information_schema.tables tab, information_schema.columns col
WHERE tab.table_name = col.table_name AND tab.table_schema = col.table_schema AND tab.table_schema IN ('LOAD', 'STAGE', 'DV', 'PUBLISH')
GROUP BY tab.table_schema, tab.table_name, tab.table_type
;
```
---
> Minussa on ongelma
>
>jokin virhe ohjelmoinnissa
>
>Puutteita koodissa
>
>Korvaan arvaamattomuudella
>
>Tuntuu että tekijä unohti otsaan kirjoittaa
>
>Ravistettava ennen käyttöä

*Apulanta*

---
Ja yhteenvetona todettakoon, että mun vahvuus ei ole sisällöntuottaminen, vaan ennemminkin se tekninen puoli asioista :smile: