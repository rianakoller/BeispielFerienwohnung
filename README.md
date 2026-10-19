<!doctype html>
<html lang="de" data-lang="de">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="description" content="Ferienwohnung in Brülisau im Alpstein: 2 Schlafzimmer, bis 7 Personen. Holiday apartment in Brülisau, Appenzell Innerrhoden.">
<title>Ferienwohnung Brülisauer</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,500;12..96,700&family=Source+Sans+3:wght@400;600&display=swap">
<style>
[hidden]{display:none!important}
body{margin:0}
img{max-width:100%}
/* Layout: eine ruhige Seite in Abschnitten, Alpstein-Grün, Bergsilhouette im Titelbereich, Kalender und Anfrage als Herzstück. */
:root {
  color-scheme: light;
  --bg: #f2f5f3;
  --surface: #ffffff;
  --fg: #17282a;
  --muted: #55696b;
  --line: #d3dcd9;
  --accent: #1f5c5a;
  --accent-fg: #ffffff;
  --sun: #d9a21b;
  --booked: #e7d3d0;
  --booked-fg: #8a4b45;
  --sel: #1f5c5a;
  --font-display: "Bricolage Grotesque", "Segoe UI", system-ui, sans-serif;
  --font-body: "Source Sans 3", "Segoe UI", system-ui, sans-serif;
}
@media (prefers-color-scheme: dark) {
  :root:not([data-theme="light"]) {
    --bg: #0f1b1c; --surface: #172627; --fg: #e6efec; --muted: #9db2b0; --line: #2a3d3e;
    --accent: #6cc2b8; --accent-fg: #0b1717; --sun: #e5b440; --booked: #3b2a28; --booked-fg: #e0a9a2; --sel: #6cc2b8;
    color-scheme: dark;
  }
}
:root[data-theme="dark"] {
  --bg: #0f1b1c; --surface: #172627; --fg: #e6efec; --muted: #9db2b0; --line: #2a3d3e;
  --accent: #6cc2b8; --accent-fg: #0b1717; --sun: #e5b440; --booked: #3b2a28; --booked-fg: #e0a9a2; --sel: #6cc2b8;
  color-scheme: dark;
}
* { box-sizing: border-box; }
body {
  background: var(--bg); color: var(--fg); font-family: var(--font-body); font-size: 17px; line-height: 1.6;
  padding-left: max(16px, env(safe-area-inset-left, 0px));
  padding-right: max(16px, env(safe-area-inset-right, 0px));
  padding-block: 0;
}
html[data-lang="en"] .de, html[data-lang="de"] .en { display: none; }
.wrap { max-width: 1040px; margin: 0 auto; }
h1, h2, h3 { font-family: var(--font-display); line-height: 1.15; text-wrap: balance; margin: 0; }
h2 { font-size: clamp(1.7rem, 4vw, 2.3rem); margin-bottom: 14px; }
h3 { font-size: 1.15rem; margin-bottom: 6px; }
p { margin: 0 0 12px; max-width: 65ch; }
a { color: var(--accent); }
a:focus-visible, button:focus-visible, input:focus-visible, select:focus-visible, textarea:focus-visible { outline: 3px solid var(--sun); outline-offset: 2px; }
.label { font-size: .78rem; letter-spacing: .12em; text-transform: uppercase; color: var(--muted); font-weight: 600; }

.topbar { display: flex; justify-content: space-between; align-items: center; gap: 12px; padding: 16px 0; flex-wrap: wrap; }
.brand { font-family: var(--font-display); font-weight: 700; font-size: 1.1rem; }
nav { display: flex; gap: 16px; align-items: center; flex-wrap: wrap; font-size: .95rem; }
nav a { text-decoration: none; color: var(--fg); }
nav a:hover { color: var(--accent); }
.lang { display: inline-flex; border: 1px solid var(--line); border-radius: 999px; overflow: hidden; }
.lang button { font: inherit; font-size: .85rem; background: transparent; color: var(--fg); border: 0; padding: 4px 12px; cursor: pointer; }
.lang button[aria-pressed="true"] { background: var(--accent); color: var(--accent-fg); }

