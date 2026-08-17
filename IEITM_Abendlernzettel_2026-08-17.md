# Abendlernzettel – Montag, 17.08.2026

**Klausur:** Internes/Externes IT-Management  
**Schwerpunkte:** Vertragsarten und Tagessätze · ITSM/FitSM · Incident/Problem Management · ITIL/ISO 20000 · DevOps  
**Bearbeitungszeit:** ca. 35–45 Minuten

> **Ablauf:** Öffne zunächst nur die Fragen der Karteikarten. Antworte laut oder schriftlich aus dem Gedächtnis und klappe erst danach die jeweilige Antwort auf. Bearbeite anschließend die 20 Single-Choice-Fragen ohne Unterlagen.

---

## Teil A – Karteikarten

### Karte 1 – Wodurch unterscheiden sich ANÜ, Dienstvertrag und Werkvertrag?

<details>
<summary>Antwort anzeigen</summary>

- **Arbeitnehmerüberlassung (ANÜ):** Der überlassene Arbeitnehmer ist in die Arbeitsorganisation des Kunden eingegliedert und dessen Weisungen unterworfen.
- **Dienstvertrag:** Der Auftragnehmer schuldet ein sorgfältiges Tätigwerden, aber keinen bestimmten Erfolg. Er organisiert die Leistung grundsätzlich eigenverantwortlich.
- **Werkvertrag:** Der Auftragnehmer schuldet einen konkret definierten und abnahmefähigen Erfolg beziehungsweise ein Werk.

**Prüfungsregel:** Nicht die Überschrift des Vertrags, sondern die **tatsächlich gelebte Zusammenarbeit** ist entscheidend.

</details>

### Karte 2 – Welche Risiken bestehen beim Body Leasing?

<details>
<summary>Antwort anzeigen</summary>

Wird ein angeblicher Dienst- oder Werkvertrag praktisch wie eine Arbeitnehmerüberlassung gelebt, droht eine **verdeckte ANÜ**. Bei Freelancern besteht zusätzlich das Risiko der **Scheinselbstständigkeit**.

Für eine reguläre ANÜ sind insbesondere relevant:

- ausdrückliche Kennzeichnung als Arbeitnehmerüberlassung,
- erforderliche Erlaubnis,
- Information des Betriebsrats,
- Equal Pay beziehungsweise Equal Treatment,
- grundsätzlich höchstens 18 Monate Überlassungsdauer.

</details>

### Karte 3 – Wie werden fakturierbare Leistungstage und Auslastung berechnet?

<details>
<summary>Antwort anzeigen</summary>

Ein typisches Kursmodell lautet:

\[
365-104\text{ Wochenendtage}-13\text{ Feiertage}-28\text{ Urlaubstage}-10\text{ sonstige Tage}=210
\]

Damit gilt:

\[
\text{erwartete fakturierbare Tage}=210\times\text{erwartete Auslastung}
\]

\[
\text{Auslastung}=\frac{\text{tatsächlich fakturierte Tage}}{\text{maximal fakturierbare Tage}}
\]

\[
\text{Umsatz}=\text{fakturierte Tage}\times\text{Tagessatz}
\]

</details>

### Karte 4 – Welche drei Regeln gelten für die Tagessatzkalkulation?

<details>
<summary>Antwort anzeigen</summary>

1. **Nenner:** maximale Leistungstage × erwartete Auslastung.
2. **Zähler:** sämtliche zurechenbaren Kosten, also Gehalt, Personalnebenkosten, direkte Kosten und anteilige Gemeinkosten.
3. **Gewinn:** Ein Gewinnzuschlag wird auf den **kostendeckenden Tagessatz** gerechnet. Eine interne IT kalkuliert typischerweise ohne Gewinnzuschlag.

\[
\text{kostendeckender Tagessatz}=\frac{\text{Vollkosten}}{\text{erwartete fakturierbare Tage}}
\]

Bei einem **Gewinnaufschlag** von \(g\):

\[
\text{Verkaufspreis}=\text{Kostenpreis}\times(1+g)
\]

