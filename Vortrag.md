<!--
version:  0.1.1
language: de

narrator: Deutsch Female

tags: Präsentation, Fortbildung, LiaScript, OER

comment:  Fortbildung 2026 — LiaScript und seine Integration in OPAL.
          Martin Lommatzsch (Geschwister-Scholl-Gymnasium Freiberg).

author:   Sebastian Zug, Martin Lommatzsch



import: https://raw.githubusercontent.com/MINT-the-GAP/lia-DynFlex/refs/heads/main/README.md
import: https://raw.githubusercontent.com/MINT-the-GAP/lia-timer/refs/heads/main/README.md
import: https://raw.githubusercontent.com/MINT-the-GAP/lia-board-mode/refs/heads/main/README.md
import: https://raw.githubusercontent.com/MINT-the-GAP/lia-marker/refs/heads/main/README.md
import: https://raw.githubusercontent.com/MINT-the-GAP/lia-annotation/refs/heads/main/README.md
import: https://raw.githubusercontent.com/MINT-the-GAP/lia-canvas-ocr/refs/heads/main/README.md
import: https://raw.githubusercontent.com/MINT-the-GAP/lia-orthography/refs/heads/main/README.md
import: https://raw.githubusercontent.com/MINT-the-GAP/lia-Mathe/refs/heads/main/README.md
import: https://raw.githubusercontent.com/MINT-the-GAP/lia-kachel/refs/heads/main/README.md
import: https://raw.githubusercontent.com/MINT-the-GAP/lia-navigation/refs/heads/main/README.md
import: https://raw.githubusercontent.com/MINT-the-GAP/lia-mathpath/refs/heads/master/README.md

import: https://raw.githubusercontent.com/MINT-the-GAP/lia-llm/refs/heads/main/README.md

import: https://raw.githubusercontent.com/liaTemplates/algebrite/master/README.md
import: https://raw.githubusercontent.com/liaTemplates/JSXGraph/main/README.md

import: https://raw.githubusercontent.com/MINT-the-GAP/lia-resetter/main/README.md

import: https://raw.githubusercontent.com/MINT-the-GAP/lia-coordinate/refs/heads/main/README.md
import: https://raw.githubusercontent.com/MINT-the-GAP/lia-freeze-v2/main/README.md
import: https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/main/imports/RedirecterREADME.md

import: https://raw.githubusercontent.com/MINT-the-GAP/lia-loot/main/README.md

import: https://raw.githubusercontent.com/MINT-the-GAP/lia-pentominos/main/README.md



persistent: true

edit: true


-->

# SchulLia - LiaScript in der Schule 

@autoscrolling(off)

<h2> R08025: Digitale Unterrichtsmaterialien mit Rückmeldung für Lernende </h2>
<h2> LiaScript - Digitale OER Arbeitsblätter nutzen und gestalten </h2>
<h2> Schwerpunkt Mathematik </h2>


> Fortbildung, November 2026, Freiberg


---

---


<section class="dynFlex" data-basis="32.5">

<div class="flex-child">

