# Odobleja-Programming-Language

   Odobleja este un limbaj de programare demonstrativ creat de Simion T. Acesta nu are foarte multe functionalitati si aplicatii in viata reala si este pur demonstrativ. Numele de *ODOBLEJA* vine de la parintele ciberneticii, Stefan Odobleja. Acesta poate fi utilizat folosind ODOBLEJA RUNNER care este trecut cu numele **odobleja.exe**.

## Cum programez? Sintaxa:
 1. ## Setarea unei variabile:
    1. ##   Pentru a seta o variabila la o valoare numerica:
      ```odobleja
          var x 12
       ```
      x=12

      *var* este pe pozitia 1; numele variabilei este pe pozitia 2(poate sa fie si un numar; obligatoriu diferita de *_* ); valoarea numerica a variabilei este pe pozitia 3.

    2. ##   Pentru a seta o variabila la o valoare alfanumerica:
   
       ```odobleja
       var #txt# x |Exemplu de text|
       ```
       *var* este pe pozitia 1; #txt# este pe pozitia 2; numele variabilei este pe pozitia 3; textul este pe pozitia 4 cuprins intre 2 |
    3. ##   Pentru a seta o variabila la o valoare speciala:

       Pe pozitia 2 se pune *_* . 

      1. ###     Pentru adunare

      ```odobleja
          var z _ x + y   
       ```
       z=x+y

       ![](https://github.com/RoAstro/Odobleja-Programming-Language-/blob/main/plus.png?raw=true)


       2. ###     Pentru scadere

      ```odobleja
          var z _ x - y   
       ```
       z=x-y

       3.  ###     Pentru inmultire

      ```odobleja
          var z _ x * y   
       ```
       z=x*y

       4. ###     Pentru impartire

      ```odobleja
          var z _ x / y   
       ```
       z=x/y

       5. ###     Pentru impartire fara rest(div)

      ```odobleja
          var z _ x // y   
       ```
       z=x div y

       6. ###     Pentru rest(mod)

      ```odobleja
          var z _ x % y    
       ```
       z=x mod y

       7. ###     Pentru puteri

      ```odobleja
          var z _ x ** y   
       ```
       z=x^y

       8. ###     Pentru radacina patrata

      ```odobleja
          var z _ /// x     
       ```
       z=sqrt(x)

       9. ###     Pentru egalitate

      ```
          var z _ x = y    
       ```
      
       Daca *x=y*, atunci z=1; daca *x≠y*, atunci z = 0.


    ![img](https://github.com/RoAstro/Odobleja-Programming-Language-/blob/main/egal.png?raw=true)


      10. ###     Pentru inegalitate(mai mare)

      ```odobleja
          var z _ x > y    
       ```
       Daca *x>y*, atunci z=1; daca *x<y*, atunci z = 0.

      11.  ###     Pentru inegalitate(mai mic)

      ```odobleja
          var z _ x < y    
       ```
       Daca *x<y*, atunci z=1; daca *x>y*, atunci z = 0.

    Numele unei variabile poate fi si un numar. De exemplu:
    ```
    var 15 4
     ```

      ![](https://github.com/RoAstro/Odobleja-Programming-Language-/blob/main/var%20nr.png?raw=true)


  3. # Conditia **daca** (**if**)
     ```
     ? x var y 18
     ```
     Daca x=1 => y=18
     
     Daca x=0 => nu se intampla nimic

     ![](https://github.com/RoAstro/Odobleja-Programming-Language-/blob/main/daca.png?raw=true)
     
  4. # Conditia **daca NU** (**if NOT**)
     ```
     
     ?! x var y 45
     ```
     Daca x=1 => nu se intampla nimic
     
     Daca x=0 => y=45
  5. # Bucla
     ```odobleja
     oo n;
     -actiune-
     #oostop;
     ```
     Se incepe cu oo n; .Pe n il inlocuiti cu numele variabilei care contine numarul de repetitii. In loc de -actiune- puneti comenzile pe care doriti sa le repetati. Dupa ultima comanda care trebuie repetata se pune #oostop; .
  7. # Deschiderea unui fisier care contine codul pe care doriti sa il rulati
     ```odobleja
     #r fisier.odblj
     ```
     In loc de fisier.odblj puneti numele fisierului.



Pentru a afisa toate variabilele inroduceti **#var** in cod.
![](https://github.com/RoAstro/Odobleja-Programming-Language-/blob/main/%23var.png?raw=true)

Intre fiecare comanda se pune **;**

Ultima comanda este **out**

Pentru a afisa o anumita variabila (ex: z), scrieti **afi z**



Exemplu de cod pentru a calcula primele max=10 numere din sirul lui Fibonacci:

```odobleja
var 0 0;
var 1 1;
var n 10;
var num1 0;
var num2 1;
var _ urm num2 + 0;
var i 1;
var max 10;
### Fiecare numar din sirul lui Fibonacci este suma celor 2 numere Fibonacci anterioare;
oo max;
afi urm;
var _ i i + 1;
var _ num1 num2 + 0;
var _ num2 urm + 0;
var _ urm num1 + num2;
#oostop;
out;
```
     
     
        
