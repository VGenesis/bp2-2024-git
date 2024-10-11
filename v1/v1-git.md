#   Uvod u Git

4 vrste objekata:
-   blob -      fajl
-   tree -      direktorijum
-   commit -    revizija
-   tag -       labela 

Svaki objekat definisan je 40-cifrenim hex brojem koji sadrži 
SHA-1 hash objekta

Commit se sastoji od:
-   identifikatora stable
-   nula ili više roditelja
-   
-   autora commit-a
-   log poruke

Git repozitorijum je kolekcija referenci:
-   referenca je pokazivač na objekat
-   repozitorijum skladišti usmereni aciklični graf objekata
-   git prati istoriju celog projekta, odnosno repozitorijuma

Git fajlovi:
-   README          - opis repozitorijuma
-   .gitignore      - spisak fajlova i direktorijuma koje ne treba pratiti

Komande:
-   git init                - kreira nov git repo
-   git add                 - dodaje fajlove na sledeći commit
-   git commit              - pravi novi commit sa dodatim fajlovima
-   git clone               - copira repozitorijum sa GitHub-a
-   git push                - šalje commit na GitHub
-   git pull                - ažurira lokalni repozitorijum kopiranjem
                              GitHub repozitorijuma
-   git remote add origin   - sets the remote GitHub repozitory
-   git branch              - prikazuje sve grane repoyitorijuma
-   git branch <branch>     - pravi novu granu <branch>
-   git checkout <branch>   - prebacujemo se na granu
-   git merge               - spajanje dve grane; spojene grane se ne brišu
