# ShapesDataset

Ovo je dataset koji se koristi za potrebe projekta iz kolegija Ugradbeni računalni sustavi.

Dataset možete git cloneat ili skinit u zipu, tak svejedno.

## labelImg
Najprije je potrebno instalirati aplikaciju [labelImg](https://github.com/tzutalin/labelImg).
Aplikacija ovisi o nekim stvarima pa je i to potrebno instalirati. Sve piše tamo. 

Kad se instalira, potrebno je samo jednu stvar promijeniti. Ući u mapu labelImg/data i u datoteci predefined_classes.txt obrisati sve klase koje pišu unutra i napisati u zasebne redove (tim redosljedom):
* valjak
* piramida
* kocka
* kugla
* kvadar


## Slike
![alt text](https://i.imgur.com/C4cep27.png)
Ovako nekako bi trebalo izgledati sučelje labelImg-a. Button _Open Dir_ otvara mapu u kojoj se nalaze sve slike za neki objekt. _Change Save Dir_ omogućava spremanje slika u neku mapu. **Slike spremati u odgovarajuće mape**. Znači kocka0001.txt treba biti spremljena u mapu kocka koja se može kreirati bilo gdje. **Ne mijenijati imena datoteka!**

S lijeve strane se ima i button za spremanje formata. Format treba biti **YOLO**. Drugi je PascalVOC i on nam ne odgovara.

Slike spremiti na button _Save_, iduća slika _Next Image_, stvaranje kvadrata _Create\nRectBox_. Ugl. kontate. 

Za sva pitanja i upite, znate gdje ćete me nać. Hehe poz i glhf.