![logo](https://raw.githubusercontent.com/MINT-the-GAP/Wochenaufgabe/refs/heads/main/Zeug/Logo.png)

</div>
<div class="flex-child">

<center>

<!-- style="max-width:250px" -->
![logo](lrLia.png)


<big><h3> Martin Lommatzsch</h3></big>
<small><small> Geschwister-Scholl-Gymnasium Freiberg </small></small>





</center>

</div>
<div class="flex-child">


![partner_map](https://github.com/LiaPlayground/Saechsischer_Schulinformatik_Tag_2026/blob/main/pic/LiaScript_Meets_OER.png?raw=true "OER-Logo - Quelle: Jonathasmello - Eigenes Werk, CC BY 3.0, [https://commons.wikimedia.org/w/index.php?curid=18460156](https://commons.wikimedia.org/w/index.php?curid=18460156) erweitert um LiaScript Logo")
</div>

</section>

<center>

---

---

<img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/0.png" width="80" height="80">  $\;\qquad\;$
<img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/1.png" width="80" height="80">  $\;\qquad\;$
<img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/2.png" width="80" height="80">  $\;\qquad\;$
<img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/3.png" width="80" height="80">  $\;\qquad\;$
<img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/4.png" width="80" height="80">  $\;\qquad\;$
<img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/5.png" width="80" height="80"> 

</center>



---

---


# Agenda



<img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/1.png" width="40" height="40">  <big><big><b>Motivation und Einführung - ca. 30 Minuten</b></big></big>

---

<img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/1.png" width="40" height="40">  <big><big><b>Erkundung der Möglichkeiten - ca. 45 Minuten</b></big></big>

---

<img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/2.png" width="40" height="40">  <big><big><b>Hospitation - ca. 45 Minuten</b></big></big>

---

<img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/2.png" width="40" height="40">  <big><big><b>Zwischenstandsbesprechung - ca. 20 Minuten</b></big></big>

---

> Kurze Pause

---


<img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/3.png" width="40" height="40">  <big><big><b>Erstellen und Bereitstellen von Kursen - ca. 20 Minuten </b></big></big>

---

<img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/3.png" width="40" height="40">  <big><big><b>Erste gemeinsame Schritte - Hallo Welt! - ca. 45 Minuten</b></big></big>

---

<img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/4.png" width="40" height="40">  <big><big><b>Anpassen von Kursen - ca. 15 Minuten </b></big></big>

---



<img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/4.png" width="40" height="40">  <big><big><b>Eigene komplexere Kurse erstellen - ca. 20 Minuten </b></big></big>

---

<img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/5.png" width="40" height="40">  <big><big><b>Reflexion - ca. 10 Minuten </b></big></big>
















# <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/1.png" width="40" height="40"> Einleitung und Motivation


<h2> Beobachtungen als Lehrkraft </h2> 


<section class="dynFlex" data-basis="49">


<div class="flex-child">



{{1}}
- <h3> Schülerinnen und Schülern fällt es mit zunehmenden Alter oftmals kontinuierlich schwerer neue Inhalte zu bearbeiten. </h3>
- <h3> Schülerinnen und Schüler verlieren das fachliche Selbstvertrauen und das explizit in MINT-Fächern. </h3>



{{2}}
> <h3>Wie kann man das begründen?</h3> 

{{2}}
<h3>Neben vielen allgemeineren Aspekten dieses multifaktoriellen Problems wie _erhöhtes Ablenkungspotential_, _Frage der Sinnhaftigkeit des Gelernten_, _stark angestiegender Vergleichsdruck_, _Zukunftsängste_, und vielen weiteren Gründen, gibt es auch klar fachliche Beobachtungen: </h3> 


{{3}}
*********************
---

---

<h3> <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/0.png" width="40" height="40"> Fachvokabeln sind nicht verinnerlicht und werden vergessen. </h3>
*********************


{{4}}
<h3> <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/0.png" width="40" height="40"> Lösungsansätze und -strategien sind nicht verinnerlicht und werden vergessen. </h3> 


{{5}}
<h3> <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/0.png" width="40" height="40"> Eigentlich bekannte Algorithmen sind so eingerostet, dass sie unbekannt wirken. </h3> 


{{6}}
*********************
---

---


<h2> Lösungsansatz </h2> 

<h3> <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/1.png" width="40" height="40">  Bereitstellung von Wiederholungsoptionen $\;\Rightarrow\;$ Idee der Wochenaufgaben </h3> 

*********************

</div>




</section>













### <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/2.png" width="40" height="40"> Wochenaufgaben










<section class="dynFlex" data-basis="49">


<div class="flex-child">



<h3> <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/2.png" width="40" height="40">  wochenaufgaben.gsg-freiberg.de </h3> 



<h3> <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/2.png" width="40" height="40">  Über 6800 Seiten an Aufgaben mit Musterlösungen für Mathematik </h3> 



<h3> <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/2.png" width="40" height="40">  Repetitorium mit mehr als 1500 Seiten Erklärungen, Aufgaben und Lösungen </h3> 


{{1}}
***********************
---

---


<h3> <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/4.png" width="40" height="40"> Sie können alle Materialien nutzen und verändern, wie es Ihnen beliegt. Sollten Ihnen Fehler auffallen, würde ich mich über eine Kontaktaufnahme freuen, sodass die Fehler behoben werden können. </h3> 

***********************



</div>

<div class="flex-child">



??[Wochenaufgaben](https://wochenaufgaben.gsg-freiberg.de)


</div>


</section>




















### <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/5.png" width="40" height="40"> Analyse der Wochenaufgaben




<section class="dynFlex" data-basis="49">


<div class="flex-child">



{{1}}
<h3> <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/0.png" width="40" height="40"> PDFs bieten keine Interaktionsmöglichkeit und sind nur die Digitalisierung einer Kopiervorlage.</h3> 


{{2}}
<h3> <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/0.png" width="40" height="40"> Die Lernenden erhalten keine Rückmeldung zu ihren Problemen, selbst wenn man die Musterlösung später bereitstellt.</h3> 

{{3}}
<h3> <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/0.png" width="40" height="40"> Lehrkräfte erhalten auch keine Rückmeldung und können den Unterricht nicht auf die Lerngruppe zielgerichteter anpassen. </h3> 


{{4}}
<h3> <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/0.png" width="40" height="40"> Entlastet im Unterricht nicht, da "Ist das richtig?"-Meldungen bleiben </h3> 


{{5}}
***************
---

---

<h3> <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/5.png" width="40" height="40"> Schülerinnen und Schüler, die die Übung dringend bräuchten, machen die Aufgaben nicht, während die anderen die Aufgaben bearbeiten. Somit nimmt die fachliche Heterogenität der Lerngruppe zu.</h3> 

***************


{{6}}
***************
---

---



<h3> $\Longrightarrow\;\;$ <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/1.png" width="40" height="40"> Es braucht interaktive digitale Aufgaben, die direkte Rückmeldungen für Lernende und Lehrende geben können. </h3> 

***************

</div>

</section>





























### <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/1.png" width="40" height="40"> Angebotsanalyse - bekannte Anbieterprobleme




<section class="dynFlex" data-basis="49">

<div class="flex-child">

{{1}}
<h3> <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/5.png" width="40" height="40"> Nahezu alle Anbieter sind proprietär </h3> 


</div>
<div class="flex-child">

{{2}}
<h3> $\Rightarrow\;$ <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/0.png" width="40" height="40"> Bildung sollte kostenlos und frei zugänglich sein </h3> 

</div>

</section>




---




<section class="dynFlex" data-basis="49">

<div class="flex-child">

{{3}}
<h3> <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/5.png" width="40" height="40">  Es wird fast nur Anforderungsbereich 1 angeboten ("Gib an"/"Nenne") </h3> 


</div>
<div class="flex-child">


{{4}}
<h3> $\Rightarrow\;$ <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/0.png" width="40" height="40"> Rechenwege, Erklärungen, Zeichnungen, Vernetzungen, und vieles mehr offenbaren erst das Verständnis - Es bedarf mehr als die reine eineindeutige Lösungseingabe einer Übung </h3> 

</div>

</section>






---






<section class="dynFlex" data-basis="49">

<div class="flex-child">


{{5}}
<h3> <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/5.png" width="40" height="40"> Oftmals gibt es eine Beschränkung auf das Angebot durch Vorgaben des Unternehmens </h3> 


</div>
<div class="flex-child">


{{6}}
<h3> $\Rightarrow\;$ <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/0.png" width="40" height="40"> Unterricht muss auf Lerngruppen abgestimmt werden können. Es müssen beliebig viele neue Angebote erstellbar und kombinierbar sein </h3> 


</div>

</section>



---




<section class="dynFlex" data-basis="49">

<div class="flex-child">


{{7}}
<h3> <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/5.png" width="40" height="40"> Angebotene Inhalte sind oftmals stark repetitiv </h3> 


</div>
<div class="flex-child">


{{8}}
<h3> $\Rightarrow\;$ <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/0.png" width="40" height="40"> Schülerinnen und Schüler lernen die Lösungseingaben auswendig anstatt kognitiv aktiviert zu werden </h3> 


</div>

</section>




---



<section class="dynFlex" data-basis="49">

<div class="flex-child">


{{9}}
<h3> <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/5.png" width="40" height="40">  Antworten müssen teilweise in einer speziellen Syntax eingegeben werden </h3> 


</div>
<div class="flex-child">


{{10}}
<h3> $\Rightarrow\;$ <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/0.png" width="40" height="40"> Es sollte eigentlich das Fach und nicht das Programm unterrichtet werden </h3> 



</div>

</section>


---



<section class="dynFlex" data-basis="49">

<div class="flex-child">


{{11}}
<h3> <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/5.png" width="40" height="40">  Oftmals ist setzt das Angebot auf das Flipped-Classroom-Prinzip </h3> 




</div>
<div class="flex-child">





{{12}}
<h3> $\Rightarrow\;$ <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/0.png" width="40" height="40"> Bringt keine Entlastung im Unterricht und verstärkt die Herkunftsungleichheit zusätzlich </h3> 



</div>

</section>


{{13}}
<h3> $\Rightarrow\;$ <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/0.png" width="40" height="40"> Und die fachliche Eignung wurde noch nicht mal thematisiert. </h3> 







































































### <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/1.png" width="40" height="40"> Bedarfe in der Schule

<h3>Ein Angebot muss... </h3> 

{{1}}
**************

<section class="dynFlex" data-basis="49">

<div class="flex-child">

<h4> ... kostenlos und freizugänglich sein. </h4> 

</div>

<div class="flex-child">

<h4> ... sollte nicht proprietär sein. </h4> 

</div>

<div class="flex-child">


<h4> ... sollte DSGVO-konform sein. </h4> 


</div>

</section>




---

**************



{{2}}
**************

<section class="dynFlex" data-basis="49">

<div class="flex-child">

<h4> ... sollte ohne jegliche Vorabinstallation auskommen. </h4> 

</div>

<div class="flex-child">

<h4> ... sollte keine zusätzliche Infrastruktur benötigen. </h4> 

</div>

<div class="flex-child">


<h4> ... sollte Bring-Your-Own-Device tauglich sein. </h4> 


</div>

</section>






---

**************





{{3}}
**************

<section class="dynFlex" data-basis="49">

<div class="flex-child">

<h4> ... sollte dezentral organisiert sein. </h4> 

</div>

<div class="flex-child">

<h4> ... sollte auch offline weiter bearbeitbar sein. </h4> 

</div>

<div class="flex-child">


<h4> ... sollte ohne Syntaxschulung benutzbar sein. </h4> 


</div>

</section>




---

**************


{{4}}
**************

<section class="dynFlex" data-basis="49">

<div class="flex-child">

<h4> ... sollte eine mathematische Schrifterkennung beinhalten.  </h4> 

</div>

<div class="flex-child">

<h4> ... sollte ein Computer-Algebra-System beinhalten. </h4> 

</div>

<div class="flex-child">


<h4> ... sollte ein Dynamisches-Geometrie-System beinhalten.  </h4> 


</div>

</section>



---

**************



{{5}}
**************


<section class="dynFlex" data-basis="49">

<div class="flex-child">

<h4> ... sollte direkte Rückmeldungen für die Lernenden geben können.  </h4> 

</div>

<div class="flex-child">

<h4> ... sollte automatisierte Korrekturen mit händischer Nachkontrolle ermöglchen. </h4> 

</div>

<div class="flex-child">


<h4> ... sollte individuelle Lernpfade ermöglichen.  </h4> 


</div>

</section>


---

**************


{{6}}
**************

<section class="dynFlex" data-basis="49">

<div class="flex-child">

<h4> ... sollte statistische Auswertungen und Analysen zur Lerngruppe der Lehrkraft bereitstellen können.  </h4> 

</div>

<div class="flex-child">

<h4> ... sollte hochwertige und individualisierbare Aufgaben bereitstellen können. </h4> 

</div>

<div class="flex-child">


<h4> ... sollte auch für die Lehrkraft ohne Syntaxschulung auskommen.  </h4> 


</div>

</section>



---


**************

{{7}}
<h4> <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/1.png" width="40" height="40"> LiaScript bietet die Basis für genau alle diese Bedarfe, jedoch ist das Potential von LiaScript nocht nicht vollständig erschlossen.  </h4> 

{{8}}
<h3> <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/2.png" width="40" height="40"> Ziel: Der Bildschirm muss wie ein Blattpapier beschreibbar sein, daraus müssen Aufgaben hochwertig generiert und diese an die Schülerinnen und Schüler übermittelt werden können.  </h3> 


{{9}}
<h3> <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/3.png" width="40" height="40"> Aufgabensammlung ist in der Entstehung: <a href="https://mint-the-gap.github.io/Aufgabensammlung/"> mint-the-gap.github.io/Aufgabensammlung/ </a> </h3> 















































# <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/1.png" width="40" height="40"> Erkundung des Potentials von LiaScript


<h3> Um das Potential von LiaScript zu erkunden, wird es für Sie in den nächsten 90 Minuten möglich sein, dass Sie in einer Teilgruppe eine Übungsstunde mit LiaScript hospitieren oder die Möglichkeiten von LiaScript anhand von Beispielen erkunden. </h3> 

---

<h3>Beobachtungsaufträge </h3> 

<section class="dynFlex" data-basis="49">



<div class="flex-child">


<h3> Hospitation </h3> 

- <h4> Wa </h4> 

</div>

<div class="flex-child">


<h3> Erkundung </h3> 

- <h4> Welche </h4> 

</div>

</section>



Kurs bereitstellen


??[Erkundungskurs](https://liascript.github.io/course/?Erkunden.md)





# <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/4.png" width="40" height="40"> Erstellung und Bereitstellen von Kursen 

uns teilen und diskutieren





# <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/4.png" width="40" height="40"> Erste gemeinsame eigene Schritte

Cheatsheets und rumprobieren




# <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/4.png" width="40" height="40"> Anpassen von Kursen

LiveEditor - Aufgabensammlung




# <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/4.png" width="40" height="40"> Eigene komplexere Kurse erstellen


SchulLia-Skill























# <img src="https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/refs/heads/main/pics/grad/5.png" width="40" height="40"> Reflexion


Formular einsendbar


