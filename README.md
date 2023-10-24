
# Aplikacja Notatnika

Projekt aplikacji notatnika

## Instrukcja uruchomienia aplikacji
Jako, że aplikacja działa lokalnie należy:
1. Pobrać Node.js z głównej strony https://nodejs.org/en
![nodejs](ss/nodejs.PNG)
    - następnie sprawdzić w środowisku czy jest zainstalowany komendą:
    ```bash
      node -v
    ```
    - następnie zainstalować NPM komendą:
    ```bash
      node i npm
    ``` 
    - sprawdzić czy jest zainstalowany:
    ```bash
      npm -v
    ```
    - zainstalować zależności w folderze **backend** jak i w folderze **frontend** komendą
    ```bash
      npm install
    ```

2. Pobrać MongoDB Community Server z tej strony: https://www.mongodb.com/try/download/community 

    ![mongoDB](ss/mongoDB.PNG)
- następnie w instalatorze wybrać typ instalacji Custom
![install](ss/install.PNG)

- następnie wybrać ścieżkę najlepiej jeśli to będzie na "Users/user" i stworzyć tam folder mongodb
![install](ss/install2.PNG)

- następnie ukaże się nam informacja o tym, że system zarejestruje nowy serwis o nazwie MongoDB za pomocą którego będziemy odpalać bazę danych. Jest tam także podany folder w którym będą przechowywane dane naszej bazy danych jest nim folder "data"

  ![install3](ss/install3.PNG)

- na koniec opcjonalnie możemy zainstalować MongoDB Compass za pomocą którego będziemy mogli za pomocą interfejsu graficznego edytować naszą bazę danych

  ![install4](ss/install4.PNG) 

- podczas instalacji instalator oznajmi nas o zmianie ścieżki gdzie ma się znajdować nasz program bazodanowy, należy kliknąć **Ignore**
- po ukończonej instalacji wchodzimy w wiersz poleceń wchodzimy w folder z naszą bazą danych i wpisujemy poniższy kod

  ![cmd](ss/cmd.PNG)

- informacja o udanym połączeniu z MongoDB z czego domyślny port oraz adres localhost przedstawia poniższy screen
![cmd2](ss/cmd2.PNG)
- ważne jest aby nie wyłączać terminala gdy korzystamy z aplikacji
3. Aby aplikacja poprawnie działa trzeba również włączyć serwer node.js w konsoli CMD najlepiej w środowisku Visual Studio Code
![cmdVSC](ss/cmdVSC.PNG)
4. Trzeba również odpalić React Development Server w PowerShell'u 
![psVSC](ss/psVSC.PNG)
5. Gdy wszystko poprawnie uruchomimy powinna odpalić się nam aplikacja pod adresem http://localhost:3000/