# Kröfulisti

## Viðskiptakröfur
- BO-1	Auka virkni og skilvirkni í lyfjagjöf með því að draga úr handvirkri skráningu og mistökum.
- BO-2	Minnka of- og vanskömmtun lyfja um 70% innan 12 mánaða með sjálfvirkum tilkynningum og staðfestingum.

## Notendakröfur
- UR-1	Sem starfsmaður vil ég fá tilkynningu þegar kominn er tími á lyfjagjöf svo ég gleymi ekki.
- UR-2	Sem starfsmaður vil ég geta staðfest með einum hnappi þegar ég hef gefið lyf.
- UR-3	Sem starfsmaður/stjórnandi vil ég sjá yfirlit yfir hvaða íbúa hefur fengið lyf í dag.
- UR-4	Sem starfsmaður/stjórnandi vil ég sjá prófíl íbúa með lista yfir lyf og skammta.
- UR-5	Sem stjórnandi vil ég geta endurnýjað lyfseðla í gegnum Heilsuveru.
- UR-6	Sem stjórnandi vil ég sjá lista yfir íbúa sem þurfa endurnýjun lyfseðils.

## Virknikröfur (Functional)
- FR-1	Kerfið skal senda push-tilkynningu á síma starfsmanns á fyrirfram skilgreindum tímum.	UR-1
- FR-2	Kerfið skal geyma tíma, notanda og staðfestingu þegar lyf er gefið.	UR-2
- FR-3	Kerfið skal birta yfirlit yfir gefin og ógefin lyf fyrir hverja vakt.	UR-3
- FR-4	Kerfið skal sýna lyf, skammta og aukaverkanir fyrir valinn íbúa.	UR-4
- FR-5	Kerfið skal leyfa stjórnanda að senda beiðni um endurnýjun lyfseðils í gegnum samþættingu við Heilsuveru.	UR-5
- FR-6	Kerfið skal birta lista yfir lyf sem nálgast lok lyfseðils og þurfa endurnýjun.	UR-6
- FR-7	Kerfið skal geyma allar aðgerðir starfsmanna í atvikaskrá.	UR-2
- FR-8	Kerfið skal senda sjálfvirka viðvörun ef lyf er ekki gefið innan skilgreinds tímaramma.	UR-1
- FR-9	Kerfið skal leyfa starfsmanni að skrá athugasemd ef lyf er ekki gefið eða íbúi hafnar því.	UR-2
- FR-10	Kerfið skal flokka íbúa eftir lyfjum, vöktum og stöðu lyfjagjafar.	UR-3
- FR-11	Kerfið skal birta aukaverkanir og leyfa skráningu þeirra.	UR-4
- FR-12	Kerfið skal geyma allar upplýsingar um íbúa og lyf í gagnagrunni sem tengist prófíl.	UR-4
- FR-13	Kerfið skal birta yfirlit yfir allar beiðnir um endurnýjun lyfseðla.	UR-6
- FR-14	Kerfið skal staðfesta að aðeins stjórnendur hafi heimild til endurnýjana.	UR-5
- FR-15	Kerfið skal senda staðfestingu til stjórnanda þegar endurnýjun hefur verið samþykkt eða hafnað.	UR-5
- FR-16	Kerfið skal skrá dagsetningu og tíma allra beiðna um endurnýjun lyfseðla.	UR-6
- FR-17	Kerfið skal geyma notendaupplýsingar og hlutverk (stjórnandi/starfsmaður).	UR-1–UR-6
- FR-18	Kerfið skal gera starfsmönnum kleift að skoða sögu fyrri gjafa og athugasemda UR-3

## Gæðakröfur (Non-functional)
- QR-1	Kerfið skal vera auðvelt í notkun – skráning lyfjagjafar má ekki taka lengur en 10 sekúndur.
- QR-2	Kerfið skal tryggja gögn gegn óviðkomandi aðgangi með dulkóðun og auðkenningu (t.d. 2FA).

## Viðskiptareglur
- BR-1	Aðeins stjórnendur mega endurnýja lyfseðla í gegnum Heilsuveru.
- BR-2	Starfsmaður má ekki staðfesta lyfjagjöf fyrr en innan 30 mínútna glugga frá áætluðum tíma.
