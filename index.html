<!DOCTYPE html>
<html lang="it">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PokéRole Dex</title>
    <link rel="manifest" href="manifest.json">
    <meta name="theme-color" content="#9e0000">

    <style>
        body {
            margin: 0;
            padding: 20px;
            font-family: 'Courier New', monospace;
            background: linear-gradient(135deg, #9e0000 0%, #d10000 40%, #c0c0c0 75%, #555 100%);
        }

        /* STRUTTURA */
        .pokedex {
            max-width: 700px;
            margin: auto;
            border-radius: 30px;
            padding: 25px;
            background: linear-gradient(145deg, #ff4646, #b30000);
            box-shadow:
                inset -8px -8px 15px rgba(0, 0, 0, 0.4),
                inset 5px 5px 10px rgba(255, 255, 255, 0.2),
                0 0 40px rgba(0, 0, 0, 0.6);
            position: relative;
        }

        /* LED */
        .led-container {
            position: absolute;
            top: 15px;
            left: 20px;
            display: flex;
            gap: 10px;
        }

        .led {
            width: 20px;
            height: 20px;
            border-radius: 50%;
        }

        .blue {
            background: #00ccff;
            box-shadow: 0 0 15px #00ccff;
        }

        .red {
            background: #ff0000;
            animation: blink 1s infinite;
        }

        .yellow {
            background: #ffcc00;
            animation: blink 1.5s infinite;
        }

        .green {
            background: #00ff66;
            animation: blink 2s infinite;
        }

        @keyframes blink {

            0%,
            100% {
                opacity: 1;
            }

            50% {
                opacity: 0.4;
            }
        }

        h1 {
            text-align: center;
            color: white;
            text-shadow: 2px 2px 4px black;
        }

        /* SCHERMO */
        .screen {
            margin-top: 40px;
            background: linear-gradient(145deg, #e6e6e6, #bfbfbf);
            border-radius: 20px;
            padding: 20px;
            box-shadow: inset 0 0 15px rgba(0, 0, 0, 0.4);
            color: #111;
            position: relative;
        }

        /* Effetto LCD pixel */
        .screen::after {
            content: "";
            position: absolute;
            inset: 0;
            background-image: repeating-linear-gradient(to bottom,
                    rgba(0, 0, 0, 0.05) 0px,
                    rgba(0, 0, 0, 0.05) 1px,
                    transparent 2px);
            pointer-events: none;
        }

        h2 {
            border-bottom: 2px solid #888;
        }

        .field {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 10px;
            flex-wrap: wrap;
        }

        input,
        select {
            width: 100px;
            max-width: 45%;
            padding: 8px;
            border-radius: 8px;
            border: 1px solid #888;
            text-align: center;
            font-size: 16px;
            /* evita zoom automatico su iPhone */
        }


        /* RISULTATI */
        .results {
            margin-top: 15px;
            background: linear-gradient(145deg, #333, #555);
            color: white;
            border-radius: 15px;
            padding: 15px;
        }

        .hp-bar-container {
            background: #999;
            border-radius: 10px;
            height: 20px;
            margin-top: 5px;
            overflow: hidden;
        }

        .hp-bar {
            height: 100%;
            width: 100%;
            background: limegreen;
            transition: 0.3s;
        }

        .footer {
            text-align: center;
            font-size: 12px;
            margin-top: 10px;
            color: white;
        }

        /* ===== MOBILE ===== */
        @media (max-width: 600px) {

            body {
                padding: 5px;
            }

            .pokedex {
                padding: 10px;
                border-radius: 18px;
            }

            .screen {
                padding: 10px;
            }

            h1 {
                font-size: 18px;
                margin-bottom: 10px;
            }

            h2 {
                font-size: 14px;
                margin: 10px 0 5px 0;
            }

            .field {
                flex-direction: row;
                justify-content: space-between;
                align-items: center;
                font-size: 13px;
            }

            input,
            select {
                width: 55px;
                /* dimensione compatta */
                padding: 4px;
                font-size: 13px;
            }

            .results {
                padding: 10px;
                font-size: 13px;
            }

            .results div {
                margin-bottom: 4px;
            }

            #difesaCommento {
                font-size: 11px;
                padding: 8px;
            }

            .led-container {
                transform: scale(0.7);
                top: 8px;
                left: 10px;
            }

            .footer {
                font-size: 10px;
            }
        }
    </style>
</head>

<body>

    <div class="pokedex">

        <div class="led-container">
            <div class="led blue"></div>
            <div class="led red"></div>
            <div class="led yellow"></div>
            <div class="led green"></div>
        </div>

        <h1>POKÉROLE DEX</h1>
        <div style="text-align:center; margin-bottom:15px;">
            <select id="lingua" onchange="cambiaLingua()" style="padding:5px; border-radius:6px;">
                <option value="it">IT</option>
                <option value="en">EN</option>
                <option value="es">ES</option>
                <option value="pt">PT</option>
                <option value="fr">FR</option>
                <option value="de">DE</option>
                <option value="ru">RU</option>
            </select>
        </div>

        <div class="screen">

            <h2>Caratteristiche</h2>
            <div class="field">Forza <input type="number" id="forza" value="0" oninput="calcola()"></div>
            <div class="field">Destrezza <input type="number" id="destrezza" value="0" oninput="calcola()"></div>
            <div class="field">Vitalità <input type="number" id="vitalita" value="0" oninput="calcola()"></div>
            <div class="field">Speciale <input type="number" id="speciale" value="0" oninput="calcola()"></div>
            <div class="field">Percezione <input type="number" id="percezione" value="0" oninput="calcola()"></div>

            <h2>Modalità Difesa</h2>
            <div class="field">
                <select id="difesaMode" onchange="calcola()">
                    <option value="tavolo">Opzione 1 - Esperienza da tavolo</option>
                    <option value="videogioco">Opzione 2 - Appassionati videogiochi</option>
                </select>
            </div>
            <div id="difesaCommento" style="
                margin-top:10px;
                padding:10px;
                border-radius:10px;
                background:rgba(0,0,0,0.1);
                font-size:13px;
                line-height:1.4;
            ">
            </div>


            <h2>Abilità</h2>
            <div class="field">Allerta <input type="number" id="allerta" value="0" oninput="calcola()"></div>
            <div class="field">Evasione <input type="number" id="evasione" value="0" oninput="calcola()"></div>
            <div class="field">Contrasto <input type="number" id="contrastoSkill" value="0" oninput="calcola()"></div>

            <div class="field">
                Contrasto
                <select id="contrastoBase" onchange="calcola()">
                    <option value="forza">Forza</option>
                    <option value="speciale">Speciale</option>
                </select>
            </div>

            <div class="results">
                <div>PS: <span id="ps"><b>4</b></span></div>
                <!--<div class="hp-bar-container">
                    <div class="hp-bar" id="hpBar"></div>
                </div>-->
                <div>Volontà: <span id="volonta"><b>3</b></span></div>
                <div>Iniziativa: <span id="iniziativa"><b>0</b></span></div>
                <div>Elusione: <span id="elusione"><b>0</b></span></div>
                <div>Contrasto Totale: <span id="contrastoTotale"><b>0</b></span></div>
                <div>Difesa: <span id="difesa"><b>0</b></span></div>
                <div>Difesa Speciale: <span id="difesaSpeciale"><b>0</b></span></div>
            </div>
            <div style="margin-top:15px; text-align:center;">
                <button onclick="exportCSV()">Export CSV</button>
                <button onclick="document.getElementById('importFile').click()">Import CSV</button>
                <input type="file" id="importFile" accept=".csv" style="display:none" onchange="importCSV(event)">
            </div>

        </div>

        <div class="footer">Sistema automatico Pokerole</div>
    </div>

    <script>
        const audioCtx = new (window.AudioContext || window.webkitAudioContext)();

        function beep() {
            const osc = audioCtx.createOscillator();
            const gain = audioCtx.createGain();
            osc.type = "square";
            osc.frequency.value = 700;
            gain.gain.value = 0.05;
            osc.connect(gain);
            gain.connect(audioCtx.destination);
            osc.start();
            osc.stop(audioCtx.currentTime + 0.05);
        }

        /* =========================
           TRADUZIONI COMPLETE
        ========================= */

        const traduzioni = {

            it: {
                stats: "Caratteristiche",
                defenseMode: "Modalità Difesa",
                skills: "Abilità",
                forza: "Forza",
                destrezza: "Destrezza",
                vitalita: "Vitalità",
                speciale: "Speciale",
                percezione: "Percezione",
                allerta: "Allerta",
                evasione: "Evasione",
                contrasto: "Contrasto",
                hp: "PS",
                volonta: "Volontà",
                iniziativa: "Iniziativa",
                elusione: "Elusione",
                contrastoTot: "Contrasto Totale",
                difesa: "Difesa",
                difesaSpec: "Difesa Speciale",
                opt1: "Opzione 1 - Esperienza da tavolo",
                opt2: "Opzione 2 - Appassionati videogiochi",
                baseForza: "Forza",
                baseSpeciale: "Speciale",
                commento1: "🎲 Opzione 1:\nDifesa e Difesa Speciale = Vitalità.",
                commento2: "🎮 Opzione 2:\nDifesa = Vitalità.\nDifesa Speciale = Percezione.",
                footer: "Sistema automatico Pokerole"
            },

            en: {
                stats: "Stats",
                defenseMode: "Defense Mode",
                skills: "Skills",
                forza: "Strength",
                destrezza: "Dexterity",
                vitalita: "Vitality",
                speciale: "Special",
                percezione: "Insight",
                allerta: "Alert",
                evasione: "Evasion",
                contrasto: "Clash",
                hp: "HP",
                volonta: "Will",
                iniziativa: "Initiative",
                elusione: "Evasion",
                contrastoTot: "Total Clash",
                difesa: "Defense",
                difesaSpec: "Sp. Defense",
                opt1: "Option 1 - Tabletop Style",
                opt2: "Option 2 - Video Game Style",
                baseForza: "Strength",
                baseSpeciale: "Special",
                commento1: "🎲 Option 1:\nDefense & Sp. Defense = Vitality.",
                commento2: "🎮 Option 2:\nDefense = Vitality.\nSp. Defense = Insight.",
                footer: "Automatic Pokerole System"
            },

            es: {
                stats: "Características",
                defenseMode: "Modo Defensa",
                skills: "Habilidades",
                forza: "Fuerza",
                destrezza: "Destreza",
                vitalita: "Vitalidad",
                speciale: "Especial",
                percezione: "Percepción",
                allerta: "Alerta",
                evasione: "Evasión",
                contrasto: "Choque",
                hp: "PS",
                volonta: "Voluntad",
                iniziativa: "Iniciativa",
                elusione: "Evasión",
                contrastoTot: "Choque Total",
                difesa: "Defensa",
                difesaSpec: "Defensa Especial",
                opt1: "Opción 1 - Estilo Mesa",
                opt2: "Opción 2 - Estilo Videojuego",
                baseForza: "Fuerza",
                baseSpeciale: "Especial",
                commento1: "🎲 Opción 1:\nDefensa y Defensa Especial = Vitalidad.",
                commento2: "🎮 Opción 2:\nDefensa = Vitalidad.\nDefensa Especial = Percepción.",
                footer: "Sistema automático Pokerole"
            },

            pt: {
                stats: "Atributos",
                defenseMode: "Modo Defesa",
                skills: "Habilidades",
                forza: "Força",
                destrezza: "Destreza",
                vitalita: "Vitalidade",
                speciale: "Especial",
                percezione: "Percepção",
                allerta: "Alerta",
                evasione: "Evasão",
                contrasto: "Confronto",
                hp: "PS",
                volonta: "Vontade",
                iniziativa: "Iniciativa",
                elusione: "Evasão",
                contrastoTot: "Confronto Total",
                difesa: "Defesa",
                difesaSpec: "Defesa Especial",
                opt1: "Opção 1 - Estilo Mesa",
                opt2: "Opção 2 - Estilo Videogame",
                baseForza: "Força",
                baseSpeciale: "Especial",
                commento1: "🎲 Opção 1:\nDefesa e Defesa Especial = Vitalidade.",
                commento2: "🎮 Opção 2:\nDefesa = Vitalidade.\nDefesa Especial = Percepção.",
                footer: "Sistema automático Pokerole"
            },

            fr: {
                stats: "Caractéristiques",
                defenseMode: "Mode Défense",
                skills: "Compétences",
                forza: "Force",
                destrezza: "Dextérité",
                vitalita: "Vitalité",
                speciale: "Spécial",
                percezione: "Perception",
                allerta: "Alerte",
                evasione: "Évasion",
                contrasto: "Conflit",
                hp: "PV",
                volonta: "Volonté",
                iniziativa: "Initiative",
                elusione: "Évasion",
                contrastoTot: "Conflit Total",
                difesa: "Défense",
                difesaSpec: "Défense Spéciale",
                opt1: "Option 1 - Style Table",
                opt2: "Option 2 - Style Jeu Vidéo",
                baseForza: "Force",
                baseSpeciale: "Spécial",
                commento1: "🎲 Option 1:\nDéfense et Défense Spéciale = Vitalité.",
                commento2: "🎮 Option 2:\nDéfense = Vitalité.\nDéfense Spéciale = Perception.",
                footer: "Système automatique Pokerole"
            },

            de: {
                stats: "Eigenschaften",
                defenseMode: "Verteidigungsmodus",
                skills: "Fähigkeiten",
                forza: "Stärke",
                destrezza: "Geschick",
                vitalita: "Vitalität",
                speciale: "Spezial",
                percezione: "Wahrnehmung",
                allerta: "Alarm",
                evasione: "Ausweichen",
                contrasto: "Konflikt",
                hp: "LP",
                volonta: "Willenskraft",
                iniziativa: "Initiative",
                elusione: "Ausweichen",
                contrastoTot: "Gesamtkonflikt",
                difesa: "Verteidigung",
                difesaSpec: "Spezial-Verteidigung",
                opt1: "Option 1 - Tischstil",
                opt2: "Option 2 - Videospielstil",
                baseForza: "Stärke",
                baseSpeciale: "Spezial",
                commento1: "🎲 Option 1:\nVerteidigung & Spezial = Vitalität.",
                commento2: "🎮 Option 2:\nVerteidigung = Vitalität.\nSpezial-Verteidigung = Wahrnehmung.",
                footer: "Automatisches Pokerole-System"
            },

            ru: {
                stats: "Характеристики",
                defenseMode: "Режим защиты",
                skills: "Навыки",
                forza: "Сила",
                destrezza: "Ловкость",
                vitalita: "Выносливость",
                speciale: "Спец",
                percezione: "Восприятие",
                allerta: "Бдительность",
                evasione: "Уклонение",
                contrasto: "Столкновение",
                hp: "HP",
                volonta: "Воля",
                iniziativa: "Инициатива",
                elusione: "Уклонение",
                contrastoTot: "Общий урон",
                difesa: "Защита",
                difesaSpec: "Спец. защита",
                opt1: "Вариант 1 - Настольный стиль",
                opt2: "Вариант 2 - Видеоигровой стиль",
                baseForza: "Сила",
                baseSpeciale: "Спец",
                commento1: "🎲 Вариант 1:\nЗащита и Спец. защита = Выносливость.",
                commento2: "🎮 Вариант 2:\nЗащита = Выносливость.\nСпец. защита = Восприятие.",
                footer: "Автоматическая система Pokerole"
            }

        };

        /* ========================= */

        function cambiaLingua() {

            const l = document.getElementById("lingua").value;
            const t = traduzioni[l];

            document.querySelectorAll("h2")[0].textContent = t.stats;
            document.querySelectorAll("h2")[1].textContent = t.defenseMode;
            document.querySelectorAll("h2")[2].textContent = t.skills;

            document.querySelector(".footer").textContent = t.footer;

            document.querySelectorAll(".field")[0].childNodes[0].nodeValue = t.forza + " ";
            document.querySelectorAll(".field")[1].childNodes[0].nodeValue = t.destrezza + " ";
            document.querySelectorAll(".field")[2].childNodes[0].nodeValue = t.vitalita + " ";
            document.querySelectorAll(".field")[3].childNodes[0].nodeValue = t.speciale + " ";
            document.querySelectorAll(".field")[4].childNodes[0].nodeValue = t.percezione + " ";

            document.querySelectorAll(".field")[7].childNodes[0].nodeValue = t.allerta + " ";
            document.querySelectorAll(".field")[8].childNodes[0].nodeValue = t.evasione + " ";
            document.querySelectorAll(".field")[9].childNodes[0].nodeValue = t.contrasto + " ";

            document.getElementById("difesaMode").options[0].text = t.opt1;
            document.getElementById("difesaMode").options[1].text = t.opt2;

            document.getElementById("contrastoBase").options[0].text = t.baseForza;
            document.getElementById("contrastoBase").options[1].text = t.baseSpeciale;

            document.querySelector(".results").children[0].childNodes[0].nodeValue = t.hp + ": ";
            document.querySelector(".results").children[1].childNodes[0].nodeValue = t.volonta + ": ";
            document.querySelector(".results").children[2].childNodes[0].nodeValue = t.iniziativa + ": ";
            document.querySelector(".results").children[3].childNodes[0].nodeValue = t.elusione + ": ";
            document.querySelector(".results").children[4].childNodes[0].nodeValue = t.contrastoTot + ": ";
            document.querySelector(".results").children[5].childNodes[0].nodeValue = t.difesa + ": ";
            document.querySelector(".results").children[6].childNodes[0].nodeValue = t.difesaSpec + ": ";

            calcola();
        }

        function calcola() {

            const l = document.getElementById("lingua").value;
            const t = traduzioni[l];

            let forza = parseInt(document.getElementById("forza").value) || 0;
            let destrezza = parseInt(document.getElementById("destrezza").value) || 0;
            let vitalita = parseInt(document.getElementById("vitalita").value) || 0;
            let speciale = parseInt(document.getElementById("speciale").value) || 0;
            let percezione = parseInt(document.getElementById("percezione").value) || 0;

            let allerta = parseInt(document.getElementById("allerta").value) || 0;
            let evasione = parseInt(document.getElementById("evasione").value) || 0;
            let contrastoSkill = parseInt(document.getElementById("contrastoSkill").value) || 0;

            let baseContrasto = document.getElementById("contrastoBase").value;
            let difesaMode = document.getElementById("difesaMode").value;

            let ps = vitalita + 4;
            let volonta = percezione + 3;
            let iniziativa = destrezza + allerta;
            let elusione = destrezza + evasione;
            let contrastoTotale = (baseContrasto === "forza" ? forza : speciale) + contrastoSkill;

            let difesa = vitalita;
            let difesaSpeciale = (difesaMode === "tavolo") ? vitalita : percezione;

            document.getElementById("ps").textContent = ps;
            document.getElementById("volonta").textContent = volonta;
            document.getElementById("iniziativa").textContent = iniziativa;
            document.getElementById("elusione").textContent = elusione;
            document.getElementById("contrastoTotale").textContent = contrastoTotale;
            document.getElementById("difesa").textContent = difesa;
            document.getElementById("difesaSpeciale").textContent = difesaSpeciale;

            document.getElementById("difesaCommento").textContent =
                difesaMode === "tavolo" ? t.commento1 : t.commento2;

            beep();
        }

        function exportCSV() {

            const dati = {
                forza: forza.value,
                destrezza: destrezza.value,
                vitalita: vitalita.value,
                speciale: speciale.value,
                percezione: percezione.value,
                allerta: allerta.value,
                evasione: evasione.value,
                contrastoSkill: contrastoSkill.value,
                contrastoBase: contrastoBase.value,
                difesaMode: difesaMode.value,
                lingua: lingua.value
            };

            let csv = "chiave,valore\n";
            for (let key in dati) {
                csv += key + "," + dati[key] + "\n";
            }

            const blob = new Blob([csv], { type: "text/csv" });
            const url = URL.createObjectURL(blob);

            const a = document.createElement("a");
            a.href = url;
            a.download = "pokerole_character.csv";
            a.click();

            URL.revokeObjectURL(url);
        }

        function importCSV(event) {

            const file = event.target.files[0];
            if (!file) return;

            const reader = new FileReader();

            reader.onload = function (e) {

                const righe = e.target.result.split("\n");

                righe.forEach(riga => {
                    const [chiave, valore] = riga.split(",");

                    if (document.getElementById(chiave)) {
                        document.getElementById(chiave).value = valore;
                    }
                });

                cambiaLingua();
                calcola();
            };

            reader.readAsText(file);
        }

        calcola();
        if ('serviceWorker' in navigator) {
            navigator.serviceWorker.register('sw.js');
        }
    </script>

</body>

</html>