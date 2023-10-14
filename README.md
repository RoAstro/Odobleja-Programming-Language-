# Odobleja-Programming-Language

   Odobleja este un limbaj de programare demonstrativ creat de Simion T. Acesta nu are foarte multe functionalitati si aplicatii in viata reala si este pur demonstrativ. Numele de *ODOBLEJA* vine de la parintele ciberneticii, Stefan Odobleja. Acesta poate fi utilizat folosind ODOBLEJA RUNNER care este trecut cu numele **odobleja.exe**.

## Cum programez- sintaxa:
 1. ## Setarea unei variabile:
    ##   Pentru a seta o variabila la o valoare numerica:
      ```odobleja
          var x 12 // x=12
       ```
      *var* este pe pozitia 1; numele variabilei este pe pozitia 2(poate sa fie si un numar; obligatoriu diferita de *_* ); valoarea numerica a variabilei este pe pozitia 3
      ##   Pentru a seta o variabila la o valoare speciala:

         Pe pozitia 2 se pune _ 

       ##     Pentru adunare
      ```odobleja
          var z _ x + y   
       ```
      z=x+y
       ##     Pentru scadere
      ```odobleja
          var z _ x - y   
       ```
      z=x-y
       ##     Pentru inmultire
      ```odobleja
          var z _ x * y   
       ```
      z=x*y
       ##     Pentru impartire
      ```odobleja
          var z _ x / y   
       ```
      z=x/y
       ##     Pentru impartire fara rest(div)
      ```odobleja
          var z _ x // y   
       ```
      z=x div y
       ##     Pentru rest(mod)
      ```odobleja
          var z _ x % y    
       ```
      z=x mod y
       ##     Pentru puteri
      ```odobleja
          var z _ x ** y   
       ```
      z=x^y
       ##     Pentru radacina patrata
      ```odobleja
          var z _ x     
       ```
      z=sqrt(x)
       ##     Pentru egalitate
      ```odobleja
          var z _ x = y    
       ```
      Daca *x=y*, atunci z=1; daca *x≠y*, atunci z = 0.
       ##     Pentru inegalitate(mai mare)
      ```odobleja
          var z _ x > y    
       ```
      Daca *x>y*, atunci z=1; daca *x<y*, atunci z = 0.
       ##     Pentru inegalitate(mai mic)
      ```odobleja
          var z _ x < y    
       ```
      Daca *x<y*, atunci z=1; daca *x>y*, atunci z = 0.