Bei einer **Gewinnmarge** von \(m\) auf den Umsatz:

\[
\text{Verkaufspreis}=\frac{\text{Kostenpreis}}{1-m}
\]

**Achtung:** 20 % Aufschlag und 20 % Marge sind nicht dasselbe.

</details>

### Karte 5 – Was bedeutet IT-Service-Management?

<details>
<summary>Antwort anzeigen</summary>

ITSM umfasst alle Aktivitäten eines Service Providers zur **Planung, Bereitstellung, Erbringung, Steuerung und Verbesserung von IT-Services**. Im Mittelpunkt steht der durch Services erzeugte Kundennutzen, nicht eine einzelne Technologie.

Die Rollen **Service Provider** und **Kunde** gelten unabhängig davon, ob die IT-Leistung intern oder extern erbracht wird.

</details>

### Karte 6 – Wie unterscheiden sich ISO 20000, ITIL und FitSM?

<details>
<summary>Antwort anzeigen</summary>

- **ISO/IEC 20000:** internationale Norm für ein Service-Management-System; zertifiziert wird die **Organisation beziehungsweise der Service Provider**.
- **ITIL:** umfangreiche Sammlung von Good Practices für IT-Service-Management; persönliche Zertifizierungen sind möglich.
- **FitSM:** leichtgewichtiger, frei verfügbarer und mit ISO 20000 sowie ITIL kompatibler ITSM-Ansatz; ebenfalls persönliche Zertifizierungen.

**Merksatz:** ISO 20000 verlangt, **was** ein Managementsystem leisten muss; ITIL und FitSM helfen bei der Ausgestaltung des **Wie**.

</details>

### Karte 7 – Welche FitSM-Kerndokumente gibt es?

<details>
<summary>Antwort anzeigen</summary>

- **FitSM-0:** Begriffe und Definitionen
- **FitSM-1:** Anforderungen an ein wirksames Service-Management-System
- **FitSM-2:** Ziele und empfohlene Aktivitäten
- **FitSM-3:** Rollenmodell

FitSM-1 enthält **16 allgemeine Anforderungen in 7 Kategorien** und **69 prozessspezifische Anforderungen in 14 Kategorien**.

</details>

### Karte 8 – Welche 14 FitSM-Prozesse müssen bekannt sein?

<details>
<summary>Antwort anzeigen</summary>

| Kürzel | Prozess | Kernziel |
|---|---|---|
| SPM | Service Portfolio Management | Serviceportfolio steuern |
| SLM | Service Level Management | Serviceziele vereinbaren und überwachen |
| SRM | Service Reporting Management | aussagekräftige Serviceberichte liefern |
| SACM | Service Availability and Continuity Management | Verfügbarkeit und Kontinuität sichern |
| CAPM | Capacity Management | ausreichende Kapazität und Leistung sicherstellen |
| ISM | Information Security Management | Informationssicherheit steuern |
| CRM | Customer Relationship Management | Kundenbeziehung und Anforderungen pflegen |
| SUPPM | Supplier Relationship Management | Lieferanten und deren Leistungen steuern |
| ISRM | Incident and Service Request Management | Störungen beheben und Anfragen erfüllen |
| PM | Problem Management | Ursachen wiederkehrender Incidents beseitigen |
| CONFM | Configuration Management | verlässliche Konfigurationsinformationen bereitstellen |
| CHM | Change Management | Änderungen bewerten und kontrollieren |
| RDM | Release and Deployment Management | Releases planen und ausrollen |
| CSI | Continual Service Improvement Management | Services und Prozesse fortlaufend verbessern |

</details>

### Karte 9 – Wie definiert FitSM Service, IT-Service, Service Provider und SLA?

<details>
<summary>Antwort anzeigen</summary>

- **Service:** Mittel zur Bereitstellung von Wert, indem vom Kunden gewünschte Ergebnisse ermöglicht werden.
- **IT-Service:** ein durch Informationstechnologie ermöglichter Service.
- **Service Provider:** Organisation oder Zusammenschluss, der Services für Kunden verwaltet und erbringt.
- **SLA:** dokumentierte Vereinbarung zwischen Service Provider und Kunde, die den Service und seine Serviceziele festlegt.

