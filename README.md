# kronio
<!DOCTYPE html>
<html lang="el">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Σπήλαιο Τράπεζας (Κρόνιο)</title>
  <style>
    :root {
      --primary: #2c5f5d;
      --secondary: #f4f1de;
      --accent: #e07a5f;
      --text: #1f2933;
    }

    body {
      margin: 0;
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
      background: var(--secondary);
      color: var(--text);
      line-height: 1.6;
    }

    header {
      background: linear-gradient(180deg, #2c5f5d, #1f3f3e);
      color: #fff;
      padding: 1.5rem 1rem;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 1.6rem;
    }

    header p {
      margin: 0.4rem 0 0;
      font-size: 0.95rem;
      opacity: 0.9;
    }

    .lang {
      display: flex;
      justify-content: center;
      gap: 0.5rem;
      padding: 0.7rem;
      background: #fff;
      position: sticky;
      top: 0;
      z-index: 10;
      box-shadow: 0 2px 6px rgba(0,0,0,0.05);
    }

    .lang button {
      border: none;
      background: #eee;
      padding: 0.4rem 0.7rem;
      border-radius: 20px;
      cursor: pointer;
      font-size: 0.85rem;
    }

    .lang button.active {
      background: var(--primary);
      color: #fff;
    }

    main {
      padding: 1rem;
      max-width: 700px;
      margin: auto;
    }

    section {
      background: #fff;
      margin-bottom: 1rem;
      padding: 1rem 1.1rem;
      border-radius: 14px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.04);
    }

    section h2 {
      margin-top: 0;
      font-size: 1.15rem;
      color: var(--primary);
      border-bottom: 1px solid #eee;
      padding-bottom: 0.3rem;
    }

    ul {
      padding-left: 1.1rem;
    }

    a {
      color: var(--accent);
      text-decoration: none;
      font-weight: 600;
    }

    footer {
      text-align: center;
      font-size: 0.8rem;
      color: #666;
      padding: 1.2rem 0 1.5rem;
    }

    [data-lang] { display: none; }
    [data-lang].active { display: block; }
  </style>
</head>
<body>

<header>
  <h1>Σπήλαιο Τράπεζας</h1>
  <p>Κρόνιο Σπήλαιο – Οροπέδιο Λασιθίου</p>
</header>

<div class="lang">
  <button class="active" onclick="setLang('el', this)">🇬🇷 EL</button>
  <button onclick="setLang('en', this)">🇬🇧 EN</button>
  <button onclick="setLang('de', this)">🇩🇪 DE</button>
  <button onclick="setLang('fr', this)">🇫🇷 FR</button>
</div>

<main>

