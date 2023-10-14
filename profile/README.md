# IFI6229.DT Rakenduste programmeerimise kursus

## Projekti jaoks pakun välja lähtuda minu mantrast "Code what you love, so you will love to code" 
Ehk liituda projektiga, mis teid kindlasti kõnetab ja meeldib

Selleks lõin Discorids kanali `#project-joining` kuhu te võite pakkuda oma ideid, mis endale meeldib ja ehk saate endale tiimikaaslasi. 

Mõte on rohkem siis soosida suunata projekti tegemise tuhin mitte tuttavatega koos tegemisele suvalist ideed, vaid ideed, mis meeldib ja vastavalt sellele koonduda huvitatud inimestega 🙂

**Kanalisse kirjutage ainult inimesed, kes pakuvad projekti ideid ja kui meeldib idee, kui ei ole Threadi tekitatud, siis parem nupp ja `Create Thread` ja kirjutage sinna alla, kui olete huvitatud. Töötame first-come-first-serve basis ehk kes 2 inimest jõuavad enne kirjutada, siis saavad liituda projektiga.**

Võite ka täiesti oma liikmetega eraldi teha projekti, mõte on siis lihtsalt selles, et pakkuda ka alternatiiv viisi kuidas meeskondi moodustada.

## 1. november on deadline projekti idee ja informatsiooni esitamiseks
‼️ **Projekti idees osalemisest puudumine tähendab aine läbi kukkumist. Ei pea ise esitama, aga peab olema kusagil projektis ja üks teist peab `#projects` kanalis esitama idee hiljemalt 1. novembril**
* `Mis see tähendab?` Vaja olla 3 liikmelises meeskonnas, projekti pealkiri, idee kirjeldus on välja valitud ning koos autoritega (täisnimed + Discordi tagimine) esitatud #projects kanalisse.
* `Võib juba projektiga alustada?` Enne ei ole mõtet projektiga alustada, kui ma ei ole rohelist linnukest pannud. Võimalik, et projekt liiga kerge/raske ja vaja veel täpsustada detaile, teen teie jaoks eraldi Discordi kanalid ja saan seal teiega täpsemalt suhelda sellel teemal.
* `Kui roheline linnuke saadud, mis siis?` Siis vaja teha projekti jaoks low-fidelity wireframe ja teha projekti README pealkirja, idee kirjeldusega, autoritega ja lisada need ka READMEsse.
* `Siis?` Saab hakata tegema projekti setupi. Selle kohta tuleb ka täpsem kirjeldus, et mis etapid on vaja läbida ja kuidas edasine töö hakkab olema.

## Projekti töö tegemise workflow

### Projekti tegemise sammud
1. Esitada õigeks ajaks (ühe rühmaliikme poolt) idee `1. novembriks`
2. Saada `roheline linnuke`, teen valmis teile repo, teen setupi, saate õigused ja saate pihta hakata
3. Esimesena teha kogu oma projektist `low-fidelity wireframe`
4. Panna kirja `kõik funktsionaalsused`, mida teie projektis võib vaja minna
5. Vastavalt funktsionaalsustele on vaja luua `GitHub issue`-d (taskid)
6. Võite ka luua uued labelid näiteks `frontend`, `disain`, `backend` jms
7. On vaja luua vähemalt `4 milestone`-i ehk nagu `nädalased sprindid` (`06.11-13.11`, `13.11-20.11`, `20.11-27.11`, `27.11-04.12`)
8. Pärast 4 sprinti on teil veel aega kuni eksamini fixida võimalikke buge ja teha vajalikke korrektuure.
9. Iga milestone-i alla on vaja minimaalselt `10 issue`-d
10. Kui tekivad projekti tegemise käigus bugid, siis teha eraldi issue labeliiga `bug`
11. Iga nädal on vaja kindlasti teha vähemalt `1 stand-up` ehk vajalik vähemalt kord nädalas enda projekti panustada
12. Kui kõik see arusaadav ja alustate tööd, siis igaüks kirjutab enda Discordi kanalisse `"Eeltöö tehtud ja alustan arendusega"` peamiselt teada andmiseks, et olete kursis kõigega, mis teha vaja on ja olete kõik ära teinud korrektselt (õige arv milestone-e, issued tehtud, minimaalne arv issue-sid iga milestone all)

