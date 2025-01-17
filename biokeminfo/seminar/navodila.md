# Navodila za pripravo seminarske naloge

Kot seminarsko nalogo boste pripravili kratko računalniško vajo in sicer boste:
1. pripravili [navodila za vajo](#priprava-navodil-za-vaje) za vaše kolege, ki bodo objavljena kot del te spletne strani (navodila boste morali oddati vsaj 4 dni pred izvedbo), in
2. [vodili](#vodenje-oz-izvedba-vaje) to dotično vajo (kot da bi bili asistent na vajah) v vnaprej določenem terminu (v okviru seminarjev pri tem predmetu).

Nekaj smernic:
- Seminarsko nalogo oz. vajo boste pripravili v paru s sošolcem/ sošolko.
- Tema seminarske naloge naj bo eden izmed programov, uporaben za študente Biokemije na UL FKKT, oz. splošno uporaben za biokemika ali molekularnega biologa.
  - Predavatelj pri predmetu vam je vnaprej pripravil seznam potencialnih programov, ki jih boste predstavili (s seznama si boste sami izbrali želenega), lahko pa tudi sami predlagate kak program, a v slednjem primeru mora vaš predlog potrditi predavatelj.
- **Programi naj bodo spletni** oz. morajo teči na javno dostopnem strežniku, z njimi pa se naj interagira preko spletnega brskalnika (vajo se tako lahko izvaja na računalniku, ki nima nainstalirane neke posebne programske opreme).
- **Naloge morajo biti izvedljive v času, predvidenem za izvedbo vaje!** Priporočam, da si za vsak primer pripravite rezultate analiz za primer, da gre kaj narobe in jih lahko pokažete ter razložite kolegom. Pri tem seveda uporabite enake vhodne podatke kot so jih uporabili vaši kolegi. Nekateri programi za izračun potrebujejo precej časa, včasih tudi več kot eno uri ali celo nekaj dni – taki programi niso primerna izbira.
   - Lahko se zgodi, da že predlagami programi ne omogočajo tovrstne izvedbe, zato to vsekakor preverite in po potrebi predlagajte zamenjavo programa s katerim drugim.
- Zamisliti si morate **vsaj dva seta vhodnih podatkov** (npr. aminokislinska zaporedja, ... - odvisno, za kateri program bo pač šlo) in sicer enega, ki bo dal *pozitiven* rezultat oz. željen, ter enega, kjer rezultat ne bo pričakovan in boste tako lahko demonstrirali, kdaj določen program ne deluje najbolje. Pri tem uporabite znane podatke (iz podatkovnih zbirk - anotacija na osnovi eksperimenta, literature), da demonstrirate pravilnost oz. napačnost rezultata. Potrudite se, da bodo vhodni podatki zanimivi in morda neobičajni - s tem boste pri kolegih vzbudili več zanimanja. **Za primer, ko program ne da pravilnega rezultata, imejte pripravljeno razlago!**
- *Vhodne podatke si morate zamisliti in poiskati sami - uporaba tistih, ki jih program sam predlaga kot primer, ni dovoljena.*

Povezava do seznama s termini seminarjev, pari ter izbranimi programi je objavljena v [spletni učilnici UL FKKT](https://ucilnica.fkkt.uni-lj.si/).

## Priprava navodil za vaje

Navodila za vaje boste pripravili v obliki datoteke formata MarkDown. **Obvezno uporabite [predlogo](seminar-predloga.md)**, pri oblikovanju pa si pomagajte s [splošnimi navodili za oblikovanje](../priloge/markdown.md) tovrstnih datotek.

Na kratko:
1. Prenesite datoteko s [predlogo](https://mpavsic.github.io/biokeminfo/_sources/seminar/seminar-predloga.md).
2. Vsebino prenešene datoteke uredite oz. njeno vsebino nadomestite z vašo – za pisanje lahko uporabite običajen program za delo s tekstovnimi datotekami, priporočam pa uporabo kakšnega specializiranega programa, ki omogoča predogled. Primeri: [Visual Studio Code](https://code.visualstudio.com/) ali pa kar [JupyterLab](../priloge/jupyterlab.ipynb), ki ga sicer uporabljamo za delo z datotekami tipa ipynb (IPython Notebook).
   - Na povezavi s [predlogo](seminar-predloga.md) vidite, kako izgleda ta datoteka, ko je pretvorjena v html. Pri oblikovanju si tako pomagajte s primerjavo tega izgleda in pa same datoteke MarkDown. Na enak način bo pretvorjena tudi vaša datoteka.
   - V navodila lahko vključite tudi eno ali več slik. *Pazite, da imate pravico za njihovo uporabo ter da ustreno navedete referenco.* V primeru lastnih zaslonskih slik (*screenshotov*) vmesnika programa ali pa primera rezultata analiz ni teh težav.
3. Datoteko (s končnico md) naložite prek posebne povezave v spletni učilnici **najkasneje 4 dni pred terminom izvedbe**. Povezava je objavljena pod kategorijo "Seminarji".
   - **Pomembno je, da datoteko ustrezno poimenujete, enako velja tudi za morebiten slikovni material.** Datoteka s seminarjev, pripravljenim na osnovi predloge, naj ima ime **s##-program.md**, pri čemer je **##** številka vašega seminarja (npr. s07 za seminar, ki je na vrsti prvi po seznamu na Google Sheets in je nam naveden kot S07), **program** pa je krako ime programa. Ime programa naj:
      - bo napisano izključno z malimi črkami, dovoljene so številke (npr **jpred4**),
      - dovoljen je znak za minus, npr. **primer-blast**,
      - presledki niso dovoljeni, nadomestite jih s spodnjo črtico (angl. *underscore*) - tako ime **Genome Data Viewer** napišete kot **genome_data_viewer**.
   - Primeri imen datotek s seminarjem:
      - **s16-ensembl.md**
      - **s08-m-coffee.md**
      - **s02-netsolp.md**
   - Imena morebitnih slikovnih datotek (format jpg ali png!) naj bodo enaka imenu glavne datoteke z dodano oznako slike (med ime program in oznako naj bo znak -); primeri imen:
      - **s07-hmmer-algoritem.png**
      - **s15-genome_data_viewer-pregled.jpg**
   - Seveda pazite, da so slike ustrezno referirane v glavni datoteki seminarja in sicer z relativno potjo do datoteke, ki je kar v isti mapi kot glavna datoteka s seminarjem.
   - Enako kot za slikovne datoteke velja za vhodne podatke, če jih je neobhodno potrebno navesti v taki obliki (sicer so bolj zaželjene povezave do ustreznih zapisov v zbirkah - glejte navodila v predlogi); primer poimenovanja: **s08-m-coffee-vhod1.txt** (za FASTA datoteko z več zaporedji).
   - Predavatelj bo vašo vajo pregledal ter vam po e-pošti sporočil, če je z vajo oz. datoteko kaj bistvenega narobe (ne gre za tehnične popravke kot so imena datotek - to morate urediti sami!). Bodite odzivni ter zahtevane nujne popravke vnesite čimprej (najkasneje 2 dni pred izvedbo). Popravljeno datoteko naložite prek iste povezave kot prvotno.
4. Vaša seminarska naloga (navodila za vaje) bodo dostopna pod kategorijo "Seminarji" na tej spletni strani.

## Vodenje oz. izvedba vaje

- Seminarji oz. vaje, ki jih boste izvedli v okviru seminarja, bodo potekali v računalniški učilnici in sicer v dveh učilnicah hkrati. V vsaki učilnici bo po en iz para, ki bo vodil predstavitev. Pri tem se boste naslanjali na navodila, ki ste jih pripravili.
- Vaši kolegi bodo sedeli za računalniki (po eden ali dva na računalnik), vi pa jim boste prek računalnika za katedrom demonstrirali uporabo izbranega programa (vaš ekran bo projiciran na platno). Kolegi vam bodo sledili ob pomoči navodil na tej strani.
- **Posamezna vaja naj traja največ 12 minut + 2 minuti za diskusijo.**

## Ocena seminarja

Ocena seminarja bo sestavljena iz dveh ocen v razmerju 1:1:
- ocene predavatelja ter
- ocene vaših kolegov (mnenje bodo oddali preko posebnega spletnega obrazca). Posamezne ocene kolegov so skrivnost, skupna ocena pa bo "javna" oz. bo objavljena v seznamu ocen, ki vam ga bom posredoval.

Prosim, da ste pri ocenjevanju kolegov realni. Nihče ne bo vedel, kdo točno je koga ocenil slabo ali dobro. *V primeru, da bodo ocene vaših kolegov popolnoma nerealne (npr. vsi bodo dobili najvišje ocene), bodo prispevek slednjih k oceni seminarja zmanjšan ali celo izničen.*