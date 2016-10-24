## Laboratoria  2016/17

Terminy rozliczania się z zadań i projektu na egzamin:

| Zadanie | Opis       | Ostateczny termin |
|--------:|----------- |------------------:|
| 1       | zaliczenie | 13.11.2016        |
| 2       | egzamin    | 08.01.2017        |

Rozwiązania zadań umieszczamy w repozytorium. Oto przykładowe repozytorium
[Szablon repozytorium dla Ruby+RSpec](https://github.com/egzamin/solutions-tar).

*Uwaga:*  Nierozliczenie się w terminie z zadań skutkuje obniżeniem oceny.

❖

Robimy porządki w katalogu domowym:

* `quota`
* `ncdu`

Potrzebne gemy instalujemy w katalogu **/var/sandbox/**  zob.
[Miejsce na dysku Sigma + Laboratoria](https://inf.ug.edu.pl/aktualizacje-serwera-sigma)

<!--
Może się przydać:

* [transfer.sh](https://transfer.sh/) –
  share your files

```sh
transfer() {
  curl --upload-file $1 https://transfer.sh/$(basename $1);
}
alias transfer=transfer
```
-->

### Zadanie 0. [Zaczynamy]

Założyć repozytorium na zadania. W repozytorium utworzyć ściągawkę
z wybranych metod / składni języka Ruby.

Można się wzorować na tych ściągawkach:

* [Learn X in Y minutes](http://learnxinyminutes.com/docs/ruby/):
  * Learn X=Ruby Hash in Y=? minutes
  * Learn X=Ruby Arrays in Y=? minutes
  * Learn X=Ruby Enumerable in Y=? minutes
* Leigh Halliday.
  [The Simple Yet Powerful Ruby Enumerable Module](https://blog.codeship.com/the-enumerable-module/)


### Zadanie 1. [Piszemy testy do własnego kodu]

Wiele ciekawych zadań programistycznych można znaleźć w [Google Interview University](https://github.com/jwasham/google-interview-university)  zwłaszcza w sekcji z [Data Structures](https://github.com/jwasham/google-interview-university#data-structures).

Jak pisać i dodawać testy można podejrzeć tutaj:
[03-rspec](labs/03-rspec/)  [04-write_tests](labs/04-write_tests/).


<!--
### 3. Doubles  mocks & stubs

> Integration tests tell **what**’s not working. But they are of no use in<br>
> **guessing where** the problem could be.<br>
> Unit tests are the sole tests that tell you **where** exactly the bug<br>
> is. To draw this information  they must run the method in a mocked<br>
> environment  where all other dependencies are supposed to correctly work.<br>
> <br>
> [What is the difference between integration and unit tests?](http://stackoverflow.com/questions/10752/what-is-the-difference-between-integration-and-unit-tests)

Testy piszemy do swojego kodu  jeśli ma to sens  lub do tego kodu
[06-integration_tests](https://github.com/egzamin/tar/tree/master/labs/06-integration_tests).
W testach jednostkowych użyć doubles/mocków/stubów.
-->

### Zadanie 2. [Piszemy testy do własnego programu]

[Poniżej to tylko przykład. Kod będzie omówiony na wykładzie.]

„Wypożyczalnia Video” (klasyka). To tylko przykład programu na egzamin :sparkling_heart:

*Program oblicza i wypisuje rachunki za wypożyczone filmy.*

Program korzystając z informacji jakie filmy i na jak długo
wypożyczył użytkownik wypisuje rachunek.<br>
Rachunek zależy od tego na jak długo wypożyczono film
i od jego rodzaju. Są trzy rodzaje filmów: zwykłe  dla dzieci
i nowe. Dodatkowo  opłata zależy od tego czy mamy przyznane
punkty za częste wypożyczenia i od tego czy film jest nowy.

*Uwaga:*  Można napisać testy do aplikacji webowej.


## Lista

Legenda:

* gmf – brak Gemfile
* cov – brak coverage
* nef – No examples found

----

### Grupa 1

1. [Lis Marcin](https://github.com/marcinlis0) 24.11
1. [Lubiejewski Kamil](https://github.com/Lubu909/Ruby-lab)
1. [Luszuk Paweł](https://github.com/luszukpawel)
1. [Łąkowski Jakub](https://github.com/kubalakowski)
1. [Łojkowski Wojciech](https://github.com/wlojkowski/)
1. [Makiewicz Adam](https://github.com/adammak2342/Ruby)
1. Mazur Ewelina 24.11
1. [Narożnik Kacper](https://github.com/knaroznik)
1. [Novik Aleksandr](https://github.com/AliaksandrN)
1. Radski, Paweł 
1. Rumanoski Krzysztof 24.11
1. Rutkowski, Mariusz
1. [Sasin Jacek](https://github.com/jsasin)
1. [Sędek Szymon](https://github.com/GSun12)
1. Strójwąs Piotr 24.11
1. [Tejszerska Aleksandra](https://github.com/atejszerska)
1. [Wiśniewski Jakub](https://github.com/jawisniewski)
1. [Zdybel Patryk](https://github.com/DyuQ) 24.11


### Grupa 2

1. [Adler Patryk](https://github.com/adlerpoland/Ruby)
1. [Banaszek Dawid](https://github.com/dbanaszek/tar-1)
1. [Byszof Michał](https://github.com/mbyszof/Ruby_2016-2017)
1. [Cabaj Tomasz](https://github.com/tcabaj/Ruby)
1. [Cwilik Dawid](https://github.com/jodanpotasu/RubyZajecia)
1. [Dziubiński Maciej](https://github.com/mdziub/ruby.git)
1. [Gawin Mateusz](https://github.com/matgawin/ruby-lab)
1. [Gołuński Radosław](https://github.com/RGolun/Ruby)
1. [Jabłoński Jakub](https://github.com/jakjablonski/rubbb)
1. [Jędzierowska Magdalena](https://github.com/MagdalenaJedzierowska/TAR_Projekty)
1. [Kalinowski Damian](https://github.com/lafreak/ruby)
1. [Katovich Darya](https://github.com/dkotowicz/ruby)
1. [Kawa Piotr](https://gitlab.com/aurustius/ruby-project.git)
1. Maksymilian Kicki
1. [Knitter Mateusz](https://github.com/supperbull/RubyMateuszKnitter)
1. [Lewandowski Rafał](https://github.com/alejafiem/projekty-ruby)
1. [Osowska Aleksandra] (https://github.com/aosowska/Ruby)
1. [Pobłocki Patryk](https://github.com/ppoblocki/tar)
1. Radomski Artur
1. Świstun Szymon


### Jaka grupa?


1. Majewski Sebastian
1. Mikucka Julianna
