# 2020-lov-na-zaklad
Lov na zaklad ob zaključku krožka v šolskem letu 2019/20

Naloge se navezujejo ena na drugo, za vsako si je smiselno pripraviti funkcijo, ki jo lahko kasneje še enkrat uporabiš.

## A del (mlajši in starejši)
[Sosedov Francelj](https://www.youtube.com/watch?v=PyYhxQiQbOU) pa bil zaljubljen je. Svoji izvoljenki bi rad poslal sporočilo, pa ni prepričan, kako bi to storil.

Ni ravno zgodovinar, a se iz šolskih časov spomni, da je Cezar svoja sporočila šifriral s posebno šifro. Izbral si je zamik `k`in vse črke v sporočilu zamaknil za `k` mest v desno. Ker Urška ne komplicira, bosta uporabljala samo male črke angleške abecede: `abcdefghijklmnopqrstuvwxyz`.  Če se dogovorita za zamik 10 se črka `a` pretvori v `k`, črka `u` pa v črko `e` (ko pridemo do konca abecede preprosto nadaljujemo okrog)

<details> <summary>Primer delovanja:</summary>
<p>

![Šifriranje](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4a/Caesar_cipher_left_shift_of_3.svg/1920px-Caesar_cipher_left_shift_of_3.svg.png "Šifriranje")
Črka `d` se kriptira kot črka `a`. in tako naprej.
</p>
</details>


1. Če se dogovorita za zamik 15, kako bi izgledal Francljev podpis (v kaj se šifrira beseda `francelj`)?

2. Seveda so skrita spročila sestavljena iz več besed, ker sta mlada in lena, bosta presledke in ostale simbole pustila na miru,  zašifrirala samo črke, `lov na zaklad` se tako za zašifrira kot `vyf xk jkuvkn` (če uporabimo zamik 10).  V kaj se zašifrira sporočilo `pridem danes, pusti okno odprto`?

3. Francelj je dobil odgovor, pa ga ne zna odšifrirati. Sporočilo se odšifrira na enak način kot zašifrira, le da zamaknemo v levo. Francelj je dobil odgovor:
     ```  qentv senapryw, xre zv znzpn ar qbibyrwb bovfxbi vznz bxab ynuxb bqcegb yr bo cbyav hev. znzpn cn fr mirpre bqcenivwb fcng, mngb fr btynfv gnxeng, xb obfgn zvahgav vab heav xnmnyrp cenibxbgan. pr wr irp zbmabfgv, cbgrz cevqv pvz xnfarwr, qn obqb znzpn tbgbib fcnyv. ```
     Koliko sekund po polnoči naj bo pri Urški, če sta dogovorjena za zamik 13?

4. Groza!! Njuna spročila so prestregli mati. Mati pa ne vedo, s kakšnimi zamiki operirata hči in njen izbranec. Ker pa je v mladosti tudi ona pisala kriptirana spročil vem, da ima tak način skrivanja veliko slabost. V parih razmislite in poskušajte ugotoviti, kakšna težava se pojavi. Mamca so prejeli spodnje spročilo in jo zanima, kaj je Francelj odgovoril Urški (sta pa med tem verjetno zamenjala za koliko zamikata črke), ker pa je celotno sporočilo ne zanima, jo zanima samo zamik, ki ga uporabljata:

	```uirxr lijbr, bvi jvd urevj ivj dftef qrgfjcve qrc ev sfd dfxvc gizkz, jvd kz gr giz fbel gljkzc gfcez kvxvcat erxvcaevm, kv kz sfuvaf m jgfdze erdv ufbcvi jv ev mievd.```
    <details> <summary>Namig 1:</summary>
	<p>
	Pomembem del razbijanja kriptiranih spročil je podatek o kontekstu. Razmisli o kontekstu tega sporočila. Torej vse informacije, okoli sporočila, ki niso zapisane v sporočilu samem. V paru porabita 5 minut za brainstormanje in poskušajta razmisliti.
	</p>
     </details>

    <details> <summary>Namig 2:</summary>
	<p>
	Perne, Novakovič , Strmčnik Žemva, Krapež, Ozimek, Batagelj, Klein, Taseva...
	</p>
	</details>

	<details> <summary>Namig 3:</summary>
	<p>
	Ali se slovenščina in angleščin v čem razlikujeta.
	</p>
	</details>

	<details> <summary>Namig 4</summary>
	<p>
	Ali šifra kakšno lastnost spročila ohrani
	</p>
	</details>

	<details> <summary>Namig 5 (preden ga odkriješ res razmisli o prejšnjem namigu)</summary>
	<p>
	Sporočilo je gotovo napisano v slovenščimi, dasiravno nekoliko arhaični. Poskusi vse možne zamike in preštej frekvenco črk, ki nastopajo, potem potrebuješ na roko pregledati zgolj nekaj zamikov
	</p>
	</details>

5. Urška je prek vrat slišala materino namero. Ker je v dolgih nočeh, ko je čakala Franceljna prebrala cel kup knjig o kriptografiji (za razliko od svojega izbranca, ki knjige bere le poredko), ima že idejo kako ostati korak pred materjo. Franclju bo poslala spodnje sporočilo, kjer bo na koncu dodala eno samo besedo, tako da bodo vse črke v sporočilu enako pogoste, in bo materina ukana zaman. Kako dolga bo polnilna beseda?
	Urškino sporočilo se glasi:
	```francelj, pazi, mati vedo za najin način kriptiranja, zato ti bodem pripravila program, ki naredi šifro nekoliko močnejšo, da pa mati ne bodo prebrali tega sporočila, je na koncu beseda, ki jo ignoriraj.```


## B del (samo starejši)

6. Najdi prvo praštevilo, večje od `A5*1e7`.

7. Najdi kvadratno funkcijo `f`, ki interpolira točke
`(-1, 2)`, `(2, A4)`, `(4, -4)`. Koliko je vrednost `f(2)`?

8. Interpretiraj si A7 v najmanjšem možnem številskem sistemu in seštej njegove števke.

9. Najdi dolžino najkrajše poti skozi labirinit v datoteki `mazeA8.txt`.

10. Sestavi nagradni niz, katerega črke po vrsti so:

- (1) prva črko sporočila iz A3 (malo)
- (2) not a stack (veliko)
- (3) šesta črka A2 (malo)
- (4) druga števka A5
- (5) ponovi (3) (malo)
- (6) Naslednik vsote števk A4
- (7) ponovi (3) (veliko)
- (8) druga črka A1 (malo)
- (9) `repr(chr(A9))[2]` (veliko)
- (10) zadnja črka druge besede A2 (malo)
- (11) Naj bo `x` vsota števk A6. Ta črka je `x`-ta po vrsti po `a`-ju v angleški abecedi.  (velika) (če bi bil `x` 1, bi bil odgovor `B`).

Oglej si Youtube video :)
