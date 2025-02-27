
User Prompt:

Generiere mir einen Prompt um ein kanban board AUFGABE Kanban-Board mit: Drei Spalten: "ToDo", "In Progress", "Done" Drei Karten-Arten: "Bug" (rot), "User Story" (grün), "Task" (blau) Zwei Karten-Eigenschaften: Titel, Beschreibung, Arbeitspacketgröße in Stunden Erstellen und löschen von Karten Verschieben von Karten per Drag&Drop Responsive Layout/Design Füge eine Option für Light/Dark mode hinzu Drag&Drop highlighting Das erstellen der Karten soll nicht im ToDo feld sein sondern außerhalb der tabelle Kein Framework/Umwege Modernes Design Externe JS und CSS File Mobile Support

Ai Prompt: Vanilla Kanban Board mit Modernem Design Erstelle ein Kanban Board mit reinem HTML, CSS und JavaScript (ohne Frameworks) nach folgenden Vorgaben: Struktur: Board-Layout: Drei Spalten ("ToDo", "In Progress", "Done") als flex/grid-basierte Container. Responsive Design: Spalten stapeln sich vertikal auf Mobilgeräten (Media Queries). Karten: Typen: "Bug" (roter Header), "User Story" (grüner Header), "Task" (blauer Header). Eigenschaften: Titel, Beschreibung, Arbeitspaketgröße (Stunden). Jede Karte hat einen Löschen-Button (oben rechts). Interaktion: Drag & Drop: Karten zwischen Spalten verschieben (HTML5 Drag & Drop API). Visuelles Feedback beim Ziehen (Transparenz, Outline). Hover-Effekte für Drop-Zonen (z. B. Hintergrundaufhellung). Externes Formular: Formular oberhalb des Boards zum Erstellen von Karten (Eingabefelder + Typ-Auswahl). Submit-Button fügt Karte zur "ToDo"-Spalte hinzu. Design: Modernes UI: Weiche Schatten, abgerundete Ecken, konsistente Abstände. Light/Dark-Mode: Toggle-Button oben rechts. CSS-Variablen für Farben (z. B. --primary-bg, --card-bg). Mobile-First: Touch-freundliche Größen (min. 48x48px für Buttons). Technische Anforderungen: Externe Dateien: style.css, script.js. Keine Bibliotheken (jQuery, React etc.). Zustand speichern: Karten-Daten im localStorage persistieren. Code-Hinweise: CSS: Flexbox/Grid für Spalten, Media Queries für Mobile. JavaScript: Drag-Events: ondragstart, ondragover, ondrop. Dynamisches Generieren von Karten aus Array-Daten. Event-Listener für Löschen-Buttons und Theme-Toggle. **Erwartetes Ergebnis:** - Funktionsfähiges Board mit allen Features. - Sauberer, kommentierter Code. - Unterstützung für Desktop & Mobile.

Und "Fix drag&drop"



Drag&Drop Feedback 
Kein Framework
Responsive Design (Handy, Tablet, Laptop)
Dark Mode



![[Pasted image 20250227124921.png]]![[Pasted image 20250227124932.png]]![[Pasted image 20250227124941.png]]

