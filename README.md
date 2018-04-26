# Mal for kompetanseprosjekt for næringslivet (KPN) - prosjektbeskrivelse

Denne LaTeX-malen forsøker å etterligne Word-malen for KPN prosjektbeskrivelse fra Forskningsrådet.
De offisielle malene ligger her:

https://www.forskningsradet.no/no/Maler_for_prosjektbeskrivelse/1254019550532

LaTeX-malen antar at du har installert skrifttypene Times New Roman, Calibri, og XITS Math. XITS Math følger med LaTeX-pakken `xits`.
Om du ikke får tak i disse skrifttypene, så kan du bytte dem ut med kloner, f.eks. XITS i stedet for Times New Roman og Carlito i stedet for Calibri.
Selv om kloneskrifttypene er ekstremt like de opprinnelige, så bryter du da instruksjonen fra Forskningsrådet som sier at man skal bruke Arial, Calibri eller Times New Roman.

Bruk LuaLaTeX til kompilering, og Biber til bibliografi.
Det enkleste er å bruke Latexmk:
```bash
latexmk -lualatex nfr-kpn-mal
```
Send gjerne forbedringsforlag / pull requests om du finner feil.

**NB: Jeg tar intet ansvar for at malen er 100 % korrekt.
Om du bruker malen, så bærer du det fullstendige ansvaret selv.
Om du får din søknad avvist på grunn av malen så er det ditt eget ansvar.**