</details>

### Karte 10 – Worin unterscheiden sich Incident und Service Request?

<details>
<summary>Antwort anzeigen</summary>

- **Incident:** ungeplante Unterbrechung oder Qualitätsminderung eines Services, zum Beispiel ein ausgefallener Mailserver.
- **Service Request:** Anfrage nach Information, Beratung, Zugriff oder einer vorab genehmigten Standardänderung, zum Beispiel die Einrichtung eines Standardzugangs.

Beide werden im FitSM-Prozess **ISRM** behandelt, aber unterschiedlich klassifiziert.

</details>

### Karte 11 – Wie verläuft der Ticket-Lebenszyklus und was ist ein Major Incident?

<details>
<summary>Antwort anzeigen</summary>

Der typische Ablauf lautet:

1. registrieren,
2. klassifizieren,
3. priorisieren,
4. eskalieren beziehungsweise zuweisen,
5. lösen,
6. schließen.

Ein **Major Incident** besitzt besonders hohe Auswirkung und Dringlichkeit und benötigt deshalb ein besonderes, beschleunigtes Vorgehen.

</details>

### Karte 12 – Wie hängen SLA, OLA und UA zusammen?

<details>
<summary>Antwort anzeigen</summary>

- **SLA:** Vereinbarung zwischen Service Provider und Kunde.
- **OLA:** interne unterstützende Vereinbarung zwischen Einheiten desselben Service Providers.
- **UA:** unterstützende Vereinbarung mit einem externen Lieferanten.

OLA und UA müssen so ausgestaltet sein, dass der Service Provider die im SLA zugesagten Ziele erfüllen kann.

</details>

### Karte 13 – Welche Rollen gibt es in FitSM?

<details>
<summary>Antwort anzeigen</summary>

- **Top Management:** trägt die Gesamtverantwortung und stellt Rahmen sowie Ressourcen bereit.
- **Process Owner:** verantwortet Zweck, Design und Wirksamkeit eines Prozesses.
- **Process Manager:** steuert die operative Ausführung eines Prozesses.
- **Process Staff Member:** führt Prozessaktivitäten aus.
- **Incident/Service Request Owner:** verantwortet den Lebenszyklus eines konkreten Tickets.

**Merksatz:** Owner verantwortet den Prozess als Ganzes; Manager organisiert den laufenden Betrieb.

</details>

### Karte 14 – Worin unterscheiden sich Incident und Problem Management?

<details>
<summary>Antwort anzeigen</summary>

- **Incident Management:** Service möglichst schnell wiederherstellen; ein Workaround ist zulässig.
- **Problem Management:** zugrunde liegende Ursachen identifizieren, Known Errors dokumentieren und erneute Incidents verhindern.

Ein **Problem** ist die Ursache eines oder mehrerer Incidents. Ein **Known Error** ist ein analysiertes Problem mit bekannter Ursache oder bekanntem Workaround.

</details>

### Karte 15 – Welche Entwicklungsschritte von ITIL sind klausurrelevant?

<details>
<summary>Antwort anzeigen</summary>

- Ursprung bei der britischen **CCTA**, zunächst 42 Bücher.
- **ITIL v2 (2000):** vor allem Service Support und Service Delivery.
- **ITIL v3 (2007):** Service Lifecycle, 26 Prozesse und Continual Service Improvement.
- **ITIL 2011:** Aktualisierung von v3.
- **ITIL 4 (2019):** modernisierte, ganzheitlichere Ausrichtung.
- Die Marke wurde von **AXELOS** betreut.

</details>

### Karte 16 – Was ist bei ISO 20000 besonders wichtig?

<details>
<summary>Antwort anzeigen</summary>

Wichtige Fassungen erschienen 2005, 2011 und 2018. In der behandelten Struktur umfassen die Teile insbesondere:

