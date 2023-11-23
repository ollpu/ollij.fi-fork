# Usein kysytyt kysymykset

Vastaan tässä yleisiin vastareaktioihin mitä olen saanut koskien tekoälyuhkaa.

*Nämä eivät ole vahvimmat vasta-argumentit tekoälyuhkaa vastaan* (tai välttämättä edes vasta-argumentteja). Nämä ovat asioita, joita olen kuullut puhuessani (aiheeseen perehtymättömien) kanssa. Ajattelen siksi niiden käsittelyllä olevan pedagogista arvoa. Jos haluaa lukea järkevien ihmisten järkeviä erimielisyyksiä aiheesta, niin tämä ei ole oikea paikka, vaan suosittelen lukemaan [muita tekstejä](https://ollij.fi/tekoaly/lukemista).

Joka tapauksessa nämä vaikuttavat olevan kysymyksiä, joita monilla on mielessä ja joihin he haluavat vastauksia. Siksi näen arvoa vastausten antamisessa.

**Kysymys:** Miksi tekoälyillä olisi tavoitteita? Puhut esimerkiksi siitä, että monilla tavoitteilla on yhteisiä välitavoitteita (kuten resurssien hankinta) -- mutta miksi olettaa ylipäätään, että tekoälyillä on tavoitteita?

Tämä on hyvä kysymys.

Aloitan selkeyttämällä tavoitteiden konseptia. Puhuttaessa [AlphaGosta](https://en.wikipedia.org/wiki/AlphaGo) voisi sanoa, että "se yrittää voittaa" tai "sen tavoite on voittaa go". Nämä kuvaavat kohtalaisen hyvin AlphaGon toimintaa -- siitäkin huolimatta, ettei tällaista tavoitetta ole eksplisiittisesti ohjelmoitu AlphaGohon ja "se vain pelaa". Tarkempia, mutta kankeampia, kuvauksia: "AlphaGo tekee sellaisia siirtoja, jotka (hyvin monessa pelilaudan tilanteessa) ovat hyviä pelin voittamisen kannalta" tai "AlphaGo on koulutettu tekemään enemmän sen tyyppisiä siirtoja, jotka ovat harjoituspeleissä johtaneet voittoon".

Ja tämä tieto AlphaGosta johtaa muihin ennustuksiin koskien AlphaGon toimintaa. Perushuomio "voittamisen kannalta hyvä välitavoite on saada kontrollia laudasta" kertoo jotakin siitä, mitä odottaa AlphaGon tekevän, vaikkei sillä "oikeasti" olisi tavoitteita. Saman asian voi nimittäin muotoilla, taas kankeammin, sanomalla "monesti siirrot, jotka johtavat pelin voittamiseen, ovat sellaisia, jotka johtavat kontrolliin laudasta" tai vastaavaa.

Yleisesti sanoisin, että useimmat tekoälyuhka-argumentit voisi muotoilla ilman sanaa "tavoite".

Toisaalta pidän kohtalaisen todennäköisenä, että kehittyneillä tekoälyillä on tavoitteita -- siis jokseenkin samassa mielessä kuin minulla on tavoitteita tai arvoja, asioita joiden haluan olevan tosia, tiloja joissa haluan todellisuuden olevan. Evoluutio nimittäin on tuottanut (ainakin) ihmiset, joilla tällaisia preferenssejä on. En tiedä tarkkoja mekanismeja preferenssien synnyn taustalla. Siksi minusta on ihan mahdollista, että myös (joidenkin) syväoppimismallien kouluttamisessa syntyy tavoitteen omaavia malleja.

**Kysymys:** Kai nyt tekoälyjen tekijät tietävät, miten ne toimivat?

Ei, tämä on yksinkertaisesti epätosi väite.

Ymmärrän, miksi jotkut uskovat näin: yleisesti ottaen ihmiset tietävät, miten heidän luomansa asiat toimivat! (On vaikea kuvitella maailmaa, jossa ihmiset ajavat autoillansa, mutta kukaan ei tiedä, miten autot toimivat.)

Mutta ei, näin ei ole syväoppimismallien tapauksessa: niin tekijät kuin yleisesti muutkaan tekoälyn parissa työskentelevät eivät tiedä, miten mallit toimivat. Tämä on ongelma, jota yritetään ratkaista (hakusana: interpretability), mutta toistaiseksi olemme varsin tietämättömiä.

Analogia: Kuvitellaan, että ulkopuolisena tarkkailijana seuraat elämän ja evoluution kehitystä maapallolla viimeisten satojen miljoonien vuosien aikana. Voit hyvin ymmärtää periaatteet evoluution taustalla. Siitä huolimatta sinun olisi vaikea etukäteen ennustaa, minkätyyppistä elämää maapallolla tulee kehittymään. Voit tehdä joitakin helppoja, korkean tason arvauksia ("ne ovat hyviä lisääntymään"), mutta esimerkiksi eläinten fysiologisten ominaisuuksien ennustaminen on hyvin haastavaa.

(Ja miten olisit ennustanut, että jotkin näistä eliöistä tulevat käymään Kuussa?)

Syväoppimisessa ollaan samankaltaisessa tilanteessa: ymmärrämme kyllä "evoluutiota" eli mallien kouluttamisprosessia hyvin -- se *on* (pitkälti) ihmisten suunnittelema! "Elämän kehittyessä" eli mallin koulutusvaiheessa mallin parametrit muuttuvat kuitenkin muuttuvat tavalla, jota ei etukäteen osata ennustaa. Edes jälkikäteen mallien toimintaa ei ymmärretä (samaan tapaan kuin emme ymmärrä vaikkapa ihmisaivojen toimintaa).

**Kysymys:** Tulevaisuuden ennustaminen on hyvin vaikeaa, mutta vaikutat silti olevan aika varma näistä uhista. Avaatko?

Olen samaa mieltä siitä, että ennustaminen on vaikeaa. Olen tietoinen siitä, että aikojen saatossa ihmiset ovat tehneet varsin huonoja ennustuksia koskien tulevaisuutta. (Olen myös tietoinen erinäisistä tekijöistä, jotka saavat ihmisiä tekemään huonoja ennustuksia -- konjunktioharha ja representatiivisuusheuristiikka tulevat nopeasti mieleen, kuten myös laajemmin probabilistisen ajattelun puute.)

En sanoisi olevani "aika varma" näistä asioista. Olen joistakin asioista varmempi kuin toisista. "Tekoälyuhka on asia, jonka välttämiseksi kannattaa käyttää paljon enemmän resursseja kuin nyt käytetään" on asia, josta olen käytännössä varma. En kuitenkaan ole varma näiden uhkien realisoitumisesta tai ajankohdista! Niin ikään minulla on näkemyksiä siitä, millaisia asioita uhkien välttämiseksi kannattaisi tehdä, mutta näissäkin on epävarmuutta.

Minulla on toki uskomuksia koskien näitäkin asioita -- "A man always has his probabilities" -- ja näen uhkien olevan todennäköisiä ja lähitulevaisuuden kannalta relevantteja. En tarkenna, mitä tarkoitan "lähitulevaisuudella", koska ensinnäkin olen epävarma ja toisekseen aikajänteet eivät ole *niin* keskeisiä uhan kannalta. Vaikka saisin tietää, että tekoälykehitys viekin pidempään kuin nyt uskon, pitäisin silti uhkaa huomionarvoisena!

(Yleensä tulevaisuuden ennustamisen vaikeudesta puhuvat mainitsevat jonkin historiallisen ennustuksen, joka on dramaattisesti aliarvioinut muutokseen kuluvan ajan -- argumenttina sille, että nytkin asioissa menee pidempään kuin ajatellaan. Tätä peliä voi tietysti [pelata kaksinkin](https://en.wikipedia.org/wiki/Flying_Machines_Which_Do_Not_Fly), mikä tarkoittaa, ettei tämä ole kovin hyödyllinen peli. Pikemminkin tällainen yksittäisten esimerkkien pallottelu vaikuttaa minusta haitalliselta.)

**Kysymys:** Eikö oikea ongelma ole...

Eri ihmiset tarjoavat erilaisia jatkoja tälle virkkeelle, pyörien yleisesti tekoälyistä koituviin haittoihin (esimerkiksi epätasa-arvoon, vinoumiin, valvontaan, misinformaatioon, autonomisiin aseisiin tai työttömyyteen).

Yksi vastaus on: Jos olet eri mieltä eksistentiaalisten uhkien todennäköisyydestä, niin voit sanoa sen suoraan! Kenties voimme keskittyä erimielisyyteen koskien tätä tai selvittää, mistä muista asioista olemme samaa tai eri mieltä.

Toinen vastaus on: Eri haitat eivät ole poissulkevia! Yhden haitan nimeäminen "oikeaksi ongelmaksi" muiden kustannuksella vaikuttaa epäproduktiiviselta. Tarvittavat toimet haittojen ennaltaehkäisemiseen tai pienentämiseen ovat, ei aina, mutta välillä samoja. Toivon yhteistyökykyä, vaikka uskomuksissa on eroja.

(Enkä itse ole välinpitämätön huolista kuten "tekoälyn avulla vaikutetaan yleiseen keskusteluun ja poliittiseen päätöksentekoon sekä levitetään misinformaatiota". [Minä ihan välitän totuudenmukaisista uskomuksista](https://ollij.fi/epi). En vähiten siksi, että hyvä yleinen keskustelu ja päätöksenteko vaikuttaa tärkeältä eksistentiaalisten uhkien välttämiseksi, mutta muistakin syistä.)

---

Seuraavaksi käsittelen paria kommenttia, joita pidän... ajattelemattomina. Nämä ovat, taas, asioita, joita olen kuullut ihmisille keskustellessani. Näen pedagogista arvoa siinä, että kerron, mitä rehellisesti ajattelen niistä, yrittämättä olla erityisen kohtelias. Ainakin joillekin. Jotkut taas eivät halua lukea tällaista.

Jos siis tekstilaji "suorasanaisia, epäkohteliaita vastauksia ajattelemattomiin kommentteihin" ei ole sinun mieleesi, suosittelen hyppäämään seuraavaan tekstiin.

Lukijan ei tule ajatella "nämä ovat ne jutut, joita tekoälyuhkaa epäilevät uskovat!". Taas, järkevien ihmisten järkevät erimielisyydet löytää [toisaalta](https://ollij.fi/tekoly/lukemista).

Hyvä, selvä? Jatkan sitten itse kommentteihin.

**Kommentti:** Pitää vain asentaa off-nappi tekoälyihin!

Ihmisillä vaikuttaa olevan vaikeuksia käsittää, että kyllä, myös tekoäly voi kyetä strategiseen suunnitteluun. "Ai, mutta sehän on vain kone! Ja koneen voi laittaa pois päältä!", ihmiset ajattelevat. "Helppo juttu!"

Ihmisetkin ovat vain koneita. Ihmisilläkin on off-nappeja.

(Houkutteleeko erä Lännen nopeinta?)

Ehkä se on luontevaa, että jos ei mallinna muita ihmisiä kykenevinä miettimään yhtä askelta pidemmälle -- "en ymmärrä miksi ihmiset ovat huolissaan tekoälystä, vaikka ratkaisu on näin ilmeinen" -- niin ei tule ajatelleeksi, että tekoälykin voisi ajatella askeleen pidemmälle. Sitä yrittää puhua näistä "ihmisiä älykkäämmistä tekoälyistä", ja mitä ihmisille jää käteen on "vain pelkkä kone, joka jää virittämääni helppoon ansaan".

Keskeinen osa ongelmaa on nimenomaan "entä kun tekoäly on minua älykkäämpi ja keksii asioita, joita minä en keksi?" Tämä vaikuttaa olevan vaikea käsittää: ongelma muuttuu *haastavammaksi*, kun tekoälyt muuttuvat kyvykkäämmiksi. Lähestymistavat, jotka toimivat tyhmillä koneilla eivät enää toimikaan, kun kyseessä on... se, mistä koko uhassa on kyse.

**Kommentti:** Aina on ennustettu maailmanloppua.

Auki kirjoitettuna "yksikään maailmanlopun ennustus ei ole toteutunut" ei enää kuulostakaan niin nerokkaalta vasta-argumentilta -- minkä vuoksi tällaiset kommentit tietysti jätetään vain epämääräiseksi retoriseksi heitoksi. Enkä siksi anna niille painoarvoa.

Mikä varmaankaan ei ole tällaisen kommentin esittäneen mielestä tyydyttävä vastaus.

Ja minä voin jatkaa, että olen [itse asiassa](https://ollij.fi/epi/reflektointi) kuullut siitä, että tällaisia ennustuksia on tehty.

Mihin voi vastata, että tämä ei tarkoita, että olen oikeassa.

Mistä minä olen tietysti samaa mieltä.

Mihin voi vastata, että en ole vastannut itse pointtiin.

Minä vastaan, että en oikeastaan tiedä, mikä on varsinainen pointti. Sanoinkin jo, että "yksikään maailmanlopun ennustus ei ole toteutunut" ei ole minusta erityisen nerokas vasta-argumentti.

Mihin voi turhautua ja sanoa, että tarkoituksella kierrän kysymyksen.

Rehellisesti, olen hieman kyllästynyt peliin "keksi [kohteliaita tulkintoja](https://ollij.fi/epi/kohteliaat_tulkinnat) ihmisten retorisista kommenteista". Jos ihmisillä on oikeita pointteja, niin esittäkööt he ne suoraan eikä vähättelevien kommenttien muodossa. Jos näitä oikeita pointteja ei ole, niin on teennäistä esittää kohteliasta ja pohtia, mitä loistavia huomioita näiden näennäisesti ajattelemattomien kommenttien takana on.

Mihin voi vastata "pointti on, että aiemmat ennustukset maailmanlopuista ovat olleet selkeästi huonoja, mikä on evidenssiä sille, että muutkin maailmanlopun ennustukset ovat selkeästi huonoja".

(Mihin joku toinen voisi vastata, että tuo ei ole se pointti ja selvästi tässä on ymmärretty asia ihan väärin. Mikä on juuri se, minkä takia olen kyllästynyt kohteliaiden tulkintojen peliin.)

Mihin vastaan, että ihmiset voivat muodostaa (ja ilmeisesti muodostavat) uskomuksena tätä kautta. Minä taas en mieti asiaa näin, koska tämä on vain surkea tapa miettiä aihetta. Jos minulta kysyttäisiin todennäköisyyttä sille, että seuraavan sadan vuoden aikana asteroidi iskeytyy Maahan johtaen ihmiskunnan sukupuuttoon, niin minä en vastaisi "ah, tämä on taas noita maailmanlopun ennustuksia, eihän tuo voi tapahtua". Minä miettisin "Kuinkakohan usein Maahan iskeytyy riittävän suuria asteroideja? Hmm, 65 miljoonaa vuotta sitten dinosaurukset..." Vastaavasti kysyttäessä keinotekoisen pandemian aiheuttaman katastrofin todennäköisyyttä miettisin muita asioita kuin "kuinka hyviä maailmanlopun ennustukset ovat yleisesti olleet?".

Jos muut ihmiset ovat tehneet paljon huonoja ennustuksia koskien asteroideja tai pandemioita, niin kenties on hyödyllistä selvittää, mistä nuo huonot ennustukset johtuvat, ettei itse tee samoja virheitä. Kenties on yleisesti hyödyllistä kehittää taitoaan muodostaa [totuudenmukaisia uskomuksia](https://ollij.fi/epi). En sanoisi, että olen sivuuttanut tätäkään puolta aiheesta.

**Kysymys:** Onko se nyt niin paha, jos tekoäly tappaa kaikki?

On.

"Se oli vitsi."

Olen [toisaalla](https://ollij.fi/epi/ongelmien_sivuuttamisesta) kirjoittanut, kuinka tällaiset huumorihakuiset absurdit väitteet ovat kätevä tapa sivuuttaa ongelmia.

Joku voisi vastata, että ylianalysoin tilannetta ja että se on vain vitsi.

On aika hauska sattuma, että useampi ihminen on keksinyt tämän saman "vitsin". Ja kun sanon "hauska sattuma", tarkoitan säännönmukaisuutta. Tekoälyuhka vaikuttaa olevan aihe, joka saa ihmisten ajattelun rikki ja sanomaan ties mitä roskaa. "[Kaukaiset](https://ollij.fi/epi/kaukotila)", "[filosofiset](https://ollij.fi/epi/filosofiatila)" aiheet tuppaavat olemaan sellaisia. Olen syystäkin [kirjoittanut](https://ollij.fi/epi) tästä teemasta.

Joku voisi "kohteliaasti" huomauttaa, että kyllä nämä ihmiset oikeasti pitävät sitä huonona asiana.

Mihin vastaan, että tämä on epätosi väite -- [jakaumat ovat leveitä](https://ollij.fi/epi/leveat_jakaumat) ja niin edelleen. Osan kohdalla kyse varmaankin on vitsistä, mutta on virheellistä sanoa, ettei kukaan ole tätä mieltä.

Voit toki pitää sitä itsestäänselvyytenä, että kaikkien kuoleminen on hyvin paha asia ja sen estämiseksi kannattaa tehdä jotakin. Olen tästä samaa mieltä.
