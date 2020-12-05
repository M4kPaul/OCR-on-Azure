### Opis projektu: 

  Serwis umożliwiający archiwizację i kategoryzację paragonów. Użytkownik wysyła zdjęcie do serwisu, które zostaje zapisane do bloba, a następnie przetworzone przez form recognizer. Odpowiednie dane zostają wykorzystane do kategoryzacji i sortowania danych. Użytkownik ma dostęp do wyszukiwarki wgranych paragonów oraz wgląd w ogólne statystyki prezentowane przy pomocy wykresów z Power BI. 

#### Przedstawienie zespołu z zlinkowaniem osoby do jej/jego konta na GitHub 

* Makowski Paweł: https://github.com/M4kPaul 

* Sulima Bartosz: https://github.com/sulimab 

#### Opis funkcjonalności (- co będziecie realizować) 

* Przesyłanie zdjęć do blob 

* Wyciągnięcie danych ze zdjęć 

* Kategoryzacja danych 

* Dostęp do katalogu ze zdjęciami i danymi 

* Moduł wyszukiwania 

* Generacja statystyk/wykresów 

#### Architektura (diagram) (- jakie serwisy Azurowe wybierzenie) 

![Azure Architecture](../../blob/master/images/architecture.png)

* Azure logic apps, zamiast callback do orchiestracji pracy: wykorzystać for fun/do nauki (często używane, porównać z logic functions) 

* Usunąć EventGrid 

#### Wybrany stos technologiczny (- jakie inne technologie użyjecie) 

* Form recognizer - https://docs.microsoft.com/pl-pl/azure/cognitive-services/form-recognizer/overview?tabs=v2-1 

* Na początku CosmosDB, **uwaga na koszty** 

* Azure functions 


###### Dodatki, do sprawdzenia: 

* Azure Cognitive Search - https://azure.microsoft.com/pl-pl/services/search/ 

* IntelligentKiosk - https://github.com/microsoft/Cognitive-Samples-IntelligentKiosk 

* https://jfk-demo.azurewebsites.net/ (https://github.com/microsoft/AzureSearch_JFK_Files) 


#### Rozpiska zadań do zrealizowania oraz przypisanie osoby odpowiedzialnej za dane zadanie (- jakie zadania będą realizowane, przez kogo i kiedy) 

* Spotkanie grudzień/styczeń 

* Oddanie raport video/ostani tydzień styczeń (również dla reszty grupy): 

    * Jak co działa, jakie modele, jakie problemy czy działa tylko usa 

    * Część AI, jak dotrenować
    
    * Sprzedać info o serwisach 

    * Diagram PowerBI + Form Recognizer 