- **Teil 1:** verbindliche Anforderungen beziehungsweise Spezifikation,
- **Teil 2:** Anwendungshinweise,
- **Teil 3:** Hinweise zur Festlegung des Geltungsbereichs,
- **Teil 4:** Prozessreferenzmodell,
- **Teil 5:** exemplarischer Implementierungsplan.

Zertifiziert wird der **Service Provider**, nicht ein einzelner Mitarbeiter.

</details>

### Karte 17 – Welche Kritik wird an klassischem ITSM beziehungsweise ITIL geübt?

<details>
<summary>Antwort anzeigen</summary>

Häufige Kritikpunkte sind:

- zu viel Bürokratie und Prozessaufwand,
- tayloristische Arbeitsteilung und viele Übergaben,
- starres Dienstleister-Kunden-Denken,
- langsame Entscheidungen, etwa durch schwerfällige CAB-Strukturen.

Das Beispiel **Projekt Phoenix** verdeutlicht, wie Silos, lange Freigabeketten und lokale Optimierung den Gesamtfluss behindern können.

</details>

### Karte 18 – Was bedeutet DevOps und welche vier Prinzipien gelten?

<details>
<summary>Antwort anzeigen</summary>

DevOps ist eine **Bewegung und Denkweise**, kein einzelner verbindlicher Standard. Leitgedanke: **„You build it, you run it.“**

Vier Grundprinzipien:

1. Trennung von Business, Development und Operations durch cross-funktionale Zusammenarbeit überwinden.
2. End-to-End-Fluss und schnelle Feedbackschleifen schaffen.
3. Vertrauenskultur, Experimente und einen lernenden Umgang mit Risiken fördern.
4. Wiederkehrende Abläufe weitgehend automatisieren.

</details>

### Karte 19 – Warum entsteht zwischen Build und Run häufig ein Konflikt?

<details>
<summary>Antwort anzeigen</summary>

- **Build/Projekt:** Veränderung unter Einhaltung von Zeit, Budget und Umfang.
- **Run/Betrieb:** stabiler, unterbrechungsfreier und kostengünstiger Betrieb.

Die Übergabe über Service Transition beziehungsweise Deployment wird zur Bruchstelle, wenn getrennte Einheiten unterschiedliche Ziele verfolgen. DevOps reduziert diese Bruchstelle durch gemeinsame Ende-zu-Ende-Verantwortung.

</details>

### Karte 20 – Welche zwei kumulativen Regeln dürfen nicht verloren gehen?

<details>
<summary>Antwort anzeigen</summary>

1. **PPM:** Auch ein Muss-Projekt braucht Kosten-, Risiko- und Ressourceninformationen. Der Umsetzungszwang ersetzt nicht die wirtschaftliche Steuerung.
2. **Tagessatz:** Erst Vollkosten und erwartete fakturierbare Tage bestimmen, dann den kostendeckenden Satz und zuletzt den korrekt bezeichneten Gewinnaufschlag oder die Gewinnmarge berechnen.

</details>

---

## Teil B – 20 Single-Choice-Fragen

**Regel:** Genau eine Antwort ist richtig. Notiere zuerst nur den Buchstaben und öffne die Lösung erst danach.

### Frage 1

Welches Merkmal spricht am stärksten für eine Arbeitnehmerüberlassung?

- A) Der Auftragnehmer schuldet ein abnahmefähiges Werk.
- B) Der Mitarbeiter ist in die Kundenorganisation eingegliedert und erhält Weisungen vom Kunden.
- C) Der Auftragnehmer entscheidet allein über die geschuldete Ergebnisqualität.
- D) Der Vertrag trägt die Überschrift „Dienstvertrag“.

<details>
<summary>Lösung anzeigen</summary>

**Richtig: B.** Eingliederung und Weisungsgebundenheit sind zentrale Merkmale der ANÜ. Die tatsächliche Praxis ist wichtiger als die Vertragsüberschrift.

</details>

### Frage 2

Was schuldet ein Auftragnehmer aus einem Dienstvertrag typischerweise?

