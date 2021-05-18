## Arrays (Listen) am Beispiel "Suchen und Ordnen"

Hier lernen Sie, Daten strukturiert in Arrays (in Python: Listen) zu speichern und üben den Umgang damit am Beispiel von Such- und Sortieralgorithmen.

### Inhalt

Nach einer Einführung in Arrays (Listen), werden verschiedene Such- und Sortieralgorithmen besprochen gefolgt von den Teilen Suchen und Ordnen (Sortieren). Jeder Algorithmus erlaubt es Ihnen, sich konkret mit Listenoperationen zu befassen.

* Arrays (in Python: Listen) als Sammelgefäss von Daten
    * Erstellen von Listen
    * Iteration über Listen
    * Zugriff auf Listenbereiche
    * Material:  
      Jupyter Notebook: Arrays.ipynb  
      * Zur lokalen Bearbeitung: Download [Notebook](assets/notebooks/solutions/Arrays.ipynb)
      * Zur Bearbeitung auf [Google Colaboration](https://colab.research.google.com/github/donze-informatikunterricht/suchen-und-ordnen/blob/gh-pages/assets/notebooks/solutions/Arrays.ipynb)
    * Zusatzmaterial zu Zufallszahlen:  
      Jupyter Notebook: Zufallszahlen.ipynb  
      * Zur lokalen Bearbeitung: Download [Notebook](assets/notebooks/solutions/Zufallszahlen.ipynb)
      * Zur Bearbeitung auf [Google Colaboration](https://colab.research.google.com/github/donze-informatikunterricht/suchen-und-ordnen/blob/gh-pages/assets/notebooks/solutions/Zufallszahlen.ipynb)
* Algorithmen zum Suchen und Ordnen
   * Suche nach einem Element in einer
      * ungeordneten Liste
      * geordneten Liste
      * Material:  
      Jupyter Notebook: Suchen.ipynb  
      * Zur lokalen Bearbeitung: Download [Notebook](assets/notebooks/solutions/Suchen.ipynb)
      * Zur Bearbeitung auf [Google Colaboration](https://colab.research.google.com/github/donze-informatikunterricht/suchen-und-ordnen/blob/gh-pages/assets/notebooks/solutions/Suchen.ipynb)
   * Sortieren von Listen nach verschiedenen Algorithmen
      * Insertion Sort
         * Einfügen eines Elements in eine Liste
      * Selection Sort
         * Suche nach dem kleinsten bzw. grössten Element einer Liste
      * Bubble Sort
         * Vertausch zweier Listenelemente
         * Sinn der Optimierung von Algorithmen
         * Material:  
         Jupyter Notebook: Bubblesort.ipynb  
         * Zur lokalen Bearbeitung: Download [Notebook](assets/notebooks/solutions/Bubblesort.ipynb)
         * Zur Bearbeitung auf [Google Colaboration](https://colab.research.google.com/github/donze-informatikunterricht/suchen-und-ordnen/blob/gh-pages/assets/notebooks/solutions/Bubblesort.ipynb)
      * Merge Sort
         * Zusammenfügen (Merge) zweier sortierter Listen 

### Voraussetzungen

#### Programmierkenntnisse
Dieser Kurs nutzt die Programmiersprache Python. Folgende Kenntnisse werden vorausgesetzt:
* Arithmetische Operatoren (`+`, `-`, `*`, `/`, `//`, `%`, `**`)
* Variablen
  *  Ein- und Ausgabe mit den Funktionen `input()` und `print()`
  *  Verändern von Variablen (`=`, `+=`, `-=`, `*=`, `/=`)
* Datentypen
  *  Strings (Zeichenketten)
  *  Integer (Ganzzahlen)
  *  Float (Fliesskommazahlen)
  *  Booleans (Wahrheitswerte)
* Kontrollstrukturen
  * Verzweigungen 
    * einseitig (`if`)
    * zweiseitig (`if` - `else`)
    * mehrstufig (`if` - `elif` - `else`)
    * Logische Ausdrücke mittels relationaler (`>`, `<`, `==`, `!=`, `>=`, `<=`) und logischer (`and`, `or`, `not`) Operatoren
  * for-Schleifen
* Funktionen

#### Tools

Dieser Kurs verwendet Jupyter Notebooks. Sie können sich diese als interaktive Notizbücher vorstellen, die im Web Browser laufen. Sie machen es möglich, Dokumentation und ausführbaren Code zu verbinden. Falls Sie mehr dazu wissen möchten, ist der Wikipedia-Artikel eine empfehlenswerte Quelle.


Sie können diese lokal auf Ihrem Gerät oder online auf Google Colaboration (dafür ist ein Google-Account nötig) nutzen. Die Jupyter Notebooks werden im Web Browser dargestellt. Sie benötigen also auch einen Web Browser wie Chrome, Safari, Firefox, etc.

Falls Sie auf Ihrem eigenen Gerät arbeiten möchten und Jupyter Notebooks noch nicht installiert haben, geht dies am einfachsten über Anaconda.

##### Installation von Anaconda

<details>
<summary>1. Anaconda herunterladen</summary>
   Sie können Anaconda <a href="https://www.anaconda.com/products/individual" target="_blank">hier herunterladen</a>.  
   <ul>
      <li>Die Individual-Lizenz ist für den Privat- und Ausbildungsbereich kostenlos.</li>
      <li>Ein Klick auf den Button "Download" unter dem obersten Abschnitt scrollt die Seite an den richtigen Ort.</li>
      <li>Wählen Sie das Download-File, das zu Ihrer Umgebung passt.
         <ul>
            <li>Für den <strong>Mac</strong> empfiehlt sich der graphische Installer.</li>
            <li><strong>Windows</strong>: Wenn Sie nicht sicher sind, ob Sie einen 32-bit- oder 64-bit-Prozessor haben:<br/>
                öffnen Sie ein Explorerfenster, Recktsklich auf "Die §ser PC" > Eigenschaften > Systemtyp.
               <img src="assets/images/contextmenue.png" alt="pfad" width="20%"/>
            <img src="assets/images/systeminfo.png" alt="pfad" width="60%"/>
            </li>
         </ul>
      </li>
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
   <ul>
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
      </li>
      <li>Im <strong>Anaconda Navigator</strong> finden Sie Jupyter und andere Tools.<br/>
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
   Sie haben die Möglichkeit, Ihr Jupyter Notebook direkt im Verzeichnis Ihrer Wahl zu öffnen.
   <ul>
      <li><strong>Mac</strong>:<br/>
         <ul>
            <li>Öffnen Sie das Terminal und gehen Sie direkt ins Verzeichnis Ihrer Wahl<br/>
               `cd ~/schule/informatik/jupyter`</li>
            <li>Starten Sie das Jupyter Notebook mit dem Befehl<br/>
               `jupyter notebook`</li>
         </ul>
      </li>
      <li><strong>Windows</strong>:
         <ul>
            <li>In diesem Beispiel ist das Verzeichnis: `C:\Users\User\Jupyter`<br/>
               (Benutzername: "User")</li>
            <li>Machen Sie einen Shortcut des Jupyter Launchers auf den auf dem Desktop.
               <ul>
                  <li>Rechtsklick darauf -> Properties</li>
                  <li>Nun können Sie in den Feldern Target bzw. Start in `%USERPROFILE%` bzw. `%HOMEPATH%` durch Ihren Pfad ersetzen:<br/>
                     <img src="assets/images/installation-path.png" alt="pfad" width="80%"/>
                  </li>
               </ul>
            </li>
         </ul>
      </li>
   </ul>

</details>  

### Lizenz
<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://donze-informatikunterricht.github.io/suchen-und-ordnen/">Suchen und Ordnen</a> by <span property="cc:attributionName">Alessandra Donzé</span> is licensed under <a href="http://creativecommons.org/licenses/by-nc/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"></a></p>