.hero { padding: 28px 0 40px; display: grid; gap: 28px; grid-template-columns: 1.1fr 1fr; align-items: center; }
.hero h1 { font-size: clamp(2.2rem, 6vw, 3.6rem); margin: 8px 0 14px; }
.hero .lead { font-size: 1.15rem; color: var(--muted); }
.facts { display: flex; gap: 8px 20px; flex-wrap: wrap; margin: 18px 0 22px; padding: 0; list-style: none; font-weight: 600; }
.facts li { white-space: nowrap; }
.btn { display: inline-block; font: inherit; font-weight: 600; background: var(--accent); color: var(--accent-fg); border: 0; border-radius: 6px; padding: 12px 22px; text-decoration: none; cursor: pointer; }
.btn:hover { filter: brightness(1.08); }
.btn.ghost { background: transparent; color: var(--accent); border: 1.5px solid var(--accent); }

.photo { border-radius: 6px; background: var(--surface); border: 1.5px dashed var(--line); aspect-ratio: 4 / 3; max-width: 100%; display: grid; place-items: center; text-align: center; color: var(--muted); font-size: .9rem; padding: 12px; position: relative; overflow: hidden; }
.photo svg { position: absolute; inset: 0; width: 100%; height: 100%; opacity: .5; }
.photo span { position: relative; background: var(--bg); padding: 4px 10px; border-radius: 4px; }
.photo.big { aspect-ratio: 5 / 4; }

section { padding: 44px 0; border-top: 1px solid var(--line); }
.gallery { display: grid; grid-template-columns: repeat(3, 1fr); gap: 12px; margin-top: 18px; }
.cols { display: grid; grid-template-columns: 1fr 1fr; gap: 28px; }
.rooms { display: grid; grid-template-columns: repeat(3, 1fr); gap: 14px; margin-top: 14px; }
.room { background: var(--surface); border: 1px solid var(--line); border-radius: 6px; padding: 16px; min-width: 0; }
.room p { margin: 0; color: var(--muted); font-size: .95rem; }
.amen { display: grid; grid-template-columns: repeat(auto-fill, minmax(210px, 1fr)); gap: 8px 22px; padding: 0; margin: 14px 0 0; list-style: none; }
.amen li { padding: 6px 0; border-bottom: 1px solid var(--line); }
.note { font-size: .88rem; color: var(--muted); }
.todo { background: color-mix(in srgb, var(--sun) 22%, transparent); border-radius: 3px; padding: 0 5px; }

table.price { border-collapse: collapse; width: 100%; max-width: 560px; margin-top: 10px; }
table.price td { padding: 10px 0; border-bottom: 1px solid var(--line); }
table.price td:last-child { text-align: right; font-variant-numeric: tabular-nums; font-weight: 600; }

.cal-wrap { background: var(--surface); border: 1px solid var(--line); border-radius: 6px; padding: 18px; }
.cal-head { display: flex; justify-content: space-between; align-items: center; margin-bottom: 12px; gap: 8px; }
.cal-head button { font: inherit; background: transparent; color: var(--fg); border: 1px solid var(--line); border-radius: 6px; padding: 4px 14px; cursor: pointer; }
.cal-months { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 22px; }
.cal-month h3 { text-align: center; font-size: 1rem; }
.grid { display: grid; grid-template-columns: repeat(7, 1fr); gap: 3px; }
.dow { text-align: center; font-size: .72rem; color: var(--muted); padding: 4px 0; }
.day { aspect-ratio: 1; display: grid; place-items: center; font: inherit; font-size: .9rem; font-variant-numeric: tabular-nums; border: 0; border-radius: 4px; background: transparent; color: var(--fg); cursor: pointer; padding: 0; min-width: 0; }
.day:hover:not(:disabled) { background: color-mix(in srgb, var(--accent) 16%, transparent); }
.day:disabled { cursor: not-allowed; opacity: .4; }
.day.booked { background: var(--booked); color: var(--booked-fg); text-decoration: line-through; opacity: 1; }
.day.inrange { background: color-mix(in srgb, var(--sel) 22%, transparent); border-radius: 0; }
.day.edge { background: var(--sel); color: var(--accent-fg); }
.legend { display: flex; gap: 18px; flex-wrap: wrap; margin-top: 14px; font-size: .85rem; color: var(--muted); }
.legend i { display: inline-block; width: 12px; height: 12px; border-radius: 3px; vertical-align: -1px; margin-right: 6px; }

