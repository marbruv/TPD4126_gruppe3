# TPD4126_gruppe3
Repository for prosjektet til gruppe 3 i TPD4126 Prototyping av fysiske brukeropplevelser, vår 2024.

Prosjektet vårt har fått navnet "Panikk", og har følgende hovedelementer:
- Trykk på en tilfeldig rute for å starte, venteshow mens spillet er inaktivt.
- Én og én rute lyser opp, og brukeren må trykke riktig rute før tiden har gått ut.
- Begynner med 4 sekunder lys, men minsker med 80ms per rute ned til 300ms. Delayet mellom hver rute begynner på 1s, og minsker med 40ms ned til 150ms.
- Hver bruker får tildelt et rundenavn bestående av en tilfeldig kombinasjon av ett adjektiv og ett dyr, som brukes for å følge poengscoren. Dersom brukeren får dagens høyeste score, blir rundenavnet plassert under highscore, og står frem til noen får høyere score (eller arduinoen resettes).

**Hva har begrepet tid med spillet vårt å gjøre?**
Tiden er relativ. Den kan feks gå fortere om man stresser eller når man har det gøy. I spillet vårt tar vi tidskonseptet og omformer det til en spennende, interaktiv opplevelse som utfordrer barn til å forstå tidsforløp på en leken måte. Stresselementet ligger i at frekvensen og lystid per rute øker. Highscorefaktoren vekker konkurranseinstinktet, like mye for voksne som for barn! 

Vi har følgende tekniske komponenter integrert i spillet:
- 1 stk Arduino Uno
- 24 stk NeoPixel 24 LED ringer (288 LED pærer)
- 14 stk arcade knapper (12 til spillet, én til reset av spillet, og én til reset av arduino)
- 2 stk LCD1602 display med I2C

Henter bibliotekene Adafruit NeoPixel, LiquidCrystal I2C, og Wire. 

Gruppemedlemmer:
Millicent Helene Nordhagen Garde, Emily Omholt Brandrud, Sanna Neeraas Brodtkorb, Maria Bruvik