#### Igakord kui alustate tööd, teha enda projekti nimelises Discordi kanalis kirjalik `stand-up` vastates kolmele küsimusele:
* Mida tegid eile? (võib issued pealkirjad ka olla)
* Mida teed täna? (konkreetsus ja lühisus tähtis)
* Kas on mingisugused takistused, mis ei lase Sul programmeerida?

Kui teete commiti vastavalt issue lahendamiseks, siis kirjeldusse saate lisada näiteks `closes #number` ehk siis kui commiti ära pushida, siis issue läheb ka automaatselt kinni ja ei pea neid käsitsi handelima 🙂

#### Alati tuleb koodi commitida main branchi läbi pull requestide ehk otse main branchi me ei commiti 🙂

1. Loote main branchi põhjal uue (feature) branchi
2. Teete oma muudatused ainult sinna brachi, peamine töö toimub seal. Teete git add, git commit ja git push selle branchi põhjal.
3. Kui viimased muudatused valmis ja üles pushitud, luua ```Pull request``` (kui see lahendab mingeid ticketeid, kirjutada ka ```closes #number```)
4. Teie projektikaaslane peab vastu võtma teie PR-i (ise vastu ei võta) ja soovitavalt ```Rebase and merge```. [Rohkem infot siit](https://rietta.com/blog/github-merge-types/)
5. Võimalikud konfliktid on vaja ka lahendada, et mis kood jääb peale ja see on ka osa õppimisest, kuidas seda lahendada 🙂

#### Main branchile panen protectioni peale järgmiste nõuetega:
- Require approvals - 1
- Require review from Code Owners 
- Require approval from someone other than the last pusher 
- Require conversation resolution before merging

#### Kuidas commitida?
* Tehke väikseid (kompaktseid) committe ja tihemini, et saab pärast commit historyst üle vaadata ja mitte mõistust kaotada, et kust kohast mingisugused muudatused on koodi sisse tulnud 🤪
* Mõte on pigem teha tööd nö hoomavate tükikestena, et ei ole vaja tervet funktsionaalsust teha, vaid teha osade kaupa.

#### Kuidas toimub basic setup?
1. Kui Discordis on teie projekt minu poolt kinnitatud, pärast 01.11 loon teile eraldi repod siia organisatsiooni alla ja siis saate tööd alustada siin 🙂
2. Repo setupi ja Next.js paigaldamise ma teen ise ära, siis kui kõik valmis, annan accessi ja saate alustada.
3. Vercelisse me otse ei deploy läbi organisatsiooni, all saate lugeda [Kuidas deployda?](https://github.com/rakenduste-programmeerimine-2023/.github/edit/main/profile/README.md#kuidas-deployda)

#### Kuidas deployda?
Vercelil on organisatsiooni jaoks paid plan selleks, et deployda. Kuna meil vaja deployda ainult projekti esitamise ajaks, siis saab forkida grupitöö enda isikliku konto alla ja kasutada seda repot läbi Verceli, et deployda 🙂 Saate ka seda projekti tegemise käigus ka vahepeal jooksvalt teha, kui vaja kellelegi näidata läbi interneti 🙂

1. Selleks on teil vaja forkida rakenduste-programmeerimine-2023/omaprojekti enda isikliku GitHubi reposse
2. Seejärel kloonida endale arvutisse enda isiklikust kontost repo
3. Panna origin, mis linkitud enda isiklikule kontole
4. Panna upstream, mis linkitud rakenduste-programmeerimine-2023/omaprojekti
5. Nüüd on teil one source of truth, et kui on vaja enda repol jälgida võimalikke muudatusi
6. Seejärel saate läbi Verceli lisada enda isikliku konto deploymiseks ja saate vajadusel deployda jooksvalt.

Rohkem infot: https://www.atlassian.com/git/tutorials/git-forks-and-upstreams

## Üldinfo

### Eksami ajad
* **Põhieksam on viimasel tunnil ehk 13.12.2023**
* **Järeleksam on 17.01.2024 kell 08:15**

Kursuse WIKI: [https://github.com/rakenduste-programmeerimine-2023/.github/wiki](https://github.com/rakenduste-programmeerimine-2023/.github/wiki)

Discord: [https://discord.gg/rYgFd6VH](https://discord.gg/nftVkkQ6Gg)

Kodused ja tunnitööd: [https://github.com/rakenduste-programmeerimine-2023/.github/wiki/homework](https://github.com/rakenduste-programmeerimine-2023/.github/wiki/homework)
