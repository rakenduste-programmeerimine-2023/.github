# IFI6229.DT Rakenduste programmeerimise kursus

## Code what you ❤️, so you will ❤️ to code
**Projekti tegemiseks jagan mantrat, mille järgi mina elan ehk liituda projektiga, mis teid kindlasti kõnetab ja meeldib ja siis jätkuvalt on suurem ka tõenäosus, et naudite programmeerimist**

* Selleks lõin Discorids kanali `#project-joining` kuhu te võite pakkuda oma ideid, mis endale meeldib ja ehk saate endale tiimikaaslasi. 
* Mõte on rohkem siis soosida suunata projekti tegemise tuhin mitte tuttavatega koos tegemisele suvalist ideed, vaid ideed, mis meeldib ja vastavalt sellele koonduda huvitatud inimestega 🙂
* Kanalisse kirjutage ainult inimesed, kes pakuvad projekti ideid ja kui meeldib idee, kui ei ole Threadi tekitatud, siis parem nupp ja `Create Thread` ja kirjutage sinna alla, kui olete huvitatud.
* Töötame first-come-first-serve basis ehk kes 2 inimest jõuavad enne kirjutada, siis saavad liituda projektiga.

ℹ️ **Võite ka täiesti oma liikmetega eraldi teha projekti, mõte on siis lihtsalt selles, et pakkuda ka alternatiiv viisi kuidas meeskondi moodustada.**

## 1. november on deadline projekti idee ja informatsiooni esitamiseks
‼️ **Selleks, et jätkata aine sooritamist on vaja alustada projektiga, tegemata jätmine tähendab aine läbi kukkumist. Ei pea ise esitama, aga peab olema kusagil projektis ja üks teist peab `#projects` kanalis esitama idee hiljemalt 1. novembril**
* `Mis see tähendab?` Vaja olla 3 liikmelises meeskonnas, projekti pealkiri, idee kirjeldus on välja valitud ning koos autoritega (täisnimed + Discordi tagimine) esitatud #projects kanalisse.
* `Võib juba projektiga alustada?` Enne vaja minu rohelist heakskiidu linnukest. Võimalik, et projekt liiga kerge/raske ja vaja veel täpsustada detaile, teen teie jaoks eraldi Discordi kanalid ja saan seal teiega täpsemalt suhelda sellel teemal.
* `Kui roheline linnuke saadud, mis siis?` [Projekti tegemise sammud](https://github.com/rakenduste-programmeerimine-2023/.github/edit/main/profile/README.md#projekti-tegemise-sammud)

## Projekti töö tegemise workflow

### Projekti tegemise sammud
1. Esitada õigeks ajaks (ühe rühmaliikme poolt) idee `1. novembriks`
2. Saada `roheline linnuke`, teen valmis teile repo, teen setupi, saate õigused ja saate pihta hakata
3. Esimesena teha kogu oma projektist `low-fidelity wireframe` ja lisada `README` faili projekti ülevaade
4. Panna kirja `kõik funktsionaalsused` `README` faili, mida teie projektis võib arendamist vajaminevat
5. Vastavalt funktsionaalsustele on vaja luua `GitHub issue`-d (taskid)
6. Võite ka luua uued labelid näiteks `frontend`, `disain`, `backend` jms
7. On vaja luua vähemalt `4 milestone`-i ehk nagu `nädalased sprindid` (`06.11-13.11`, `13.11-20.11`, `20.11-27.11`, `27.11-04.12`)
8. Pärast `4 sprinti` on teil veel aega kuni eksamini fixida võimalikke buge ja teha vajalikke korrektuure.
9. Iga `milestone`-i alla on vaja minimaalselt `10 issue`-d
10. Kui tekivad projekti tegemise käigus `bugid`, siis teha eraldi issue labeliiga `bug`
11. Iga nädal on vaja kindlasti teha `vähemalt 1 stand-up` ehk vajalik vähemalt kord nädalas enda projekti panustada
* **Tagantjärgi `stand-up`id arvesse ei lähe**
* `Stand-up`id peaksid vastama ka commitide tegemisele ehk mitte teha arendust kui stand-up on puudu
* `Stand-up`e on vaja teha igakord kui alustate arendusega ja neid võib teha ükskõik kui palju nädalas, aga minimaalselt 1 kord

**Kirjalikud `stand-up`id enda projekti kanalis vastates kolmele küsimusele**
* Mida tegid eile? (võib issued pealkirjad ka olla)
* Mida teed täna? (konkreetsus ja lühisus tähtis)
* Kas on mingisugused takistused, mis ei lase Sul programmeerida?

12. Kui kõik see arusaadav ja alustate tööd, siis igaüks isiklikult kirjutab enda Discordi kanalisse `"Eeltöö tehtud ja alustan arendusega"` peamiselt teada andmiseks, et olete kursis kõigega, mis teha vaja on ja olete kõik ära teinud korrektselt (õige arv milestone-e, issued tehtud, minimaalne arv issue-sid iga milestone all)

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
* Tehke väikseid (kompaktseid) committe ja tihemini 
* **➡️ Tutvuda: https://www.conventionalcommits.org/en/v1.0.0/**
* Hakata kasutama conventioni järgi committe projektis (nt `feat: add Login component`) `Message`vormi kohta info: https://github.com/angular/angular/blob/22b96b9/CONTRIBUTING.md#subject
* Rohkem infot: https://blogs.halodoc.io/code-version-best-practices-with-clean-commit-formats/

#### Kuidas deployda?
* Vercelil on organisatsiooni jaoks paid plan selleks, et deployda ja me ei hakka deployma läbi organisatsiooni 🙂
* Deploymiseks vaja forkida grupitöö enda isikliku konto alla ja kasutada enda isiklikku repot läbi Verceli, et deployda 🙂 
* **Kuidas?** ➡️ Lugeda ja tutvuda: https://stefanbauer.me/articles/how-to-keep-your-git-fork-up-to-date ja https://www.atlassian.com/git/tutorials/git-forks-and-upstreams

## Üldinfo

### Eksami ajad
* **Põhieksam on viimasel tunnil ehk 13.12.2023**
* **Järeleksam on 17.01.2024 kell 08:15**

Kursuse WIKI: [https://github.com/rakenduste-programmeerimine-2023/.github/wiki](https://github.com/rakenduste-programmeerimine-2023/.github/wiki)

Discord: [https://discord.gg/rYgFd6VH](https://discord.gg/nftVkkQ6Gg)

Kodused ja tunnitööd: [https://github.com/rakenduste-programmeerimine-2023/.github/wiki/homework](https://github.com/rakenduste-programmeerimine-2023/.github/wiki/homework)