- A) Einen bestimmten, abnahmefähigen Erfolg
- B) Ausschließlich die Überlassung eigener Arbeitnehmer
- C) Sorgfältiges Tätigwerden, aber keinen bestimmten Erfolg
- D) Eine garantierte Kosteneinsparung beim Kunden

<details>
<summary>Lösung anzeigen</summary>

**Richtig: C.** Beim Dienstvertrag wird die fachgerechte Tätigkeit geschuldet; beim Werkvertrag steht der definierte Erfolg im Mittelpunkt.

</details>

### Frage 3

Ein Vertrag heißt „Werkvertrag“, die eingesetzten Personen arbeiten jedoch dauerhaft nach Einzelanweisungen des Kunden in dessen Teams. Welche Aussage trifft zu?

- A) Die Vertragsüberschrift verhindert jedes ANÜ-Risiko.
- B) Entscheidend ist die tatsächliche Durchführung; eine verdeckte ANÜ ist möglich.
- C) Es liegt automatisch ein Dienstvertrag ohne weitere Risiken vor.
- D) Nur die Höhe des Tagessatzes entscheidet über die Vertragsart.

<details>
<summary>Lösung anzeigen</summary>

**Richtig: B.** Für die rechtliche Einordnung ist die gelebte Zusammenarbeit maßgeblich.

</details>

### Frage 4

Eine Beratungskraft kann maximal 16 Tage pro Monat fakturieren und fakturiert tatsächlich 14 Tage. Wie hoch ist ihre Auslastung?

- A) 80,0 %
- B) 85,0 %
- C) 87,5 %
- D) 114,3 %

<details>
<summary>Lösung anzeigen</summary>

**Richtig: C.** \(14/16=0{,}875=87{,}5\,\%\).

</details>

### Frage 5

Welche Aussage beschreibt ITSM am besten?

- A) ITSM betrifft ausschließlich externe IT-Dienstleister.
- B) ITSM ist nur die technische Überwachung von Servern.
- C) ITSM umfasst die Aktivitäten zur Planung, Erbringung und Steuerung von IT-Services.
- D) ITSM ist mit Projektportfoliomanagement identisch.

<details>
<summary>Lösung anzeigen</summary>

**Richtig: C.** ITSM ist serviceorientiert und gilt sowohl für interne als auch externe Provider-Kunden-Beziehungen.

</details>

### Frage 6

Welches FitSM-Dokument enthält Begriffe und Definitionen?

- A) FitSM-0
- B) FitSM-1
- C) FitSM-2
- D) FitSM-3

<details>
<summary>Lösung anzeigen</summary>

**Richtig: A.** FitSM-0 enthält die Terminologie; FitSM-1 Anforderungen, FitSM-2 Ziele und Aktivitäten sowie FitSM-3 Rollen.

</details>

### Frage 7

Welche Zahlenkombination gehört zu den Anforderungen in FitSM-1?

- A) 14 allgemeine und 7 prozessspezifische Anforderungen
- B) 16 allgemeine und 69 prozessspezifische Anforderungen
- C) 26 allgemeine und 42 prozessspezifische Anforderungen
- D) 40 allgemeine und 75 prozessspezifische Anforderungen

<details>
<summary>Lösung anzeigen</summary>

**Richtig: B.** FitSM-1 umfasst 16 allgemeine Anforderungen in 7 Kategorien sowie 69 prozessspezifische Anforderungen in 14 Kategorien.

</details>

### Frage 8

Was ist ein SLA?

- A) Eine interne Vereinbarung zweier Abteilungen ohne Kundenbezug
- B) Ein ausschließlich technisches Monitoring-Protokoll
- C) Eine dokumentierte Vereinbarung zwischen Provider und Kunde über Service und Serviceziele
- D) Ein Vertrag zur Arbeitnehmerüberlassung

<details>
<summary>Lösung anzeigen</summary>

**Richtig: C.** Das SLA konkretisiert den vereinbarten Service und die zu erreichenden Ziele.

</details>

### Frage 9

Welches Beispiel ist ein Incident?

