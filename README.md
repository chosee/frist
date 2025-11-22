# Schweizer Fristenrechner | Calculateur de délais suisse

🇩🇪 [Deutsch](#deutsch) | 🇫🇷 [Français](#français)

---

<a name="deutsch"></a>
## 🇩🇪 Deutsch

Berechne juristische Fristen nach der Schweizerischen Zivilprozessordnung (ZPO).

**[frist.ch](https://frist.ch)**

### Berechnungsregeln

Dieser Rechner implementiert die Artikel 142-146 ZPO. Die Berechnungslogik ist vollständig Open Source.

#### Art. 142 ZPO – Beginn und Berechnung

**Abs. 1: Tagesfristen**
> Fristen, die durch eine Mitteilung oder den Eintritt eines Ereignisses ausgelöst werden, beginnen am folgenden Tag zu laufen.

```
Fristende = Zustelldatum + Anzahl Tage
```

**Abs. 2: Monatsfristen** (inkl. BGer 5A_691/2023)
> Berechnet sich eine Frist nach Monaten, so endet sie im letzten Monat an dem Tag, der dieselbe Zahl trägt wie der Tag, an dem die Frist zu laufen begann.

**Wichtig:** Gemäss Bundesgerichtsurteil 5A_691/2023 beginnt die Monatsfrist am **Tag der Zustellung**.

**Abs. 3: Fristende an Wochenende/Feiertag**
> Fällt der letzte Tag einer Frist auf einen Samstag, einen Sonntag oder einen [...] Feiertag, so endet sie am nächsten Werktag.

#### Art. 145 ZPO – Gerichtsferien (Fristenstillstand)

Gesetzliche und gerichtliche Fristen stehen still:
- **Ostern**: 7 Tage vor bis 7 Tage nach Ostersonntag
- **Sommer**: 15. Juli bis 15. August
- **Winter**: 18. Dezember bis 2. Januar

**Ausnahmen (Abs. 2):** Schlichtungsverfahren und summarisches Verfahren

#### Art. 146 ZPO – Zustellung während Gerichtsferien

Wird während Gerichtsferien zugestellt, beginnt die Frist am ersten Tag nach Ferienende.

### Feiertage

**National:** Neujahr, Auffahrt, Nationalfeiertag (1. August), Weihnachten

**Kantonal wählbar:** Berchtoldstag, Dreikönige, Josephstag, Karfreitag, Ostermontag, Tag der Arbeit, Pfingstmontag, Fronleichnam, Mariä Himmelfahrt, Allerheiligen, Maria Empfängnis, Stephanstag

---

<a name="français"></a>
## 🇫🇷 Français

Calculez les délais juridiques selon le Code de procédure civile suisse (CPC).

**[frist.ch](https://frist.ch)**

### Règles de calcul

Ce calculateur implémente les articles 142-146 CPC. La logique de calcul est entièrement open source.

#### Art. 142 CPC – Computation

**Al. 1 : Délais en jours**
> Les délais déclenchés par la communication ou la survenance d'un événement courent dès le lendemain de celles-ci.

```
Fin du délai = Date de notification + Nombre de jours
```

**Al. 2 : Délais en mois** (incl. TF 5A_691/2023)
> Lorsqu'un délai est fixé en mois, il expire le jour du dernier mois correspondant au jour où il a commencé à courir.

**Important :** Selon l'arrêt du Tribunal fédéral 5A_691/2023, le délai en mois commence le **jour de la notification**.

**Al. 3 : Fin du délai un week-end/jour férié**
> Si le dernier jour est un samedi, un dimanche ou un jour férié reconnu [...], le délai expire le premier jour ouvrable qui suit.

#### Art. 145 CPC – Suspension des délais (Féries judiciaires)

Les délais légaux et judiciaires ne courent pas :
- **Pâques** : Du 7e jour avant au 7e jour après Pâques inclus
- **Été** : Du 15 juillet au 15 août inclus
- **Hiver** : Du 18 décembre au 2 janvier inclus

**Exceptions (al. 2) :** Procédure de conciliation et procédure sommaire

#### Art. 146 CPC – Notification pendant les féries

Si la notification a lieu pendant les féries, le délai commence le premier jour après la fin des féries.

### Jours fériés

**Nationaux :** Nouvel An, Ascension, Fête nationale (1er août), Noël

**Cantonaux (sélectionnables) :** Saint-Berchtold, Épiphanie, Saint-Joseph, Vendredi saint, Lundi de Pâques, Fête du travail, Lundi de Pentecôte, Fête-Dieu, Assomption, Toussaint, Immaculée Conception, Saint-Étienne

---

## Technologie | Technologie

- Single-Page-App (HTML/CSS/JavaScript)
- Aucun backend – calculs côté client
- Hébergé sur Cloudflare Pages
- Open Source

## Avertissement | Avertissement

Ce calculateur sert uniquement d'orientation. Vous êtes seul responsable du respect des délais. En cas de doute, consultez un avocat.

Dieser Rechner dient nur zur Orientierung. Für die Wahrung von Fristen sind Sie selbst verantwortlich. Im Zweifelsfall konsultieren Sie einen Rechtsanwalt.

## Licence | Lizenz

MIT

---

[Durchblick Consultancy BV](https://durchblick.nl) • [Source Code](https://github.com/chosee/frist)
