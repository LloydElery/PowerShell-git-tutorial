# Terminal
## 1.

    >ls
    Det visar att mappen jag befinner mig i är tom. Alltså dyker ingenting upp.
## 5.

    >cd newFolder
    >ls
## 6.

    >pwd
    C:\Users\Threefiddy\Desktop\terminal-git-tutorial\newFolder>
## 7.

    >echo "Hello from the terminal!" >> newFile.txt
## 9.

    Git används för att spara ner filer lokalt och skapa checkpoints i ditt arbete och din kod. Man kan t.ex. skapa förgreningar i sitt arbete för att säkerställa att ens nya kod inte ställer till det för huvudkoden. Detta kallas för en 'branch'.
## 10.

    1. Modified - Modifierade filer betyder att filerna harändrats men ännu inte commitats till databasen.
    2. Staged - Stageade filer är i stadiet mellan 1 och 3 där de vid nästa commit kommer att inkluderas.
    3. Commited - Commitade filer är filer som har sparats och som nu lagras lokalt på i databasen.
## 12.

    >git init 
    Initialized empty Git repository in C:/Users/Threefiddy/Desktop/terminal-git-tutorial/.git/
## 13

    > echo >> .gitignore
    InputObject[0]: >/newFolder
## 14.

    >git add README.md
    >git add .gitignore
## 15.

    >git status
## 16.

    >git commit -am "README file for the repository"
## 17.

    En git branch används för att skriva kod som vid ett senare tillfälle ska fogas samman med stammen, 'main'. Detta är särskilt bra när det är flera utvecklare som jobbar på samma projekt då de skapar en miljö (branch) som var och en kan jobba i utan att påverka varandras arbete eller stammen, main.
## 18.

    >git branch newBranch
    >git checkout newBranch
## 19.

    >echo >> newFile.txt
    >git add newFile.txt
    >git commit -am "New file to the newBranch"
## 20.

    >git checkout master
    Den syns inte när man skriver >ls
## 21.
# README
## 22.

This is my first GitHub repository and I'm training the use of **Git** and *GitHub.*

## 24.

I'm alsi learning:
- HTML
- CSS
- JavaScript

## 27.