- A) Ein Nutzer bestellt einen vorab genehmigten Standardzugang.
- B) Ein Nutzer bittet um eine Bedienungsanleitung.
- C) Der zentrale Maildienst ist ungeplant nicht erreichbar.
- D) Ein Kunde verhandelt neue Ziele für das kommende SLA.

<details>
<summary>Lösung anzeigen</summary>

**Richtig: C.** Der ungeplante Ausfall ist eine Unterbrechung des Services und damit ein Incident.

</details>

### Frage 10

Welches Beispiel ist am ehesten ein Service Request?

- A) Ein Datenbankserver fällt unerwartet aus.
- B) Die Antwortzeiten eines Services verschlechtern sich ungeplant.
- C) Ein Nutzer beantragt einen standardmäßig vorgesehenen Softwarezugang.
- D) Eine Störung tritt zum zehnten Mal mit derselben unbekannten Ursache auf.

<details>
<summary>Lösung anzeigen</summary>

**Richtig: C.** Ein Standardzugang ist eine typische vorab genehmigte Anfrage.

</details>

### Frage 11

Welche Zuordnung ist richtig?

- A) OLA = Vereinbarung mit externem Lieferanten; UA = Vereinbarung mit dem Kunden
- B) OLA = interne Unterstützungsvereinbarung; UA = Vereinbarung mit externem Lieferanten
- C) OLA = Kunden-SLA; UA = internes Prozesshandbuch
- D) OLA und UA sind zwei Bezeichnungen für einen Incident

<details>
<summary>Lösung anzeigen</summary>

**Richtig: B.** OLA unterstützt das SLA intern; ein UA stützt es durch eine Vereinbarung mit einem externen Lieferanten.

</details>

### Frage 12

Welche Reihenfolge des Ticket-Lebenszyklus ist richtig?

- A) priorisieren → registrieren → schließen → klassifizieren → lösen
- B) registrieren → klassifizieren → priorisieren → zuweisen/eskalieren → lösen → schließen
- C) klassifizieren → schließen → registrieren → lösen → priorisieren
- D) registrieren → lösen → priorisieren → klassifizieren → schließen

<details>
<summary>Lösung anzeigen</summary>

**Richtig: B.** Erst wird das Ticket erfasst und eingeordnet; nach Priorisierung und Bearbeitung folgen Lösung und Abschluss.

</details>

### Frage 13

Welche Aussage zu FitSM-Rollen ist richtig?

- A) Der Process Manager definiert allein die Unternehmensstrategie.
- B) Der Process Owner verantwortet Design und Wirksamkeit des Prozesses.
- C) Der Ticket Owner zertifiziert den Service Provider nach ISO 20000.
- D) Process Staff Members dürfen keine Prozessaktivitäten ausführen.

<details>
<summary>Lösung anzeigen</summary>

**Richtig: B.** Der Process Owner trägt die übergreifende Prozessverantwortung; der Process Manager steuert die operative Durchführung.

</details>

### Frage 14

Was ist das vorrangige Ziel des Problem Managements?

- A) Jede Störung möglichst schnell mit irgendeinem Workaround schließen
- B) Ursachen von Incidents erkennen und Wiederholungen verhindern
- C) Service Requests nach Eingangszeit sortieren
- D) Ausschließlich neue Releases ausrollen

<details>
<summary>Lösung anzeigen</summary>

**Richtig: B.** Problem Management arbeitet ursachenorientiert; Incident Management priorisiert die schnelle Wiederherstellung.

</details>

### Frage 15

Welche Aussage zur ITIL-Historie ist richtig?

- A) ITIL v2 wurde 2019 als Service Value System veröffentlicht.
- B) ITIL v3 führte 2007 den Service-Lifecycle-Ansatz mit 26 Prozessen ein.
- C) ITIL entstand als deutsche ISO-Norm.
- D) ITIL 2011 war die erste Fassung mit Service Support und Service Delivery.

<details>
<summary>Lösung anzeigen</summary>

**Richtig: B.** v2 erschien 2000; v3 folgte 2007 mit Lifecycle und 26 Prozessen; ITIL 4 erschien 2019.

</details>

### Frage 16

