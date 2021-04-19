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
<summary>Installationsanleitung</summary>
    
1. Anaconda herunterladen  
  Sie können Anaconda [hier herunterladen](https://www.anaconda.com/products/individual)  
  * Die Individual-Lizenz ist für den Privat- und Ausbildungsbereich kostenlos. 
  * Der Link "Download" scrollt die Seite nach unten.
  * Wählen Sie das Download-File, das zu Ihrer Umgebung passt.  
    Für den **Mac** empfiehlt sich der graphische Installer.

2. Anaconda installieren  
  Folgen Sie den Instruktionen des Installers.  
  * Die entsprechenden Konfigurationen sollten bereits vorangewählt sein:
    * Install for: `Just me / Nur für mich installieren`
    * Destination Folder (Pfad):  
      **Windows**: `C:\users\IhrBenutzername\anaconda3`
  * Add Anaconda3 to my PATH environment variable
  * Register Anaconda3 as my default Python 3.8: *Kein Haken* ist sicherer, falls Sie noch andere Pythonprojekte mit anderen Tools verwenden.

<details>
<summary>Windows</summary>

<p>...</p>
</details>  

<details>
<summary>Mac</summary>

<p>...</p>
</details>  


3. Jupyter Notebook öffnen  
   Es gibt verschiedene Möglichkeiten, wie Sie Jupyter Notebook starten können:
   1. Jupyter über das Programm *Anaconda Navigator* öffnen
      Sie finden es am einfachsten so:
      * **Mac**: Öffnen Sie *Anaconda Navogator*  
        (Sie finden es am einfachsten über die Spotlight-Suche mit \[ ⌘ + Leertaste \] )  
        **Windows**: Öffnen Sie das Programm Anaconda Navigator  
        (über den Startknopf, unter A: Anaconda)
        <img src="assets/images/launch-navigator.png" alt="launch-navigator" width="30%"/>
                
      * Im Anaconda Navigator finden Sie Jupyter und andere Tools.
      
        <img src="assets/images/anaconda-navigator.png" alt="anaconda-navigator"/>
      
        * Starten Sie Jupyter über den Button "Launch".  
        * In Ihrem Standard-Web-Browser sollte sich nun Jupyter öffnen.
    2. **Windows**: Jupyter Notebook direkt aus dem Start-Menü starten  
      * Unter Windows können Sie alternativ dazu ein Jupyter Notebook direkt aus dem Startmenü heraus starten, woraufhin sich der Webbrowser selbst öffnen wird.  
      <img src="assets/images/launch-jupyter.png" alt="launch-jupyter" width="30%"/>

4. Möglichkeiten, das Jupyter Notebook im gewünschten Verzeichnis öffnen
   Sie haben die Möglichkeit, Ihr Jupyter Notebook zu öffnen.
   * **Mac**:  
     * Öffnen Sie das Terminal und gehen Sie direkt ins Verzeichnis Ihrer Wahl
       `cd ~/schule/informatik/jupyter`
     * Starten Sie das Jupyter Notebook mit dem Befehl
       `jupyter notebook`
   * **Windows**:  
     * Mein Verzeichnis ist: `C:\Users\User\Jupyter`
     * Machen Sie einen Shortcut des Jupiter Launchers auf den auf dem Desktop.  
        * Rechtsklick darauf -> Properties  
        * Nun können Sie in den Feldern Target bzw. Start in `%USERPROFILE%` bzw. `%HOMEPATH%` durch Ihren Pfad ersetzen:
        <img src="assets/images/installation-path.png" alt="pfad" width="80%"/>
 

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

