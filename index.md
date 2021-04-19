## Arrays (Listen) am Beispiel "Suchen und Ordnen"

Hier üben Sie den Umgang mit Arrays (Listen in Python) am Beispiel von Such- und Sortieralgorithmen.

### Hier werden Sie folgendes lernen

* Arrays (Python: Listen) als Sammlung von Elementen
    * Erstellen von Listen
    * Iteration über Listen
    * Zugriff auf Teilbereiche von Listen
* Suche nach einem Element in einer 
    * ungeordneten Liste
    * geordneten Liste
* Sortieren von Listen nach verschiedenen Algorithmen
    * Insertion Sort
        * Einfügen eines Elements in eine Liste
    * Selection Sort
        * Suche nach dem kleinsten bzw. grössten Element einer Liste
    * Bubble Sort
        * Vertausch zweier Listenelemente
        * Sinn der Optimierung von Algorithmen
    * Merge Sort
        * Zusammenfügen (Merge) zweier sortierter Listen
        
        
### Voraussetzungen

#### Programmierkenntnisse
Dieser Kurs nutzt die Programmiersprache Python. Folgende Kenntnisse werden vorausgesetzt:

* Variablen
  *  Ein- und Ausgabe mit den Funktionen `input()` und `print()`
  *  Verändern von Variablen (`+=`, `-=`, `*=`, `/=`)
* Datentypen
  *  Strings (Zeichenketten)
  *  Integer (Ganzzahlen)
  *  Float (Fliesskommazahlen)
  *  Booleans (Wahr/Falsch)
* Kontrollstrukturen
  * Verzweigungen und logische Ausdrücke
  * for-Schleifen

#### Tools

Dieser Kurs verwendet Jupyter Notebooks. Sie können sich diese als interaktive Notizbücher vorstellen, die im Web Browser laufen. Sie machen es möglich, Dokumentation und ausführbaren Code zu verbinden. Falls Sie mehr dazu wissen möchten, ist der Wikipedia-Artikel eine empfehlenswerte Quelle.


Sie können diese lokal auf Ihrem Gerät oder online auf Google Colaboration (dafür ist ein Google-Account nötig) nutzen. Die Jupyter Notebooks werden im Web Browser dargestellt. Sie benötigen also auch einen Web Browser wie Chrome, Safari, Firefox, etc.

Falls Sie auf Ihrem eigenen Gerät arbeiten möchten und Jupyter Notebooks noch nicht installiert haben, geht dies am einfachsten über Anaconda.

##### Installation von Anaconda

<details>
<summary>1. Anaconda herunterladen</summary>
   Sie können Anaconda <href="https://www.anaconda.com/products/individual" target="_blank">hier herunterladen</href>.  
   <ul>
      <li>Die Individual-Lizenz ist für den Privat- und Ausbildungsbereich kostenlos.</li>
      <li>Der Link "Download" scrollt die Seite nach unten.</li>
      <li>Wählen Sie das Download-File, das zu Ihrer Umgebung passt.<br/>
         Für den <strong>Mac</strong> empfiehlt sich der graphische Installer.</li>
   </ul>
</details>


<details>
   <summary>2. Anaconda installieren</summary>
   Folgen Sie den Instruktionen des Installers.  
   <ul>
      <li>Die entsprechenden Konfigurationen sollten bereits vorangewählt sein:
         <ul>
            <li>Install for: `Just me / Nur für mich installieren`</li>
            <li>Destination Folder (Pfad):<br/>
               <strong>Windows</strong>: `C:\users\IhrBenutzername\anaconda3`</li>
         </ul>
      </li>
      <li>Add Anaconda3 to my PATH environment variable</li>
      <li>Register Anaconda3 as my default Python 3.8: <it>Kein Haken</it> ist empfehlenswert, falls Sie noch andere Pythonprojekte mit anderen Tools verwenden.</li>
   </ul>
</details>


<details>
   <summary>3. Jupyter Notebook öffnen</summary>
   Es gibt verschiedene Möglichkeiten, wie Sie Jupyter Notebook starten können.
   <ol>
      <li>Am einfachsten starten Sie Jupyter über das Programm <it>Anaconda Navigator</it>.<br/>
         Öffnen Sie das Programm <it>Anaconda Navigator</it>.
         <ul>
            <li><strong>Mac</strong>:<br/>
               Sie finden es am einfachsten über die Spotlight-Suche mit [⌘ + Leertaste].</li>
            <li><strong>Windows</strong>:<br/>
               Sie finden es über den Startknopf bei den Programmen unter A: Anaconda.<br/>
               <img src="assets/images/launch-navigator.png" alt="launch-navigator" width="30%"/>
            </li>
         </ul>
         Im <strong>Anaconda Navigator</strong> finden Sie Jupyter und andere Tools.<br/>
         <img src="assets/images/anaconda-navigator.png" alt="anaconda-navigator"/>
         <ul>   
            <li>Starten Sie Jupyter über den Button "Launch".</li>
            <li>In Ihrem Standard-Web-Browser sollte sich nun Jupyter öffnen.</li>
         </ul>
      </li>
      <li><strong>Windows</strong>: Jupyter Notebook direkt aus dem Start-Menü starten<br/>
         Der Webbrowser wird sich selbst öffnen.<br/>
      <img src="assets/images/launch-jupyter.png" alt="launch-jupyter" width="30%"/></li>
         </ul>
</details>


<details>
   <summary>4. Möglichkeiten, das Jupyter Notebook im gewünschten Verzeichnis öffnen</summary>
   Sie haben die Möglichkeit, Ihr Jupyter Notebook zu öffnen.
   <ul>
      <li><strong>Mac</strong>:<br/>
         <ul>
           <li>Öffnen Sie das Terminal und gehen Sie direkt ins Verzeichnis Ihrer Wahl
       `cd ~/schule/informatik/jupyter`</li>
           <li>Starten Sie das Jupyter Notebook mit dem Befehl
       `jupyter notebook`</li>
         </ul>
      </li>
      <li><strong>Windows</strong>:
         <ul>
            <li>In diesem Beispiel ist das Verzeichnis: `C:\Users\User\Jupyter` <br/>
        (Benutzername: "User")</li>
           <li>Machen Sie einen Shortcut des Jupiter Launchers auf den auf dem Desktop.
               <ul>
                  <li>Rechtsklick darauf -> Properties</li>
                  <li>Nun können Sie in den Feldern Target bzw. Start in `%USERPROFILE%` bzw. `%HOMEPATH%` durch Ihren Pfad ersetzen:<br/>
                     <img src="assets/images/installation-path.png" alt="pfad" width="80%"/>
                  </li>
               </ul>
            </li>
        </li>
 

</details>  


------

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/donze-informatik/suchen-und-ordnen/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

