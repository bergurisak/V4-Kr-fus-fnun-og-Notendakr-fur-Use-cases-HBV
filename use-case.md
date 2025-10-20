# Fully Dressed Use Case

**ID:** UC-1  
**Heiti:** Gefa Lyf
**Aðal aðili:** Starfsmenn 
**Aukaaðilar:** Stjórnendur og Íbúar

## Forsendur
- Starfsmaður er skráður inn í appið með réttum aðgangi.
- Lyfjaskrá íbúa er uppfærð og gild.
- Appið hefur aðgang að interneti eða geymir gögn tímabundið offline.
- Íbúi er á virkum lyfjaáætlunartíma.

## Eftirskilyrði
- Ef vel tekst til:
Gjöf er skráð í gagnagrunn með tíma, notanda og skammtaupplýsingum.
Yfirlit dags uppfært og tilkynning merkt sem lokið.
Rekjanleiki (audit log) inniheldur allar upplýsingar.

- Ef mistekst:
Villuskilaboð birtast, skráning fer ekki í gagnagrunn og starfsmaður fær tilkynningu um að endursenda síðar.

## Aðalflæði
1. Kerfið sendir push-tilkynningu á síma starfsmanns þegar kominn er tími á lyfjagjöf.
2. Starfsmaður opnar tilkynninguna og er vísað á skjá með lista yfir íbúa og þeirra skammta.
3. Starfsmaður velur viðeigandi íbúa og sér upplýsingar um lyf, skammt og aukaverkanir.
4. Starfsmaður gefur lyfið samkvæmt leiðbeiningum.
5. Starfsmaður ýtir á hnappinn „Lyf gefið“.
6. Kerfið skráir lyfjagjöfina með tíma, notanda og staðfestingu.
7. Kerfið uppfærir yfirlit „búið að gefa“ og sýnir næstu áætlun eða íbúa.

## Valflæði
- A1: Lyfjagjöf seinkar:
Ef starfsmaður getur ekki gefið lyfið á réttum tíma, velur hann „Seinka“ og gefur ástæðu.
Kerfið sendir áminningu eftir 15 mínútur eða þegar hann er laus.

- A2: Íbúi hafnar lyfi:
Starfsmaður velur valkostinn „Íbúi hafnaði lyfi“.
Kerfið biður um stutta skýringu og skráir tilvikið sem undantekningu í audit log.
Stjórnandi fær tilkynningu um tilfellið.

## Undantekningar
- E1: Tengingartruflun (offline):
Ef engin nettenging er til staðar, skráir appið gjöfina staðbundið og samstillir þegar tenging næst aftur.

- E2: Ofnæmi eða villa í lyfjaskrá:
Kerfið birtir viðvörun ef íbúi hefur skráð ofnæmi við lyfi.
Starfsmaður getur ekki staðfest gjöf nema með sérstakri skýringu.

- E3: Tæknileg villa:
Ef kerfið nær ekki að vista skráningu, birtast villuskilaboð og gögn vistast í biðlista til samstillingar.

## Tengsl (Traceability)
- Tengdar notendakröfur: UR-1, UR-2, UR-3
- Tengdar virknikröfur: FR-1, FR-2, FR-3, FR-7, FR-8, FR-9, FR-10, FR-18
- Tengdar viðskiptareglur: BR-2
- Tengdar gæðakröfur: QR-1, QR-2