<div data-lang="el" class="active">
  <section>
    <h2>📘 Ιστορία & Περιγραφή</h2>
    <p>Το Σπήλαιο Τράπεζας, γνωστό και ως Κρόνιο Σπήλαιο, βρίσκεται ανάμεσα στα χωριά Μαρμακέτο και Τζερμιάδο του Οροπεδίου Λασιθίου, σε υψόμετρο περίπου 860 μέτρων. Βρίσκεται πολύ κοντά στον περιφερειακό δρόμο που ενώνει το Μαρμακέτο με το Γυμνάσιο Τζερμιάδου και η πρόσβαση επισημαίνεται με πινακίδες και από τα δύο χωριά.</p>
    <p>Ένα ανηφορικό καλντερίμι με σκαλοπάτια, πνιγμένο στους πρίνους, οδηγεί στο σπήλαιο μετά από περίπου πέντε λεπτά ανάβασης. Η είσοδος είναι διακριτική, όμως η πανοραμική θέα προς το Οροπέδιο Λασιθίου από το σημείο αυτό είναι ιδιαίτερα εντυπωσιακή.</p>
    <p>Το Κρόνιο αποτελείται από δύο κύριες αίθουσες με ανάπτυξη σε μικρές κόγχες. Η είσοδος είναι στενή και ένας υγρός διάδρομος με πρασινωπές αποχρώσεις οδηγεί σε μια μικρή αίθουσα, όπου διακρίνονται σπασμένοι σταλακτίτες και σταλαγμίτες από ανθρώπινες παρεμβάσεις. Ένας μεγάλος σταλαγμίτης στο κέντρο σχηματίζει δύο πλευρικά περάσματα, ενώ μικρές κόγχες με κολονάκια εμφανίζονται στα τοιχώματα.</p>
  </section>

  <section>
    <h2>🏺 Αρχαιολογικά Ευρήματα</h2>
    <p>Στο σπήλαιο έχουν εντοπιστεί ίχνη ανθρώπινης παρουσίας ήδη από τη Νεολιθική εποχή. Αρχικά χρησιμοποιήθηκε ως τόπος κατοίκησης, ενώ σε μεταγενέστερες περιόδους λειτούργησε ως χώρος ταφής και λατρείας, ιδιαίτερα όταν κατοικήθηκε ο λόφος Κάστελος στα ανατολικά του Τζερμιάδου.</p>
    <p>Οι αρχαιολογικές ανασκαφές αποκάλυψαν σημαντικά ευρήματα από τη Νεολιθική έως και τη Βυζαντινή περίοδο, όπως φύλλα χρυσού, ειδώλια από φαγεντιανή και ελεφαντόδοντο. Ιδιαίτερη σημασία έχουν οι αιγυπτιακοί σκαραβαίοι της 11ης Δυναστείας, που αποδεικνύουν τις αρχαίες πολιτισμικές επαφές μεταξύ Κρήτης και Αιγύπτου.</p>
  </section>

  <section>
    <h2>⚡ Μύθος του Δία</h2>
    <p>Το Κρόνιο Σπήλαιο, μαζί με το Δικταίο Άντρο, συνδέεται άρρηκτα με τον μύθο της γέννησης του Δία. Σύμφωνα με την ελληνική μυθολογία, ο Κρόνος κατάπινε τα παιδιά του για να αποτρέψει την προφητεία που προέβλεπε την ανατροπή του από έναν απόγονό του.</p>
    <p>Όταν η Ρέα γέννησε τον Δία, τον έκρυψε στο Δικταίο Άντρο (Σπήλαιο Ψυχρού), σώζοντάς τον από τον Κρόνο και επιτρέποντας την εκπλήρωση της μοίρας του ως πατέρα των θεών.</p>
  </section>

  <section>
    <h2>ℹ️ Πληροφορίες Επίσκεψης</h2>
    <ul>
      <li>🚶 Χρόνος ανάβασης: περίπου 5 λεπτά</li>
      <li>🪨 Ανηφορικό καλντερίμι με σκαλοπάτια</li>
      <li>👟 Συνιστάται κατάλληλο υπόδημα</li>
      <li>⚠️ Προσοχή σε χαμηλή οροφή και ολισθηρά σημεία</li>
    </ul>
  </section>
</div>

<div data-lang="en">
  <section>
    <h2>📘 History & Description</h2>
    <p>The Trapeza Cave, also known as the Kronio Cave, lies on the Lasithi Plateau at an altitude of about 860 meters.</p>
  </section>
</div>

<div data-lang="de">
  <section>
    <h2>📘 Geschichte & Beschreibung</h2>
    <p>Die Trapeza-Höhle befindet sich auf der Lassithi-Hochebene in etwa 860 Metern Höhe.</p>
  </section>
</div>

<div data-lang="fr">
  <section>
    <h2>📘 Histoire & Description</h2>
    <p>La grotte de Trapeza est située sur le plateau du Lassithi à environ 860 mètres d’altitude.</p>
  </section>
</div>

</main>

<footer>
  © Σημείο Πληροφόρησης – Παρακαλούμε σεβαστείτε τον χώρο
</footer>

<script>
  function setLang(lang, btn) {
    document.querySelectorAll('[data-lang]').forEach(el => el.classList.remove('active'));
    document.querySelector('[data-lang="' + lang + '"]').classList.add('active');

    document.querySelectorAll('.lang button').forEach(b => b.classList.remove('active'));
    btn.classList.add('active');

    localStorage.setItem('lang', lang);
  }

  const saved = localStorage.getItem('lang');
  if (saved) {
    const btn = [...document.querySelectorAll('.lang button')].find(b => b.textContent.includes(saved.toUpperCase()));
    if (btn) setLang(saved, btn);
  }
</script>

</body>
</html>
