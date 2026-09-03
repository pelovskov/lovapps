## Lydlab i browseren
Man trækker en lydfil ind og vælger, hvad der skal ske: mono, fjern dyb brummen under 80 Hz, klip tavsheden væk i enderne, blød start og slutning, og hvor kraftigt stemmen skal jævnes ud. Loudness-målet står på −16 LUFS. Så trykker man på én knap.

Bagefter viser den kurven før og efter, en skala hvor man kan se hvor optagelsen lå og hvor den endte, og knapper til at høre de to udgaver mod hinanden. Nederst gemmer man mp3'en i 96, 128 eller 192 kbit/s.

**Målingen er den rigtige.** Loudness regnes efter EBU R128 med K-vægtning, 400 ms blokke og begge de gates standarden foreskriver — ikke bare et gennemsnit. Jeg testede den mod referencetonen fra standarden, og den rammer inden for hundrededele. Bagefter sidder der en begrænser med fremsyn, der holder toppene under −1 dBFS; hvis den har måttet arbejde så hårdt at lydstyrken faldt, retter appen op én gang mere. På mit testsignal landede den på −16,07 LUFS med toppen præcis på −1,00.

To ting du skal vide på forhånd:

**Mp3-kodningen tager tid.** Cirka ni sekunder pr. minut lyd. En lydfortælling på ti minutter er halvandet minut om at blive gemt. Der er en fremgangsbjælke, og siden fryser ikke, men man skal blive på fanen imens. Det er prisen for at kode mp3 i en browser — din Mac gør det ti gange hurtigere.

**Længden.** Over cirka 25 minutter siger appen selv til, at det kan blive tungt. Al lyden skal ligge i hukommelsen på én gang.

Fra Cladue
