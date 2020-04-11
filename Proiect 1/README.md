### Proiect 1

## Pentru a configura Hostul Virtual

1. intrăm în:

    ```
    xampp\apache\conf\extra\httpd-vhosts.conf
    ```
   
   adaugăm la finalul fișierului:
   ```
   <VirtualHost *:80>
       DocumentRoot "C:\xampp\htdocs\BazeDeDate\Proiect 1"
       ServerName proiect1.bd
   </VirtualHost>
   ```
3. intrăm în:
    ```
    C:\Windows\System32\drivers\etc\hosts
    ```
    adaugăm la finalul documentului:
    ```
   127.0.0.1 proiect1.bd 
   ```   
    

## Pentru a configura Baza de Date:

1. intrăm în:

    ```
    config\init\poem_translator.sql
    ```

2. copiem tot conținutul și creăm o Bază de date MySQL cu numele __poem_translator__.
3. adăugăm la baza de date și un user, pentru accesarea acesteia, codul se găsește în:

    ```
    config\init\PT_USER for poem_translator.sql
    ```


## Pentru a testa proiectul:

Intrăm la adresa: [http://proiect1.bd](http://proiect1.bd/)

Conturi de test:

- Ca utilizator:
```
Email: rrazvan.rraducanu@gmail.com
Parola: parola
```

- Ca admin:
```
Email: admin@poem-translator.bd
Parola: admin
```