form { display: grid; grid-template-columns: 1fr 1fr; gap: 14px; margin-top: 14px; }
form .full { grid-column: 1 / -1; }
label { display: grid; gap: 4px; font-weight: 600; font-size: .92rem; min-width: 0; }
input, select, textarea { font: inherit; font-weight: 400; color: var(--fg); background: var(--surface); border: 1px solid var(--line); border-radius: 6px; padding: 10px 12px; width: 100%; min-width: 0; }
textarea { min-height: 110px; resize: vertical; }
.out { background: var(--surface); border: 1px solid var(--accent); border-radius: 6px; padding: 18px; margin-top: 18px; }
.out pre { white-space: pre-wrap; word-break: break-word; font-family: inherit; background: var(--bg); padding: 12px; border-radius: 6px; margin: 10px 0; }
.out .row { display: flex; gap: 10px; flex-wrap: wrap; align-items: center; }

footer { border-top: 1px solid var(--line); padding: 28px 0 40px; font-size: .92rem; color: var(--muted); display: grid; gap: 16px; grid-template-columns: 1fr 1fr; }
footer h3 { color: var(--fg); font-size: 1rem; }

@media (max-width: 760px) {
  .hero, .cols, footer, form { grid-template-columns: 1fr; }
  .rooms, .gallery { grid-template-columns: 1fr; }
  body { font-size: 16px; }
}
@media (prefers-reduced-motion: reduce) { * { scroll-behavior: auto !important; } }
html { scroll-behavior: smooth; }
</style>
</head>
<body>
<div class="wrap">
  <header class="topbar">
    <div class="brand">Ferienwohnung Brülisauer</div>
    <nav>
      <a href="#wohnung"><span class="de">Wohnung</span><span class="en">Apartment</span></a>
      <a href="#lage"><span class="de">Lage</span><span class="en">Location</span></a>
      <a href="#preise"><span class="de">Preise</span><span class="en">Prices</span></a>
      <a href="#kalender"><span class="de">Verfügbarkeit</span><span class="en">Availability</span></a>
      <a href="#anfrage"><span class="de">Anfrage</span><span class="en">Enquiry</span></a>
      <span class="lang" role="group" aria-label="Sprache / Language">
        <button type="button" data-set="de" aria-pressed="true">DE</button>
        <button type="button" data-set="en" aria-pressed="false">EN</button>
      </span>
    </nav>
  </header>

  <div class="hero">
    <div>
      <div class="label">Brülisau · Appenzell Innerrhoden</div>
      <h1><span class="de">Ferien im Alpstein, mit Platz für die ganze Familie</span><span class="en">Holidays in the Alpstein, with room for the whole family</span></h1>
      <p class="lead"><span class="de">Zwei Schlafzimmer, bis zu 7 Gäste und die Wanderwege des Alpsteins direkt vor der Tür.</span><span class="en">Two bedrooms, up to 7 guests and the hiking trails of the Alpstein right on your doorstep.</span></p>
      <ul class="facts">
        <li><span class="de">bis 7 Personen</span><span class="en">up to 7 guests</span></li>
        <li><span class="de">2 Schlafzimmer</span><span class="en">2 bedrooms</span></li>
        <li><span class="de">5 Betten + Couch</span><span class="en">5 beds + sofa</span></li>
      </ul>
      <a class="btn" href="#anfrage"><span class="de">Jetzt anfragen</span><span class="en">Send an enquiry</span></a>
      <a class="btn ghost" href="#kalender"><span class="de">Freie Tage ansehen</span><span class="en">See free dates</span></a>
    </div>
    <div class="photo big">
      <svg viewBox="0 0 400 320" preserveAspectRatio="xMidYMax slice" aria-hidden="true"><path d="M0 320V210l60-70 40 40 70-110 55 80 45-50 60 90 70-40v180z" fill="currentColor" opacity=".25"/><path d="M0 320V250l80-50 60 30 90-70 70 60 100-30v130z" fill="currentColor" opacity=".25"/></svg>
      <span><span class="de">Titelfoto folgt</span><span class="en">Cover photo coming soon</span></span>
    </div>
  </div>

  <section id="wohnung">
    <div class="label"><span class="de">Die Wohnung</span><span class="en">The apartment</span></div>
    <h2><span class="de">Schlafen, kochen, ankommen</span><span class="en">Sleep, cook, arrive</span></h2>
    <p><span class="de">Die möblierte Ferienwohnung bietet Platz für bis zu 7 Personen. Fünf Gäste schlafen in richtigen Betten, zwei weitere finden auf der Couch Platz.</span><span class="en">The furnished apartment sleeps up to 7 people. Five guests sleep in proper beds, two more can sleep on the sofa.</span></p>
    <div class="rooms">
      <div class="room"><h3><span class="de">Schlafzimmer 1</span><span class="en">Bedroom 1</span></h3><p><span class="de">1 Doppelbett</span><span class="en">1 double bed</span></p></div>
      <div class="room"><h3><span class="de">Schlafzimmer 2</span><span class="en">Bedroom 2</span></h3><p><span class="de">1 Doppelbett und 1 Einzelbett</span><span class="en">1 double bed and 1 single bed</span></p></div>
      <div class="room"><h3><span class="de">Wohnbereich</span><span class="en">Living area</span></h3><p><span class="de">Couch mit Schlafmöglichkeit für bis zu 2 weitere Personen</span><span class="en">Sofa bed for up to 2 more guests</span></p></div>
    </div>
    <h3 style="margin-top:26px"><span class="de">Ausstattung</span><span class="en">Amenities</span> <span class="todo note"><span class="de">Platzhalter, bitte anpassen</span><span class="en">placeholder, please edit</span></span></h3>
    <ul class="amen">
      <li><span class="de">Voll ausgestattete Küche</span><span class="en">Fully equipped kitchen</span></li>
      <li>WLAN</li>
      <li><span class="de">Bettwäsche und Handtücher</span><span class="en">Bed linen and towels</span></li>
      <li><span class="de">Parkplatz</span><span class="en">Parking</span></li>
      <li><span class="de">Balkon oder Sitzplatz</span><span class="en">Balcony or seating area</span></li>
      <li><span class="de">Haustiere: nach Absprache</span><span class="en">Pets: on request</span></li>
      <li><span class="de">Nichtraucherwohnung</span><span class="en">Non-smoking</span></li>
    </ul>
    <div class="gallery">
      <div class="photo"><span><span class="de">Foto: Wohnzimmer</span><span class="en">Photo: living room</span></span></div>
      <div class="photo"><span><span class="de">Foto: Küche</span><span class="en">Photo: kitchen</span></span></div>
      <div class="photo"><span><span class="de">Foto: Schlafzimmer</span><span class="en">Photo: bedroom</span></span></div>
    </div>
  </section>

  <section id="lage">
    <div class="cols">
      <div>
        <div class="label"><span class="de">Lage</span><span class="en">Location</span></div>
        <h2>Brülisau</h2>
        <p><span class="de">Brülisau liegt am Fuss des Alpsteins im Kanton Appenzell Innerrhoden. Von hier starten Wanderungen zum Hohen Kasten, zum Sämtisersee und in die Berge rund um den Säntis. Im Winter gibt es Schneeschuhrouten und Winterwanderwege.</span><span class="en">Brülisau lies at the foot of the Alpstein in the canton of Appenzell Innerrhoden. Hikes start here towards the Hoher Kasten, the Sämtisersee and the mountains around the Säntis. In winter there are snowshoe routes and winter walking trails.</span></p>
        <p class="note"><span class="todo"><span class="de">Hier können wir Entfernungen ergänzen, etwa zur Seilbahn, zum Dorfladen und nach Appenzell.</span><span class="en">Distances can be added here, e.g. to the cable car, the village shop and Appenzell.</span></span></p>
      </div>
      <div class="photo"><span><span class="de">Foto: Umgebung</span><span class="en">Photo: surroundings</span></span></div>
    </div>
  </section>

  <section id="preise">
    <div class="label"><span class="de">Preise</span><span class="en">Prices</span></div>
    <h2><span class="de">Was ein Aufenthalt kostet</span><span class="en">What a stay costs</span></h2>
    <table class="price">
      <tr><td><span class="de">Pro Nacht, bis 2 Personen</span><span class="en">Per night, up to 2 guests</span></td><td><span class="todo">CHF ___</span></td></tr>
      <tr><td><span class="de">Pro Nacht, jede weitere Person</span><span class="en">Per night, each additional guest</span></td><td><span class="todo">CHF ___</span></td></tr>
      <tr><td><span class="de">Endreinigung</span><span class="en">Final cleaning</span></td><td><span class="todo">CHF ___</span></td></tr>
      <tr><td><span class="de">Kurtaxe pro Person und Nacht</span><span class="en">Tourist tax per person and night</span></td><td><span class="todo">CHF ___</span></td></tr>
    </table>
    <p class="note" style="margin-top:12px"><span class="de">Check-in ab <span class="todo">__:__</span> Uhr, Check-out bis <span class="todo">__:__</span> Uhr. Mindestaufenthalt: <span class="todo">__</span> Nächte.</span><span class="en">Check-in from <span class="todo">__:__</span>, check-out by <span class="todo">__:__</span>. Minimum stay: <span class="todo">__</span> nights.</span></p>
  </section>

  <section id="kalender">
    <div class="label"><span class="de">Verfügbarkeit</span><span class="en">Availability</span></div>
    <h2><span class="de">Freie und belegte Tage</span><span class="en">Free and booked dates</span></h2>
    <p><span class="de">Wähle Anreise und Abreise im Kalender. Die Daten landen automatisch im Anfrageformular.</span><span class="en">Pick your arrival and departure in the calendar. The dates are carried over to the enquiry form.</span></p>
    <div class="cal-wrap">
      <div class="cal-head">
        <button type="button" id="prev" aria-label="Zurück / Previous">←</button>
        <span id="calTitle" class="label"></span>
        <button type="button" id="next" aria-label="Weiter / Next">→</button>
      </div>
      <div class="cal-months" id="months"></div>
      <div class="legend">
        <span><i style="background:var(--booked)"></i><span class="de">belegt</span><span class="en">booked</span></span>
        <span><i style="background:var(--sel)"></i><span class="de">deine Auswahl</span><span class="en">your selection</span></span>
        <span class="todo"><span class="de">Belegte Tage im Kalender sind Beispieldaten</span><span class="en">Booked dates shown are sample data</span></span>
      </div>
    </div>
  </section>

  <section id="anfrage">
    <div class="label"><span class="de">Anfrage</span><span class="en">Enquiry</span></div>
    <h2><span class="de">Unverbindlich anfragen</span><span class="en">Send a non-binding enquiry</span></h2>
    <p><span class="de">Es gibt keine Online-Buchung. Du schickst eine Anfrage und bekommst eine persönliche Antwort.</span><span class="en">There is no online booking. You send an enquiry and get a personal reply.</span></p>
    <form id="form">
      <label><span><span class="de">Name</span><span class="en">Name</span></span><input id="f-name" required autocomplete="name"></label>
      <label><span>E-Mail</span><input id="f-mail" type="email" required autocomplete="email"></label>
      <label><span><span class="de">Anreise</span><span class="en">Arrival</span></span><input id="f-from" type="date" required></label>
      <label><span><span class="de">Abreise</span><span class="en">Departure</span></span><input id="f-to" type="date" required></label>
      <label><span><span class="de">Personen</span><span class="en">Guests</span></span>
        <select id="f-pers"><option>1</option><option>2</option><option selected>3</option><option>4</option><option>5</option><option>6</option><option>7</option></select></label>
      <label><span><span class="de">Telefon (optional)</span><span class="en">Phone (optional)</span></span><input id="f-tel" type="tel" autocomplete="tel"></label>
      <label class="full"><span><span class="de">Nachricht</span><span class="en">Message</span></span><textarea id="f-msg"></textarea></label>
      <div class="full"><input type="checkbox" id="f-bot" tabindex="-1" autocomplete="off" style="display:none" aria-hidden="true"><button class="btn" id="submitBtn" type="submit"><span class="de">Anfrage vorbereiten</span><span class="en">Prepare enquiry</span></button></div>
    </form>
    <div class="out" id="sent" hidden role="status"><h3><span class="de">Danke für deine Anfrage</span><span class="en">Thank you for your enquiry</span></h3><p><span class="de">Sie ist bei uns angekommen. Wir melden uns so bald wie möglich per E-Mail.</span><span class="en">We have received it and will reply by email as soon as possible.</span></p></div>
    <div class="out" id="out" hidden>
      <h3><span class="de">Deine Anfrage ist bereit</span><span class="en">Your enquiry is ready</span></h3>
      <p class="note" id="failNote" hidden><span class="de">Das Senden hat nicht geklappt. Bitte schicke den Text per E-Mail.</span><span class="en">Sending did not work. Please send the text by email.</span></p>
      <p><span class="de">Sie wurde noch nicht gesendet. Kopiere den Text und schicke ihn an <strong>ferienwohnungbruelisauer@gmail.com</strong>.</span><span class="en">It has not been sent yet. Copy the text and send it to <strong>ferienwohnungbruelisauer@gmail.com</strong>.</span></p>
      <pre id="outText"></pre>
      <div class="row">
        <button class="btn" type="button" id="copy"><span class="de">Text kopieren</span><span class="en">Copy text</span></button>
        <a class="btn ghost" id="mailto" href="#"><span class="de">Im Mailprogramm öffnen</span><span class="en">Open in mail app</span></a>
        <span class="note" id="copied" hidden><span class="de">Kopiert</span><span class="en">Copied</span></span>
      </div>
    </div>
  </section>

  <footer>
    <div>
      <h3>Impressum</h3>
      <p><span class="todo">Vorname Nachname</span><br><span class="todo">Strasse Nr., PLZ Ort</span><br>ferienwohnungbruelisauer@gmail.com</p>
    </div>
    <div>
      <h3><span class="de">Datenschutz</span><span class="en">Privacy</span></h3>
      <p><span class="de">Angaben im Anfrageformular werden nur verwendet, um deine Anfrage zu beantworten. Das Formular wird über den Dienst Web3Forms an uns übermittelt. Für die Schrift werden Schriftarten von Google Fonts geladen, dabei wird deine IP-Adresse an Google übertragen.</span><span class="en">Details in the enquiry form are only used to answer your enquiry. The form is transmitted to us via the service Web3Forms. Fonts are loaded from Google Fonts, which transmits your IP address to Google.</span></p>
    </div>
  </footer>
