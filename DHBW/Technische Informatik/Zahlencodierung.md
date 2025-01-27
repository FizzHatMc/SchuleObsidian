-Abzählsysteme
	jedes Symbol hat einen Symbolwert. Der Wert der Zahl ergibt sich aus der dargestelten Symbole.
	
a) Fingerabzählsysteme
		Alphabet = {Finger}
		Symbolwert(Finger) = 1
		
++ Intuitiv, einfach, anschaulich, verständlich
++ Immer "zurhand"
++Extrem einfache Addition und Subtraktion
--Nur beschränkter Wertebereich außerdem bis auf weiteres ganze, nicht negative Zahlen
 
b) einfache Strichliste
		Bspl. Hr Müller  -> ||||||||
				   Fr. Maier  -> ||||||||
		Alphabet = { | }
		Symbolwert(|) = 1
		
++ Intuitiv, einfach, verständlich
++ Schreibwerkzeug notwending
++ Addition extrem einfach
++ Subtraktion erfordert löschmöglichkeit
-- übersichtlicher Wertebereich bis ~ 10
	
c) erweiterte Strichliste
		Alphabet = { | , ||/||}
		Symbolwert(|) = 1
		Symbolwert(||/||) ) = 5

++ relativ einfach, abber ein wenig Komplexer als die einfache Liste
  weitere Regel: Symbole müssen nach Symbolwert sortiert werden.

+- Addition erfordert Umschreiben und Gruppierung
+- Subtraktion erfordert Auflösung von großen Symbolen 
-+ übersichtlicher Wertebereich bis ~ 50 
		
d) Römische Abzählsystem
		Alphabet = {I, V, X, L, C, D, M}
		I: 1 V:5 X:10 L:50 X:100 D:500 M:1000
		+- doch schon recht Schwierung zu verstehen
		+ übersichtlicher Werte bereich
		weitere Regel: Symbol niedrigerem Symbolwert darf auch vor Symbol 
		höheren wertes notiert werden, aber dann wird der Wert abgezogen
		Nur max. 3 Symbole erlaubt
		- Beschränkter (?) Wertebereich bis ca. 4000
		- Rechnen praktisch Unmöglich


- Stellenwertsystem
		Symbole haben wieder einen Symbolwert sowie abhängig von der Position,
		wo sie stehen einen Stellenwert. Symbol und stellenwert müssen zuerst 
		multipliziert und dann erst aufsummiert werden.
		
	a) Dezimalsystem
			Symbole heißen Ziffern
			Alphabet = {0,1,2,3,4,5,6,7,8,9}
			0=0 1=1 2=2 3=3 4=4 5=5 6=6 7=7 8=8 9=9
			
	eine Zahl wird notiert als Folge von Ziffern, eine Folge von n 
	Ziffern heißt n-stellige Zahl
	z(n-1) z(n-2) z(n-3) = z1 z0 = z E {0,1,...,9}
			
	Wert(Z(n-1)...z(0)) = $\sum_{i=0}^{n+1}$
			("Werte Formel")
	$10^i$ ist der Stellenwert der i-ten Ziffern von rechts im Dezimalsystem  		
	+- deutlich komplexer als ein Abzählsystem, aber nach abarbeiten doch gut verständlich
	+- Schreibwerkzeug notwendig
	+- für alle Grundrechenarten sind Verfahren mit moderater Komplexität und moderaten Aufwand verfügbar
	++ unbeschränkter Wertebereich
	+- deutlich erhöhter übersichtlicher Wertebereich ~ 10000000000
	
	b) Stellenwertsystem (SWS) zur Basis b
		b "Basis", b $\epsilon  \mathbb{N} = {1}$   (d.h. b>1)
		Die Ziffermenge entählt b verschiedene Ziffern
		Die niderwertigste Ziffer hat den Ziffernwert "0"
		die höchstwertige "b-1"
	n-stellige Zahl = $\normalsize Z \tiny n-1 \normalsize ... Z \tiny0$  
	Wert($\normalsize Z \tiny n-1 \normalsize ... Z \tiny0$) = $\sum_{i=0}^{n-1} |Z\tiny i \normalsize = b^i$  
	(Damit wäre der einzige darstellbare Zahlenwert im SWS zur Basis = 1 die "0" => SWS zur Basis b=1 macht keinen Sinn!)
	SWS zur Basis b:
	+ übersichtlicher Wertebereich bis + b¹⁰
	(also exponentiell steigend!)

