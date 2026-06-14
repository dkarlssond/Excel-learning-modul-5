Excel Modul 5 – Dynamiska matriser

Femte caset i min Excel-träning inför en roll som business controller. Det här handlar om dynamiska matriser – moderna formler där en enda formel fyller flera celler och uppdaterar sig själv när datan ändras.

Underlaget är en orderlista för ett påhittat tillverkningsbolag, Nordvik Industri. 70 försäljningsrader med region, säljare, produktkategori och intäkt. Uppgiften var att bygga självuppdaterande sammanställningar utan vanliga formler eller pivottabeller.

Vad jag gjorde


Plockade fram unika regioner och säljare med UNIQUE
Sorterade säljarlistan i bokstavsordning med SORT
Filtrerade fram alla order i en region med FILTER
Nästlade SORT och FILTER för att visa en regions order sorterade på intäkt
Byggde en topp 10-lista över de största ordern med TAKE och SORT


Vad jag tog med mig

Hur en dynamisk matris "spiller" ut sitt resultat över flera celler från en enda formel, och uppdateras automatiskt när data tillkommer. Och hur funktioner kan nästlas i varandra – SORT runt FILTER, TAKE runt SORT – för att bygga rapporter som sköter sig själva.

Fil

Övningscase_5_Excel.xlsx – fliken Försäljning innehåller datan, och Analys innehåller formlerna med sina framspillda resultat.

Byggd i Excel 365.