</div>

<script>
(function () {
  // Belegte Zeiträume (Anreise bis Abreise-Tag, Abreise-Tag bleibt frei). Beispieldaten.
  var BOOKED = [["2026-11-06", "2026-11-09"], ["2026-11-20", "2026-11-23"], ["2026-12-26", "2027-01-02"]];
  var MONTHS_DE = ["Januar","Februar","März","April","Mai","Juni","Juli","August","September","Oktober","November","Dezember"];
  var MONTHS_EN = ["January","February","March","April","May","June","July","August","September","October","November","December"];
  var DOW_DE = ["Mo","Di","Mi","Do","Fr","Sa","So"], DOW_EN = ["Mo","Tu","We","Th","Fr","Sa","Su"];
  var lang = "de";

  function iso(d) { return d.getFullYear() + "-" + String(d.getMonth() + 1).padStart(2, "0") + "-" + String(d.getDate()).padStart(2, "0"); }
  function parse(s) { var p = s.split("-"); return new Date(+p[0], +p[1] - 1, +p[2]); }
  var bookedSet = {};
  BOOKED.forEach(function (r) {
    for (var d = parse(r[0]), end = parse(r[1]); d < end; d.setDate(d.getDate() + 1)) bookedSet[iso(d)] = true;
  });
  var today = new Date(); today.setHours(0, 0, 0, 0);
  var view = new Date(today.getFullYear(), today.getMonth(), 1);
  var arr = null, dep = null;

  function nightsBooked(a, b) {
    for (var d = parse(a); d < parse(b); d.setDate(d.getDate() + 1)) if (bookedSet[iso(d)]) return true;
    return false;
  }
  function render() {
    var host = document.getElementById("months"); host.innerHTML = "";
    var names = lang === "de" ? MONTHS_DE : MONTHS_EN, dows = lang === "de" ? DOW_DE : DOW_EN;
    var n = window.innerWidth < 640 ? 1 : 2;
    var t1 = names[view.getMonth()] + " " + view.getFullYear();
    document.getElementById("calTitle").textContent = t1;
    for (var m = 0; m < n; m++) {
      var first = new Date(view.getFullYear(), view.getMonth() + m, 1);
      var box = document.createElement("div"); box.className = "cal-month";
      var h = document.createElement("h3"); h.textContent = names[first.getMonth()] + " " + first.getFullYear(); box.appendChild(h);
      var g = document.createElement("div"); g.className = "grid";
      dows.forEach(function (x) { var e = document.createElement("div"); e.className = "dow"; e.textContent = x; g.appendChild(e); });
      var offset = (first.getDay() + 6) % 7;
      for (var i = 0; i < offset; i++) g.appendChild(document.createElement("div"));
      var days = new Date(first.getFullYear(), first.getMonth() + 1, 0).getDate();
      for (var d = 1; d <= days; d++) {
        var date = new Date(first.getFullYear(), first.getMonth(), d), key = iso(date);
        var b = document.createElement("button"); b.type = "button"; b.className = "day"; b.textContent = d; b.dataset.d = key;
        if (date < today) b.disabled = true;
        else if (bookedSet[key]) { b.classList.add("booked"); b.disabled = true; }
        if (arr && key === arr) b.classList.add("edge");
        if (dep && key === dep) b.classList.add("edge");
        if (arr && dep && key > arr && key < dep) b.classList.add("inrange");
        g.appendChild(b);
      }
      box.appendChild(g); host.appendChild(box);
    }
  }
  document.getElementById("months").addEventListener("click", function (e) {
    var b = e.target.closest(".day"); if (!b || b.disabled) return;
    var k = b.dataset.d;
    if (!arr || dep) { arr = k; dep = null; }
    else if (k > arr && !nightsBooked(arr, k)) { dep = k; }
    else { arr = k; dep = null; }
    document.getElementById("f-from").value = arr || "";
    document.getElementById("f-to").value = dep || "";
    render();
  });
  document.getElementById("prev").addEventListener("click", function () {
    var p = new Date(view.getFullYear(), view.getMonth() - 1, 1);
    if (p >= new Date(today.getFullYear(), today.getMonth(), 1)) { view = p; render(); }
  });
  document.getElementById("next").addEventListener("click", function () { view = new Date(view.getFullYear(), view.getMonth() + 1, 1); render(); });
  window.addEventListener("resize", render);

  function setLang(l) {
    lang = l; document.documentElement.setAttribute("data-lang", l); document.documentElement.lang = l;
    document.querySelectorAll(".lang button").forEach(function (b) { b.setAttribute("aria-pressed", b.dataset.set === l ? "true" : "false"); });
    render();
  }
  document.querySelectorAll(".lang button").forEach(function (b) { b.addEventListener("click", function () { setLang(b.dataset.set); }); });
  document.documentElement.setAttribute("data-lang", "de");

  var MAIL = "ferienwohnungbruelisauer@gmail.com";
  // Hier den kostenlosen Schlüssel von web3forms.com eintragen:
  var ACCESS_KEY = "HIER_WEB3FORMS_SCHLUESSEL_EINTRAGEN";
  var keyReady = ACCESS_KEY.indexOf("HIER_") !== 0;
  if (keyReady) {
    document.getElementById("submitBtn").innerHTML = '<span class="de">Anfrage senden</span><span class="en">Send enquiry</span>';
  }

  function showFallback(text, subject, failed) {
    document.getElementById("outText").textContent = text;
    document.getElementById("mailto").href = "mailto:" + MAIL + "?subject=" + encodeURIComponent(subject) + "&body=" + encodeURIComponent(text);
    document.getElementById("failNote").hidden = !failed;
    document.getElementById("out").hidden = false;
    document.getElementById("copied").hidden = true;
    document.getElementById("out").scrollIntoView({ block: "nearest" });
  }

  document.getElementById("form").addEventListener("submit", function (e) {
    e.preventDefault();
    if (document.getElementById("f-bot").checked) return;
    var v = function (id) { return document.getElementById(id).value.trim(); };
    var de = lang === "de";
    var lines = de
      ? ["Anfrage Ferienwohnung Brülisauer", "", "Name: " + v("f-name"), "E-Mail: " + v("f-mail"), "Telefon: " + (v("f-tel") || "-"), "Anreise: " + v("f-from"), "Abreise: " + v("f-to"), "Personen: " + v("f-pers"), "", v("f-msg")]
      : ["Enquiry Ferienwohnung Brülisauer", "", "Name: " + v("f-name"), "Email: " + v("f-mail"), "Phone: " + (v("f-tel") || "-"), "Arrival: " + v("f-from"), "Departure: " + v("f-to"), "Guests: " + v("f-pers"), "", v("f-msg")];
    var text = lines.join("\n");
    var subject = de ? "Anfrage Ferienwohnung" : "Enquiry holiday apartment";
    if (!keyReady) { showFallback(text, subject, false); return; }

    var btn = document.getElementById("submitBtn");
    btn.disabled = true;
    fetch("https://api.web3forms.com/submit", {
      method: "POST",
      headers: { "Content-Type": "application/json", "Accept": "application/json" },
      body: JSON.stringify({
        access_key: ACCESS_KEY,
        subject: subject + " - " + v("f-name"),
        from_name: v("f-name"),
        name: v("f-name"),
        email: v("f-mail"),
        message: text
      })
    }).then(function (r) { return r.json(); }).then(function (res) {
      btn.disabled = false;
      if (res && res.success) {
        document.getElementById("form").hidden = true;
        document.getElementById("out").hidden = true;
        document.getElementById("sent").hidden = false;
        document.getElementById("sent").scrollIntoView({ block: "nearest" });
      } else { showFallback(text, subject, true); }
    }).catch(function () { btn.disabled = false; showFallback(text, subject, true); });
  });
  document.getElementById("copy").addEventListener("click", function () {
    var text = document.getElementById("outText").textContent;
    var done = function () { document.getElementById("copied").hidden = false; };
    var fallback = function () {
      var r = document.createRange(); r.selectNodeContents(document.getElementById("outText"));
      var s = window.getSelection(); s.removeAllRanges(); s.addRange(r);
    };
    try { navigator.clipboard.writeText(text).then(done, fallback); } catch (err) { fallback(); }
  });

  render();
})();
</script>
</body>
</html>
