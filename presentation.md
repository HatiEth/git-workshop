# Git Workshop 
###<small> (auch für Designer)</small>

![](gifs/no_idea.gif)

Note:
+ Projekt ansehen
+ Aktueller Build
+ Assets anschauen im Level
+ Level bauen
+ Tweaking, Testing etc.



## Git Hoster

+ [Bitbucket](bitbucket.org) [¹](https://www.atlassian.com/software/views/bitbucket-academic-license.jsp)
+ [GitHub](github.com) [¹](https://education.github.com/)
+ [Projektlaufwerk FH Trier RZ](https://www.hochschule-trier.de/index.php?id=16238)
+ [GitLab FSI](https://gitlab.fsi.hochschule-trier.de/users/sign_in)

----

<small>¹ academic license</small>

Note:
+ Alle kostenlos (studentisch)
+ 2x FH
+ Zeigen werde ich Bitbucket und GitHub



## Workflow

<span>clone <!-- .element: class="fragment"--></span>
<span>$\rightarrow{}$ <!-- .element: class="fragment" --></span>
<span>**Änderungen** <!-- .element: class="fragment" --></span>
<span>$\leftrightarrow{}$ <!-- .element: class="fragment" --></span>
<span>add <!-- .element: class="fragment" --></span>
<span>$\leftrightarrow{}$ <!-- .element: class="fragment" --></span>
<span>commit <!-- .element: class="fragment" --></span>
<span>$\leftrightarrow{}$ <!-- .element: class="fragment" --></span>
<span>push <!-- .element: class="fragment" --></span>

Note:
+ Clone => Herunterladen
+ Add => Hinzufügen
+ Commit => Dazu stehen
+ Push => Hochladen


<span>pull <!-- .element: class="fragment"--></span>
<span>$\leftrightarrow{}$ <!-- .element: class="fragment" --></span>
<span>**Änderungen** <!-- .element: class="fragment" --></span>
<span>$\leftrightarrow{}$ <!-- .element: class="fragment" --></span>
<span>add <!-- .element: class="fragment" --></span>
<span>$\leftrightarrow{}$ <!-- .element: class="fragment" --></span>
<span>commit <!-- .element: class="fragment" --></span>
<span>$\leftrightarrow{}$ <!-- .element: class="fragment" --></span>
<span>push <!-- .element: class="fragment" --></span>

Note:
+ Pull => Updaten



## Branches

+ "Versionen"
+ Mehrere Historien
+ Arbeitsbereiche

Note:
Asset-Branches, Mergen


![](gifs/refactoring-00.gif)<!-- .element: class="fragment" -->

Note:
Tests, Refactoring, halbfertige Sachen


## Merge Conflicts

![](gifs/Git-merge-conflict.gif)

Note:
Sind nicht schlimm!
Müssen passieren



## Tags

![](gifs/presentation-version.gif)

Note:
Versionsnummern / Markierungen



## Nebeneffekte

![](gifs/makes-sense-00.gif)

Note:
Fast umsonst kriegt man folgendes:
Arbeitsdokumentation, Änderungshistorie, Hotfixes einspielbar,
Präsentationsspeicher


### Lockerer Code

![](gifs/end-of-projects-01.gif)


### Backups

![](gifs/i-quit.gif)

Note:

+ "Computer kaputt Änderung weg"
+ Branches (die Länger als 1 Tag dauern) sollten 1x am Tag hochgeladen werden


### Raum für Experimente

![](gifs/bug-found.gif)

Note:
Grafiktests, Stiltests, Lichteinstellungen, etc.



## Tools

+ TortoiseGit<!-- .element: class="fragment" -->
+ SourceTree<!-- .element: class="fragment" -->
+ GitExtensions<!-- .element: class="fragment" -->
+ GitHub<!-- .element: class="fragment" -->
+ SmartGit<!-- .element: class="fragment" -->
+ u.v.m.<!-- .element: class="fragment" -->


## Git-LFS

[https://git-lfs.github.com/](https://git-lfs.github.com/)

Note:
Für große Dateien (Texturen, Audio, etc.) gibt es Git-LFS



## Workshop (Tortoise Git)

![](gifs/pass-code.gif)

Note:

1. Clonen (Bitbucket und GitHub - FSI GitLab funktioniert analog)
+ Https (SSH später)
+ Änderung machen
+ Commiten
+ Pushen



## Unity Specifics

<div style="float: left">Edit/Project Settings/Editor
	<div>
	<small>Version Control: Visible Meta Files</small></div>
	<div><small>Asset Serializaton: Force Text</small></div>
</div>

![](images/inspector.png)



![](images/gitignore.io.png)

Note:

+ Nicht perfekt, aber gute Basis
+ Download als Datei
+ schnell erweiterbar
+ Tag basiert



## Danke

[GitHub.io Präsentation](http://hatieth.github.io/git-workshop)

[GitHub Repo der Präsentation](https://github.com/hatieth/git-workshop)
