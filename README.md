# Hello World!
HTML og CSS introduktion Webudvikler grundforløb 2021
<p align="center">
  <img src="https://github.com/rts-cmk-opgaver/HelloWorld/blob/main/Media/0_4ty0Adbdg4dsVBo3.png" /><br>
</p>

## FORMÅLET
Formålet med opgaven Hello World! er helt enkelt at ”ramme skærmen”. Det betyder at vi skal arbejde med et HTML dokument i en kode editor og efterfølgende se vores HTML dokument renderet som en webapplikation i browseren. I arbejdet med at ”ramme skærmen” vil I stifte bekendtskab med en kode editor og få en grundlæggende forståelse for helt fundamental webteknologi.

## HTML
HTML eller Hyper Text Markup Language benyttes til at definere struktur på en hjemmeside. Strukturen defineres ved brug af forskellige HTML tags. Hvert HTML tag repræsenterer et bestemt område i vores webapplikation, hvilket for eksempel kunne være området for applikationens overskrift. HTML består af flere forskellige semantiske tags. Hver enkelt tag repræsenter et specifikt formål, taggets navn beskriver tydeligt for både udvikler og browser hvilket formål der er talt om.

> NOTE: Når vi skriver semantisk markup, bruger vi HTML-tags til at fortælle browseren om elementernes indhold!

Et eksempel på et formål kunne endnu engang være webapplikationens overskrift. For at definere applikationens overskrift, skal vi bruge et specifikt HTML tag. Den semantiske navngivning af tags hjælper os med at finde det korrekte tag til formålet. I dette eksempel vil det være tagget h1, som er en forkortelse af Heading 1, som I måske allerede kender fra for eksempel Microsoft Word.

<p align="center">
  <img src="https://github.com/rts-cmk-opgaver/HelloWorld/blob/main/Media/HTMLTags.jpg" /><br>
</p>

I dette afsnit skal vi se lidt nærmere på HTML tags. HTML tags har som regel både et åben(start)-tag og lukke(slut)- tag, med undtagelse af nogle få tags, som åbner og lukker i et og samme tag. Lad os tage et nærmere kig på hvordan det tidligere omtalte Heading 1(h1) tag er opbygget

> NOTE: <!-- … --> Kommentar tagget bruges til at kommenterer kildekoden. Kommentar vises ikke i browseren!

## HTML Heading 1 tag

<p align="center">
  <img src="https://github.com/rts-cmk-opgaver/HelloWorld/blob/main/Media/Heading.jpg" /><br>
</p>

Karakteren imellem mindre end tegnet og større end tegnet indikerer taggets formål. I eksemplet oven for er h1 en forkortelse for Heading 1. Den overskrift som vi ønsker at vise i vores webapplikation, skal placeres imellem h1 elementets åben- og lukketag. Se grafik i umiddelbart herunder.

## HTML element

<p align="center">
  <img src="https://github.com/rts-cmk-opgaver/HelloWorld/blob/main/Media/HTMLElement.jpg" /><br>
</p>

Når et HTML element bliver renderet i browseren vises det indhold som er placeret imellem åben og lukke tagget.

I ovenstående eksempel vil det derfor alene være teksten HELLO WORLD!, der vil blive vist i browseren.

> NOTE: Et HTML element omfatter et åbentag, et lukketag og hvilket som helst indhold placeret herimellem!

## Markup

I dette afsnit skal vi se nærmere på seks semantiske HTML tags. Vi skal bruge de seks udvalgte tags i praksis, til at definere struktur for hello world applikationen. Før vi kan begynder at skriv markup, skal der oprettes en projektmappe og heri en index.html fil.

<p align="center">
  <img src="https://github.com/rts-cmk-opgaver/HelloWorld/blob/main/Media/sas.jpg" /><br>
</p>

Den første opgave består i at skrive den samme markup, som der
ses på skærmbilledet herover. Vær omhyggelig, syntaksen er vigtig og selv den mindste tastefejl, kan betyde at applikationen ikke
renderes som det forventes. Indryk mellem tags er vigtig for dokumentets læsbarhed og ’debug-og-samarbejds-venlighed’ og er derfor en helt essentiel del af arbejdet med at skrive kode. Når i er færdige med at skrive ovenstående markup, er det tid til at eksekverer dokumentet i browseren.

<p align="center">
  <img src="https://github.com/rts-cmk-opgaver/HelloWorld/blob/main/Media/sas.jpg" /><br>
</p>

Måden vi gør vores applikations userinterface mere indbydende, tilgængelige og fleksibel på, er ved at tilføje et præsentations lag. Det kommer vi nærmere ind på, men først en forklaring af de seks tag, som vi skal arbejde med.

> NOTE: Vi benytter HTML til struktur, CSS til præsentation og JavaScript til interaktion i vores applikationer!

## Tags forklaring

**Header**. 
elementet bruges til introducerende indhold, hvilket eksempelvis kan være en overskrift eller et logo. Elementet vil også kunne bruges som placering for eksempelvis en søge- eller loginformular, navigation etc.

**Nav** elementet bruges hovedsageligt til at præsenterer applikationens navigations som kan bestå af både interne og eksterne links.

**Main** elementet bruges til at præsenterer indhold som relaterer sig direkte til applikationens centrale emne eller funktionalitet.

**Article** elementet bruges til at præsenterer selvstændigt indhold som vil kunne genanvendes i andre sammenhæng hvilket eksempelvis kunne være; en blog post, en artikel eller en nyheds historie.

**Section** elementet bruges til at repræsenterer fritstående indhold som ikke kan repræsenteres af et mere specifikt semantisk element.

**Footer** elementet bruges som ofte til at præsenterer information omkring applikationens ophavsmænd, copyright information eller links til relevant information.
