# 🎮 Programació en Català – Portal Arcade Educatiu

![Programació en Català](https://img.shields.io/badge/Llengua-Catal%C3%A0-blue)
![Autor](https://img.shields.io/badge/Creat%20per-Bernat%20Marquilles-emerald)
![Llicència](https://img.shields.io/badge/Llic%C3%A8ncia-MIT-orange)

Benvinguts a **Programació en Català**, una plataforma web interactiva d'aprenentatge algorítmic dissenyada especialment per a infants i principiants. A través d'una interfície basada en la programació per blocs (inspirada en *Code.org* i *Minecraft Hour of Code*), els jugadors resolen reptes de lògica, bucles i condicionals mentre guien diferents vehicles i personatges.

**Creat per:** Bernat Marquilles  
**GitHub:** [github.com/bmarquil](https://github.com/bmarquil)

---

## 🌟 Característiques Principals

- **4 Jocs Temàtics 100% Únics**: Amb una progressió pedagògica que va des de l'orientació espacial bàsica fins a l'ús de bucles niats i condicions lògiques.
- **Interfície Intuïtiva per Blocs (Drag & Drop)**: Permet arrossegar, connectar, reordenar i esborrar blocs de codi fàcilment (a la caixa d'eines o a la paperera).
- **Selector de Gir Unificat**: Un sol bloc de gir amb menú desplegable per a triar direcció (`Dreta ↻` / `Esquerra ↺`).
- **Nivells Garantits 100% Solubles**: Implementació d'un cercador de camins *BFS (Breadth-First Search)* per validar que tot mapa té una solució lògica.
- **Sons i Efectes Synth (Web Audio API)**: Efectes de so sintetitzats en temps real sense dependències de fitxers externs.
- **Previsualitzador de Codi JavaScript**: L'infant pot veure en qualsevol moment l'equivalent en codi text real (`JS`) de la seqüència de blocs que ha construït.
- **Detecció de Progrés en Temps Real**: Menú inicial amb percentatges de superació per a cada un dels jocs.

---

## 🚀 Els 4 Jocs Inclosos

| Joc | Icona | Descripció | Nivells | Tamany del Tauler |
| :--- | :---: | :--- | :---: | :---: |
| **CAFArobot** | 🤖 | Dirigeix el robot de circuit a través de laberints de proves i zones de construcció. | **20** | 6x6 ➔ 10x10 |
| **ASTRO-bot** | 🚀 | Explora planetes alienígenes amb el Rover Espacial recollint cristalls galàctics. | **20** | 6x6 ➔ 10x10 |
| **TRACTORcode** | 🚜 | Mena el tractor agrícola pels camps esquivant valles i recollint la collita. | **10** | 6x6 ➔ 10x10 |
| **SUBmaríCODE** | 🌊 | Submergeix el submarí fins a fossetes submarines 12x12 i esquiva bombes marítimes. | **20** | 6x6 ➔ 12x12 |

---

## 🛠️ Tecnologies Utilitzades

- **HTML5 & Canvas 2D**: Renderitzat gràfic dinàmic dels mapes, grilles, vehicles i obstacles.
- **Tailwind CSS**: Disseny d'interfície web modèrn, adaptatiu i amb temes fosc/neó (*Cyberpunk/Space*).
- **JavaScript pur (ES6+)**: Lògica d'execució d'algorismes (AST, generadors `function*`, iteradors dinàmics).
- **Web Audio API**: Generació de sons i efectes d'àudio sintetitzats.
- **Font Awesome 6**: Iconografia vectorial.

---

## 💻 Com Executar el Projecte

Aquest projecte està dissenyat com una **aplicació d'un sol fitxer** (`Single-File Web Application`). No requereix instal·lar cap servidor ni dependències de Node.js.

1. Descarrega o clona aquest repositori:
   ```bash
   git clone https://github.com/bmarquil/programacio-en-catala.git
   ```
2. Obre el fitxer `index.html` directament a qualsevol navegador web modern (Chrome, Firefox, Safari, Edge).

---

## 📜 Llicència

Aquest projecte està sota la llicència **MIT**. Et convidem a utilitzar-lo, compartir-lo i adaptar-lo per a ús educatiu en escoles, tallers de robòtica o a casa!

---
*Creat amb ❤️ per **Bernat Marquilles** ([@bmarquil](https://github.com/bmarquil))*