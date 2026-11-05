(1) Napište příkaz, který z adresáře `data` zkopíruje všechny soubory s příponou `.ini` do adresáře `konfigurace`:

(2) V souboru `kody.txt` se nachází seznam čtyřciferných kódů. Napište příkaz, který do souboru `pocet.txt` zapíše počet všech kódů:

(3) V souboru `obrazek.txt` jsou kódy barev každého pixelu jednoho obrázku (ve tvaru RRGGBB). Napište příkaz, který do souboru `barvy.txt` zapíše všechny řádky, kde se alespoň jednou vyskytuje bílá barva:

(4) Napište příkaz, který do souboru `hlasy.txt` zapíše unikátní čísla ze souboru `hlasovani.txt`. Bude se hodit příkaz sort a vhodný přepínač:

(5) Slovně popište, co vypíše tento příkaz (lze vyjádřit čtyřmi slovy):

```
$ sort telefony.txt | uniq -c | sort -r | head -n 5
```
