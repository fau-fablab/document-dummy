document-dummy
==============

Ein Demodokument als Vorlage für andere [FAU FabLab](https://fablab.fau.de)-Dokumente mit der Klasse [fablab-document](https://github.com/fau-fablab/fablab-document).

Inhalt
------

- `demo.tex`: minimales Beispiel mit Titel, Abschnitten und Kopf-/Fußzeile im FabLab-Layout
- Zum Anlegen eines neuen Dokuments siehe `fablab-document/README_deployment.md`

Download
--------

Die neueste Version aus [GitHub](https://github.com/fau-fablab/document-dummy) ist als PDF abrufbar:

- [Demo](https://brain.fablab.fau.de/build/document-dummy/demo.pdf)

Auschecken und bauen
--------------------

```bash
git clone --recursive git@github.com:fau-fablab/document-dummy.git
cd document-dummy
make
```

Die PDFs landen in `output/`. Layout, Kopf- und Fußzeile und das Logo des FAU FabLab (mit
FAU-Schriftzug) kommen aus dem Untermodul [fablab-document](https://github.com/fau-fablab/fablab-document),
das Logo wiederum aus dessen Untermodul [logo](https://github.com/fau-fablab/logo). Bei einem bestehenden
Klon die Untermodule mit `git submodule update --init --recursive` laden.

Technische Details zum Buildserver: [fau-fablab/buildserver](https://github.com/fau-fablab/buildserver)

[![Build Status](https://brain.fablab.fau.de/build/document-dummy/status.svg)](https://brain.fablab.fau.de/build/document-dummy/)
[![TODOs](https://brain.fablab.fau.de/build/document-dummy/status-todos.svg)](https://brain.fablab.fau.de/build/document-dummy/)

Lizenz
------

[![Lizenz: CC BY-SA 3.0](https://licensebuttons.net/l/by-sa/3.0/de/88x31.png)</br>CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/)
