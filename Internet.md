% Internet

---
revealjs-url: ../../reveal.js
theme: white
width: \"95%\"
height: \"95%\"
header-includes:
    <style>
    .beispiel {
      border:3px;
      border-style:solid;
      border-color:black;
      width:fit-content;
      margin:auto;
    }
    .wichtig {
      border:3px;
      border-style:solid;
      border-color:red;
      width:fit-content;
      margin:auto;
    }
    </style>
...

### Wie wird eine Webseite für Internetnutzer erreichbar?
<ul>
<li class="fragment fade-in">Webseiten sind Nachrichten, die an den Browser gesendet und von ihm interpretiert werden</li>
<li class="fragment fade-in">Also allgemeiner: Wie werden Nachrichten übertragen?</li>
</ul>

### Sender-Empfänger-Modell
Ein <span class="fragment highlight-red">Sender</span> übersendet eine <span class="fragment highlight-red">Nachricht</span> über ein <span class="fragment highlight-red">Übertragungsmedium</span> an einen <span class="fragment highlight-red">Empfänger</span>.

### Nachrichten
<ul>
<li class="fragment fade-in">Nachrichten sind zu übermittelnde Zeichenketten, die zu Informationen interpretiert werden können.</li>
<li class="fragment fade-in"><a href="https://www.inf-schule.de/content/6_kommunikation/1_netze/1_kommunikationssysteme/1_transatlantikkabel/3_senderempfaenger/codierung.png">Zur Übertragung werden Nachrichten in physikalisch übertragbare Signale umgewandelt.</a></li>
</ul>

### Schichtenmodell
Beim Aufrufen einer Webseite gibt es viel zu beachten und zu verfolgen:  

<ul>
<li class="fragment fade-in">Computer herausfinden, der die Webseite anbietet</li>
<li class="fragment fade-in">Verbindung mit dem Computer aufbauen</li>
<li class="fragment fade-in">Anfragen an den Computer senden</li>
<li class="fragment fade-in">Anfragen in Signale codieren</li>
<li class="fragment fade-in">Signale über Kabel an den Computer schicken</li>
<li class="fragment fade-in">Sicherstellen, dass alles so ankommt, wie geplant</li>
<li class="fragment fade-in">Und das alles wieder zurück...</li>
</ul>

### Schichtenmodell
<ul>
<li class="fragment fade-in">Damit alles richtig abläuft, gibt es Protokolle, die den Ablauf regeln</li>
<li class="fragment fade-in">Der Übertragungsprozess ist in verschiedene Schichten aufgeteilt</li>
<li class="fragment fade-in">Für jede Schicht gibt es Protokolle, nach denen gearbeitet wird</li>
</ul>

### Schichtenmodell
<a href="https://www.inf-schule.de/content/6_kommunikation/1_netze/2_schichtenmodelle/2_schichtenmodell_internet/nachrichtenuebertragung.png">Ein Schichtenmodell</a>

<a href="https://www.inf-schule.de/content/6_kommunikation/1_netze/2_schichtenmodelle/2_schichtenmodell_internet/protokollstapel.png">Protokolle eines Schichtenmodells</a>

### Vereinfachtes Beispiel des HTTP
<ul>
<li class="fragment fade-in">baslers.github.io/informatik-wp10/Internet.html soll aufgerufen werden</li>
<li class="fragment fade-in">Die Adresse des Servercomputers, der baslers.github.io anbietet, wird über das DNS-Protokoll ausfindig gemacht</li>
<li class="fragment fade-in">Der Servercomputer, der baslers.github.io anbietet, wird aufgefordert die Datei /informatik-wp10/Internet.html zurückzusenden</li>
<li class="fragment fade-in">Der Servercomputer sendet die angeforderte Datei zurück</li>
</ul>

<span class="fragment fade-in"><a href="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f9/HTTP-Anfrage.svg/1920px-HTTP-Anfrage.svg.png">Abbildung einer Beispielverbindung</a></span>

### DNS-Protokoll
<ul>
<li class="fragment fade-in">Wird eine Internetadresse aufgerufen, wird die IP-Adresse des anbietenden Computers aufgerufen</li>
<li class="fragment fade-in">Beispiel: 211.123.12.1/index.html</li>
<li class="fragment fade-in">Damit Menschen sich die Adressen merken können, werden sie in Domain-Namen mit dem DNS-Protokoll umgewandelt</li>
</ul>

<span class="fragment fade-in"><a href="https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/Dns-raum.svg/1920px-Dns-raum.svg.png">Beispiel einer DNS-Hierarchie</a></span>
