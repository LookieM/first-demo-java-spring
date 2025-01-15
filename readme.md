First Demo Java Spring
Prosty projekt stworzony w Spring Boot, który umożliwia wyświetlanie podstawowych informacji w przeglądarce oraz obsługę parametrów za pomocą zapytań GET.

Opis projektu
1. Wyświetlenie strony powitalnej
- Pod adresem http://localhost:8080/ zwraca komunikat "Hello World, this is my Spring Controller" (lub inny napis zdefiniowany w kontrolerze).
2. Obsługe parametru /greeting:
- Pod adresem http://localhost:8080/greeting wyświetla stronę HTML (widok Thymeleaf) zawierającą przywitanie.
- przy użyciu ?name pokazuje personalny komunikat



Przykład użycia
Uruchomić aplikacje 
Otworzyc w przegladarce localhost:8080(Zobaczysz stronę z domyślnym tekstem)
Przejdź do http://localhost:8080/greeting?name=cos
Powinieneś zobaczyć stronę z przywitaniem "Hello, cos!".

Technologie
Java 23 (lub wyższa – w zależności od projektu)
Spring Boot 3.4.1
Thymeleaf – do obsługi widoków i renderowania HTML
Maven – do zarządzania zależnościami i budową projektu

Uruchamianie projektu 

Sklonowanie repo
    