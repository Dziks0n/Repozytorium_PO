# Laboratorium 4 Narzędzia informatyczne w praktyce inżynierskiej

- W tym zadaniu opisane zostały wszelkie dokonane zmiany wykonane w środowisku GIT BASH

## Spis treści

1. [Komendy i Commity](#komendyicommity)
2. [Akcje](#akcje)

##Komendy i Commity
- Zadanie 1
	- Wprowadzono komendę git config --global user.name "Marcin Dzik"
		- Komenda ta służy do wpisania nazwy użytkownika.
	- Wprowadzono komendę git config --global user.email "marcin.dzik@student.po.edu.pl"
		- Komenda służy do wpisania adresu email użytkownika.
- Zadanie 2
	- Wprowadzono komendę mkdir repository_lab4
		- Komenda ta utworzyła folder o nazwie repository_lab4
	- Wprowadzono komendę cd repository_lab4
		- Komenda przenosi użytkownika do folderu
	- Wprowadzenie komendy git init
		- Zainicjowanie repozytorium
- Zadanie 3
	- Utworzenie plików ręcznie w repozytorium
- Zadanie 4
	- Wprowadzono komendę git add newfile.txt
		- Utworzono nowy plik o nazwie newfile.txt
		- Utworzono commita za pomocą komendy git commit -m "Dodano nowy plik txt"
	- Wprowadzono komendę git rm exampletxt5.txt
		- Usunięto plik o powyższej nazwie
		- Utworzono commita: git commit -m "Usunięto plik exampletxt5.txt"
	- Wprowadzono komendę git mv newfile.txt nowyPlik.txt
		- Zmieniono nazwę pliku newfile.txt na nowyPlik.txt
		- Utworzono commita: git commit -m "Zmiana nazwy pliku newfile.txt na nowyPlik.txt"
- Zadanie 5
	- Wprowadzono komendę git log
		-Komenda wyświetliła listę wszystkich commitów na danej gałęzi
- Zadanie 6
	- Wprowadzono komendę git status
		- Komenda wyświetla status plików i repozytorium
	- Wprowadzono komendę touch .gitignore
		- Komenda utworzyła plik .gitignore w repozytorium, w którym ma ignorować plik exampletxt1.txt w repozytorium
- Zadanie 7
	- Sposoby na wyświetlenie historii commitów za pomocą komend:
		- git log
			- Wyświelenie historii wszystkich commitów
		- git show "id_commita"
			- Wyświetlenie konkretnego commita za pomocą danego identyfikatora commita
		- gitk
			- Wyświetla okno historii commitów jako graficzny interfejs użytkownika
- Zadanie 8
	- Wprowadzono komendę git checkout -b nowaGalaz
		- Utworzono nową gałąź i przełączono się na nią
	- Wprowadzono komendę git add .
		- Zatwierdzono zmiany dla nowej gałęzi
		- Utworzono commita git commit -m "Dodanie nowej gałęzi"
	- Wprowadzenie komendy git checkout master
		- Powrót na główna gałęź
	- Wprowadzenie komendy git merge nowaGalaz
		- Połączenie dwóch gałęzi
		- Utworzono commita git commit -m "Połączenie gałęzi nowaGalaz z master"
- Pozostałe rzeczy:
	- Polecenie config zostało wykorzystane przy konfiguracji nazwy i adresu email
	- Polecenie init zostało wykorzystane do zainicjowania repozytorium
	- Polecenie add zostało wykorzystane przy dodawaniu nowych plików
	- Polecenie commit zostało wykorzystane przy tworzeniu rewizji, czyli do zatwierdzania zmian w repozytorium
	- Polecenie status zostało wykorzystane do sprawdzenia repozytorium
	- Polecenie diff zostało wykorzystane do sprawdzenia różnic między commitami za pomocą ich identyfikatora
	- Polecenie rm posłużyło się usunięcia pliku exampletxt5.txt
	- Polecenie mv zostało wykorzystane do zmiany nazwy pliku
	- Polecenie log pozwoliło na wyświetlenie historii commitów
	- Polecenie checkout umożliwiło przełączanie się między dostępnymi gałęziami
	- Polecenie restore zostało wykorzystane do przywrócenia usuniętego pliku exampletxt5.txt
	- Polecenie reflog zostało wykorzystane do wyświtlenia logu zmian w HEAD w repozytorium
	- Polecenie brach umozliwiło utworzenie nowej gałęzi nowaGalaz
	- Polecenie merge zostało wykorzystane do połączenia obydwu gałęzi
	
##Akcje
- Utworzono 5 przykładowych plików tekstowych w repozytorium ręcznie