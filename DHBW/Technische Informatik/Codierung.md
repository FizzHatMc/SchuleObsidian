1. Codierung 
    

Definition (Codierung): Darstellung von Informationen mit einen  Symbol oder einer Symbolfolge, wobei die Symbole einen "Alphabet" entnommen sind. 

Definition(Alphabet): ist eine endliche Symbolmenge 

Hinweis: Bei analoger Ursprungsinformation ist Codierung immer mit einer Digitalisierung verbunden.   

Es gibt unterschiedliche Arten von Codierung 

1. Zahlencodierung: Darstellung von Zahlenwerten 
    
2. Zeichencodierung: Darstellung von Zeichen einer Schriftsprache 
    
3. Anwendungscodierung: Darstellung von Informationen die einem bestimmten Anwendungsbereich zugeordnet sind 
    
4. Verschlüsselung: Art von umcodierung, bei welcher (im Gegensatz zu allen anderen Codierung) die Ursprungsinfo (nicht ohne Kenntnis des "Schlüssels") erkennbar sein soll. 
    
5. Kompression: Art von umcodierung, bei welcher die Datenmenge reduziert werden soll. 
    
6. Signalcodierung: Darstellung von Abstrakten Informationen als Signal oder Signalfolge wobei ein Signal eine physisch messbare Größe ist.  
    

=> wichtig zur Speicherung oder Übertragung von Informationen in oder zwischen digitalen Systemen 

Zeichencodierung: 

ASCII ( ~1960): Alphabet = {0,1,..127}, 

Also 128 verschiedene Symbole  

- Genau 128 verschiedene darstellbare Schriftzeichen, da jedes Schriftzeichen auf ein Symbol abgebildet wird 
    
- Enthält Buchstaben, Satzzeichen, Sonderzeichen… 
    

Aber z.B. keine Umlaute oder andere nationale Sonderzeichen, 

(z.B beim Ä, â ê) 

ISO8859-x (~1990): Alphabet = {0,1,..,255}, 

Also 256 verschiedene Symbole 

- Für verschiedene Sprachregionen gibt es unterschiedliche varianten 
    

ISO8859-1 : Westeuropa (früher) bzw -15 (heute) 

      -2 : Mitteleuropa 

      -5 : kyrillisch 

      -3 : asiatisch 

- Problem: Keine Variante für mehrere Sprachen (z.b. Chinesisch, japanisch indisch, …) außerdem keine verschiedenen Sonderzeichen aus unterschiedlichen Varianten gleichzeitig nutzbar 
    

Unicode (2. Hälfte 199 -er Jahre) 

- Anspruch, die Schriftzeichen aller existierenden damaligen und zukünftigen 61Schriftsprachen darstellen zu können 
    
- potentiell unendlich viele Schriftzeichen 
    
- Notwendig ist eine konkrete Unicode Transfer Codierung: 
    
    z.B. UTF-8 Alphabet = {0,…,255} 
    
           UTF-16 Alphabet = {0,…,65535} 
    
           UTF-32 Alphabet = {0-2³²-1} 
    
- Dargestellt wird das Schriftzeichen durch eine Symbolfolge,  
    

Wobei (mindestens) ein Symbol dafür reserviert ist, 

Anzuzeigen, dass xx mindestens ein weites Symbol in der Symbolfolge für das Schriftzeichen folgt! 

- Damit lassen sich durch immer längere Symbolfolgen beliebig viele weitere Schriftzeichen darstellen! 
    

Abhängig von den verwendeten Schriftzeichen unterscheiden sich die Codierungen im UTF-8, 16 ,… in der Resultierenden Daten menge

