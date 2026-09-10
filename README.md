Vad innebär semantisk HTML och varför har ni använt det på er eventsida?
Semantisk HTML beskriver innehållets betydelse i de olika delarna av webbsidan till skillnad från div som är en generell tag.
T.ex  "header" talar om att det är huvudet på sidan, vilket är därför i valde den till vår hero. Vi använder semantisk-HTML på vår sida för att göra strukturen tydlig för oss själva och verktyg som skärmläsare.

Hur fungerar arv i CSS? Ge ett exempel från er egen kod?
Arv fungerar så att om man till exempel sätter vissa egenskaper som textfärg på föräldern, anvämder barnen också det värdet, så länge barnen inte har ett eget värde för egenskapen. Det gäller inte alla CSS egenskaper. Tex padding arvs inte.
Ex: i vår kod på  .footer har har vi satt color och p-tagarna som är barnen får också den textfärgen.

Vad är den största skillnaden mellan Flexbox och CSS Grid, och när ska man använda vilket verktyg? Motivera utifrån hur ni fördelade dem på er sida.
Flexbox är endimensionellt. Det är utformat att lägga element i en riktning åt gången, tex rad eller kolumn. På vår sida använde vi Flexbox när vi skulle rada upp vara aktiviteter om pannkokor (.aktivtetskort), eftersom vi ville lägga korten i een rad och låta dem byta rad vid behov.
CSS grid är två dimensionellt och kan hantera både rader och kolumner samtidigt. Vi ville ha like breda kolumner för våra event (.grid-ccontainer), så för att ordna eventen i ett rutnät med både rader och kolumner valde vi CSS grid.
