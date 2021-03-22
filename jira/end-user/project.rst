*******
Project
*******


Rationale
=========
- Project Lead
- Categories

    - Department
    - Team
    - Project
    - Product

- Project vs. Boards
- Issue Collector


Issue key
=========
- short
- easy to remember
- 2-10 uppercase letters


Project Configuration
=====================
- Versions
- Components
- Users and Roles
- Application Links


Versions
========
* Semantic Versioning: major.minor.bugfix - (1.2.3, 3.9.1)
* Convention:

    * ``YYYY-MM`` - 2000-01, 2000-02, 2000-03
    * ``YYYY-QX`` - 2000-Q1, 2000-Q2, 2000-Q3, 2000-Q4
    * ``YYYY`` - 2000, 2001, 2002, 2003

* Roadmap
* Releases (with Bamboo)
* Time Tracking Report by Version

.. figure:: ../_img/scrum-capacity-backlog.png
.. figure:: ../_img/jira-release-versions.png
.. figure:: ../_img/jira-release-overview.png


AffectsVersion vs FixVersion
============================
Affects Version/s:

    * MyApp 1.0 (assume this is unsupported)
    * MyApp 2.0
    * MyApp 3.0

Fix Version/s:

    * MyApp 2.0.1
    * MyApp 3.0.5


Demonstration
=============
* Go to project settings
* Change project avatar
* Change project name
* Add project component (mention `Default assignee` problem)
* Add and reorder versions
* Add user to role
* Add field to issue (mention switching to `Field` tab)
* Add tab to issue fields


Assignments
===========

Project Details
---------------
#. Z menu u góry wybierz `Projects` -> Twój Projekt -> `Project Settings` (przycisk koła zębatego w menu po lewej na samym dole)
#. Zakładka `Details` -> zmień awatar swojego projektu na rakietę
#. Zakładka `Details` -> zmień nazwę swojego projektu na `Imię N.` (z kropką na końcu)

Project Components
------------------
#. Z menu u góry wybierz `Projects` -> Twój Projekt -> `Project Settings` (przycisk koła zębatego w menu po lewej na samym dole)
#. Przejdź na zakładkę `Components`
#. Dodaj: `Frontend`, `Backend`, `Database`
#. Aby przycisk `Add` stał się aktywny musisz:

    * dodać komponent należy wpisać jego nazwę (w polu po lewej)
    * z ostatniej listy rozwijanej (po prawej przy zaraz koło przycisku add) wybrać jedną z opcji np. `Unassigned`

Project Versions
----------------
#. Z menu u góry wybierz `Projects` -> Twój Projekt -> `Project Settings` (przycisk koła zębatego w menu po lewej na samym dole)
#. Przejdź na zakładkę `Versions`
#. Dodając wersje w tym zadaniu nie musisz ustawiać dat rozpoczęcia i zakończenia
#. Dla uproszczenia w zadaniach, a później w `JQL` i filtrach będę stosował konwencję z rokiem `2000`
#. Możesz dodać wersje z dzisiejszą datą (rokiem), ale w kolejnych zadaniach pamiętaj, żeby podmieniać na swoje nazwy
#. Dodaj: `2000-Q2`, `2000-Q3`
#. Dodaj: `2001`, `2002`

Project Roles
-------------
#. Z menu u góry wybierz `Projects` -> Twój Projekt -> `Project Settings` (przycisk koła zębatego w menu po lewej na samym dole)
#. Przejdź na zakładkę `Users and roles`
#. Dodaj siebie do roli `Administrators`
#. Dodaj użytkownika `admin` do roli `Developers`

Project Fields
--------------
#. Z menu u góry wybierz `Projects` -> Twój Projekt -> `Project Settings` (przycisk koła zębatego w menu po lewej na samym dole)
#. Przejdź na zakładkę `Issue Types`
#. Wybierz `Task`, a następnie w prawym górnym rogu wybierz przycisk `Fields` -> dodaj pole `Due Date`, usuń pole `Labels`
#. Wybierz `Story`, a następnie w prawym górnym rogu wybierz przycisk `Fields` -> dodaj nową zakładkę `Estimate` , dodaj na niej pole `Time Tracking` oraz `Story Points`; pasek z zakładkami jest u góry tam gdzie jest `Field Tab` i ikonka ołówka; nową zakładkę dodaje się poprzez kliknięcie na znak `(+)`
#. Zwróć uwagę, że ta zakładka `Estimate`, która stworzyłeś/aś pojawiła się w prawie każdym `Issue Type` (poza `Bug`)
