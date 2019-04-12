# UQ Awaz Ambiri

**Téren Öginish (Deep Learning)** téxniki arqiliq Tékistni Awazgha Aylandurush (Text To Speech) tetqiqatida Uyghurche Awaz Ambirining bolmasliqidek boshluqni toldurushni meqset qilip yasaldi. Bu awaz ambirini ishlitishte héchqandaq cheklime yoq. Peqetla ishletkende **«UQ Awaz Ambiri»** ishlitildi dégenni maqale yaki mehsulatqa qoshushni iltimas qilimen.</br>
Mezkur awaz ambiri **Exmed Pida’iy** oqughan, **Merhum Muhemmed Sali Damolla** terjime qilghan **Uyghurche Qur’an Kerimining** awaz we tékist höjjiti asasida yasaldi. Merhum Muhemmed Sali Damollining yatqan yéri jennet bolsun, Exmed Pida’iy ependige kop rehmet. Bularning emgiki bolmighan bolsa, bu ambarmu yasalmighan, yuqirida tilgha alghan boshluq, boshluq péti qéliwergen bolar idi.
Bu awaz ambiri 16187 dane awaz höjjiti we unigha mas tékisttin terkib tapqan bolup, awazning eng uzuni 10 sékunt. Jem’iy awazning uzunluqi 28 sa’et (her bir awazning aldi keynidiki jimliqmu buning ichide).

## Höjjetning pichimi

1.	Tékist höjjiti (metadata.csv) UTF-8 kod sistémisida saqlanghan bolup, her bir qur bir awaz höjjitige mas kélidu. Her bir qurda jem’iy 4 bölek bolup, 
 -	Birinchi bölek: höjjetning kimliki. uninggha. wav ni qoshsa awaz höjjitining ismi hasil bolidu.
 -	Ikkinchi bölek: Uyghur Ereb Yéziqi (UEY) diki tékisti
 -	Üchinchi bölek: Uyghur Latin Yéziqi (ULY) diki tékisti.
 -	Tötinchi bölek: Uyghur Slawyan Yéziqi (USY) diki tékisti.

2.	Awaz höjjiti (wavs) qisquchida bolup, taq qanal, 16 bitliq PCM WAV pichimida saqlanghan. Sample rate 22050 Hz.

## Bashqilar:
Uyghurche Qur’an kerimining awazliq höjjiti(114 dane) ni programma arqiliq 10 sékunttin chong bolmighan parchigha bölgendin kéyin, özüm yasighan **[AwazAmbiriQorali](https://github.com/gheyret/AwazAmbiriQorali)** (awaz we tékistni maslashturush) arqiliq, Qur’an Kerimining Uyghurche tékistni ishlitip, awaz bilen tékistni birmu bir maslashturup yasap chiqildi. Bu ishqa Dilshat Abla, Osman Tursun, Rustem Mexet qérindashlirimiz yardemde boldi. Andin özüm bashtin axir hemmini yene bir qétim tekshürüp chiqtim(Bir awaz bilen shuninggha mas kélidighan qur birdekmu emesmu). Yuqiriqi 3 qérindishimizgha chin könglümdin rehmet éytimen.</br>
Tékist terkibidiki sanlar pütünley oqulushigha aylanduruldi (12 dégenni on ikki dep). Tetqiqatchilargha qulay bolsun üchün tékisti Uyghurchining UEY,ULY,USY din ibaret 3 xil shekilide teminlendi. 

Yene In’glizche The LJ Speech Dataset(https://keithito.com/LJ-Speech-Dataset/) bilen oxshash qurulma ishlitildi. 