Hinweis: Bei größeren Basen wird die Übersichtlichkeit dann doch wieder eingeschrenkt da die vielen verschiedenen Ziffersymbole, welche benötigt und unterschieden werden können müssen

Gängige SWS:
b=10: Dezimalsystem von Menschen verwendeten SWS
b=2: Binärsysstem von Computer verwendetes SWS
$$ \begin{cases} b=16: Hexadezimalsystem  \\ b=8: Oktalsystem \end{cases} \Big\} \text{verwendet zur darstellung von Kompakteren Zahlen  von Computer Zahlen} $$
Umrechung zwischen verschiedenen Basen:
1. Umrechnung von b != 10 nach Basis 10:
		10111 $\tiny 2$ = 1 * 2⁰ + 1 * 2¹ + 1 * 2³ + 1 * 2⁴
			 = 1 * 1 + 1 * 2 + 1 * 4 + 0 * 8 + 1 * 16
			 = 23 $\tiny10$
		=> also über ddie Werte formel
			$\text{Wert}(Z\tiny n-1\normalsize,...Z\tiny 0 = \sum_{i=0}^{n+1} |Z \tiny i \normalsize | = b^i)$ 
2. Umrechung Basis 10 nach Basis b>0 
	- Umgekehrte Werteforme => klar!
	- Ganzzahldivision durch Zielbasis und Notation des restes
$$ \begin{align}
	23 : 2 = 11 \ R 1 = Z \tiny 0 \normalsize \\
   11 : 2 = 5\ R 1 = Z \tiny 1 \normalsize \\
   5 : 2 = 2\ R 1 = Z \tiny 2 \normalsize \\ 
   2 : 2 = 1\ R 0 = Z \tiny 3 \normalsize \\
   1 : 0 = 0\ R 1 = Z \tiny 4 \normalsize \\
   \end{align}
   $$
	23 = $10111 \tiny 2$ 

	Bsp: $$ \begin{align}
69 \tiny 10 \normalsize => b=3\\
	69 : 3 = 23 R \ 0 \\
	23 : 3 = 7 R \ 2 \\
	7 : 3 = 2 R \ 1 \\
	2 : 3 = 0 R \ 2 \\
	= 2120 \tiny 3 
\end{align}
	$$
	3. Umrechnung von Basis b != 10 nah Basis b != 10
		   in zwei Schritten von $b \tiny1$ nach $b\tiny z$ = 10
						   dann um $b\tiny z$ = 10 nach $b\tiny2$
			=> allgemeiner Weg
			- direkte Umrechnung möglich, falls $b\tiny1\normalsize ^n = b \tiny 2$ 
										bzw. $b\tiny 1 \normalsize = b ^ n$ 



| b=10 | b=16 | b=2  |
| ---- | ---- | ---- |
| 0    | 0    | 0000 |
| 1    | 1    | 0001 |
| 2    | 2    | 0010 |
| 3    | 3    | 0011 |
| 4    | 4    | 0100 |
| 5    | 5    | 0101 |
| 6    | 6    | 0110 |
| 7    | 7    | 0111 |
| 8    | 8    | 1000 |
| 9    | 9    | 1001 |
| 10   | A    | 1010 |
| 11   | B    | 1011 |
| 12   | C    | 1100 |
| 13   | D    | 1101 |
| 14   | E    | 1110 |
| 15   | F    | 1111 |

CAFE$\tiny16$ = 1100101011111110$\tiny2$ 
1A = 1 1010

Vorteil Oktalsystem
	Nur Übliche Ziffernsymbole
Vorteil Hexadezimalsystem
	ein Byte entspricht exact 2 HexaZiffern
	kompaktere Darstellung als beim Oktalsystem
Vorteil von beiden
	direktere Schnelle Umrechnung ins Binärsystem möglich