Wer beziehungsweise was wird nach ISO/IEC 20000 zertifiziert?

- A) Ausschließlich eine einzelne IT-Fachkraft
- B) Ein einzelnes Incident-Ticket
- C) Der Service Provider beziehungsweise dessen Service-Management-System
- D) Nur das verwendete Ticketsystem

<details>
<summary>Lösung anzeigen</summary>

**Richtig: C.** ISO 20000 ist eine Organisationszertifizierung; persönliche Zertifikate gehören zu Methoden beziehungsweise Frameworks wie ITIL oder FitSM.

</details>

### Frage 17

Welche Einordnung von DevOps ist am treffendsten?

- A) Eine verbindliche internationale Zertifizierungsnorm
- B) Eine reine Cloud-Preismethode
- C) Eine Bewegung und Denkweise für gemeinsame Ende-zu-Ende-Verantwortung
- D) Eine Form der Arbeitnehmerüberlassung

<details>
<summary>Lösung anzeigen</summary>

**Richtig: C.** DevOps ist kein einzelner Standard, sondern verbindet kulturelle, organisatorische und technische Praktiken.

</details>

### Frage 18

Welche Maßnahme widerspricht den DevOps-Grundprinzipien?

- A) Schnelle Feedbackschleifen
- B) Weitgehende Automatisierung wiederkehrender Abläufe
- C) Gemeinsame Verantwortung von Entwicklung und Betrieb
- D) Möglichst viele organisatorische Übergaben und getrennte Ziele

<details>
<summary>Lösung anzeigen</summary>

**Richtig: D.** DevOps soll Silos und Übergabeverluste gerade reduzieren.

</details>

### Frage 19

Warum benötigt ein Muss-Projekt im PPM weiterhin Kosten- und Risikoinformationen?

- A) Damit entschieden werden kann, ob die gesetzliche Pflicht ignoriert wird
- B) Damit Umsetzung, Ressourcen und Risiken trotz Umsetzungszwang wirtschaftlich gesteuert werden können
- C) Weil Muss-Projekte stets den höchsten ROI besitzen
- D) Weil Muss-Projekte nicht in das Portfolio aufgenommen werden dürfen

<details>
<summary>Lösung anzeigen</summary>

**Richtig: B.** Die Pflicht zur Umsetzung beseitigt weder Budgetknappheit noch Risiken und Abhängigkeiten.

</details>

### Frage 20

Die Vollkosten pro fakturierbarem Tag betragen 500 €. Gefordert ist eine Gewinnmarge von 20 % auf den Umsatz. Welcher externe Tagessatz ist richtig?

- A) 600 €
- B) 620 €
- C) 625 €
- D) 650 €

<details>
<summary>Lösung anzeigen</summary>

**Richtig: C.** Bei einer Marge gilt \(500/(1-0{,}20)=625\) €. Ein bloßer Aufschlag von 20 % ergäbe dagegen 600 €.

</details>

---

## Teil C – Aktiver Abschluss ohne Unterlagen

Beantworte jede Aufgabe in höchstens drei Minuten:

1. Erkläre ANÜ, Dienstvertrag und Werkvertrag anhand je eines entscheidenden Merkmals.
2. Erkläre an einem selbst gewählten Beispiel den Zusammenhang zwischen Incident, Problem, Known Error und Workaround.
3. Nenne die vier DevOps-Prinzipien und erkläre, welches Problem an der Build-Run-Schnittstelle sie lösen sollen.

---

## Auswertung

- **18–20 richtig:** sehr gute Tagesleistung; morgen nur kurz wiederholen.
- **15–17 richtig:** gute Grundlage; falsche Fragen als Karteikarten übernehmen.
- **12–14 richtig:** die betroffenen Karten am Dienstagmorgen erneut aktiv abrufen.
- **0–11 richtig:** zuerst Grundlagen festigen, bevor du eine weitere Vollklausur schreibst.

**Fehlerprotokoll:** Notiere zu jedem Fehler nicht nur die richtige Antwort, sondern auch, warum deine gewählte Antwort falsch war.
