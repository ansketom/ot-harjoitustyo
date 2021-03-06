# Ruokasovellus
Ruokasovellus on sovellus, jonka avulla käyttäjä voi laskea, että kuinka paljon hän sai päivän
 aikana energiaa ja eri makroravinteita sekä vettä. Laskenta tapahtuu sovellukseen 
aiemmin tallennetuista ruoka-aineista koostettuja aterioita yhteen laskemalla.  
    
## Dokumentaatio

[Käyttöohje](https://github.com/ansketom/ot-harjoitustyo/blob/master/Dokumentointi/Kayttoohje.md)    
[Vaatimusmäärittely](https://github.com/ansketom/ot-harjoitustyo/blob/master/Dokumentointi/vaatimusmaarittely.md)    
[Arkkitehtuurikuvaus](https://github.com/ansketom/ot-harjoitustyo/blob/master/Dokumentointi/Arkkitehtuurikuvaus.md)    
[Työaikakirjanpito](https://github.com/ansketom/ot-harjoitustyo/blob/master/Dokumentointi/tyoaikakirjanpito.md)    

## Releaset
[viikon 6 release](https://github.com/ansketom/ot-harjoitustyo/releases/tag/Viikko6)    
[viikon 7 release](https://github.com/ansketom/ot-harjoitustyo/releases/tag/Viikko7) 
 

## Komentorivikomennot

### Ohjelman käyttö
Komentoriviltä [juurikansiosta](https://github.com/ansketom/ot-harjoitustyo/tree/master/ruokasovellus)
(..ot-harjoitustyo\ruokasovellus) komennolla  
```    mvn compile exec:java -Dexec.mainClass=ruokasovellus.Main    ```  

### Testaus
#### Testit saa suoritettua komennolla  
```    mvn test    ```  
#### Testikattavuusraportin saa luotua komennolla  
```    mvn test jacoco:report    ```  
  
#### Checkstyleraportin tekeminen 
```    mvn jxr:jxr checkstyle:checkstyle    ```    
#### JavaDoc
```    mvn javadoc:javadoc    ```    
#### Suoritettavan jar:n generointi    
```    mvn package    ```




