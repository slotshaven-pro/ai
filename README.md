# AI-assisteret T0DO-liste

Dette er en skabelon for nybegyndere, der ønsker at lære, hvordan man bruger GitHub Copilot til at udvikle en Python-applikation.

I skabelonen tages udgangspunkt i en TODO-liste app med tkinter og ttkbootstrap.

## Om projektet

**Beskrivelse:** En enkel, men funktionel opgaveliste-applikation bygget med Python, tkinter og ttkbootstrap. Projektet demonstrerer, hvordan man strukturerer Copilot-instruktioner for at få mest muligt ud af AI-assisteret kodning.

**Målgruppe:** Begynderprogrammører, der gerne vil lære god praksis inden for AI-assisteret udvikling.

---

## Forudsætninger

- Python 3.8 eller nyere
- Git
- VS Code
- GitHub Copilot Chat-udvidelse installeret

---

## Projektstruktur

```bash
pro/ai/
├── .github/
│   ├── copilot-instructions.md      # Copilot-konfiguration
│   ├── python.instructions.md       # Python-kodestandarder
│   └── example-prompt-file.prompt.md # Prompt-skabelon
├── src/
│   ├── main.py                      # Indgangspunkt for appen
│   ├── models/                      # Datamodeller
│   └── views/                       # GUI-komponenter
├── tests/                           # Enhedstests
├── docs/                            # Dokumentation
├── AGENTS.md                        # Agent-instruktioner
├── copilot.log.md                   # Interaktionslog
└── README.md                        # Dette fil
```

---

## Hvordan bruger man Copilot i dette projekt?

### 1. Forstå instruktionerne

Læs disse filer før du starter:

- **`copilot-instructions.md`** - Generelle retningslinjer for projektet
- **`python.instructions.md`** - Python og GUI-kodestandarder
- **`AGENTS.md`** - Hvordan forskellige AI-agenter fungerer

### 2. Stil gode spørgsmål

Brug skabelonen i `example-prompt-file.prompt.md`:

```markdown
**Kontekst:** Jeg bygger indstillingsdialogen for to-do appen

**Nuværende tilstand:** Jeg har en hovedvindue med opgavelisten

**Mål:** Lav en indstillingsdialog til temavalg

**Begrænsninger:** Skal være modal og bruge ttkbootstrap

**Spørgsmål:** Hvordan laves en modal dialog i ttkbootstrap?
```

### 3. Få h$jælp fra Copilot

Copilot kan hjælpe med:

- ✅ At forklare, hvordan kode fungerer
- ✅ At generere enhedstests
- ✅ At foreslå fejlrettelser
- ✅ At skrive nye funktioner
- ✅ At gennemgå din kode
- ✅ At skrive dokumentation

Copilot kan **ikke**:

- ❌ Køre kode direkte
- ❌ Få adgang til eksterne databaser
- ❌ Træffe permanente designbeslutninger

### 4. Følg kodestandarderne

Alt kode skal følge reglerne i `python.instructions.md`. Copilot vil automatisk foreslå kode, der følger disse standards.

---

## Vigtige filer

| Fil | Formål |
|-----|--------|
| `copilot-instructions.md` | Konfigurer Copilot til dit projekt |
| `python.instructions.md` | Definer Python-kodestandarder |
| `AGENTS.md` | Beskriv, hvordan AI-agenter skal fungere |
| `example-prompt-file.prompt.md` | Lær at skrive gode prompts |
| `copilot.log.md` | Log af alle Copilot-interaktioner |

---

## Tips til nybegyndere

1. **Start med planlægning:** Brug Copilot til at planlægge features før du koder
2. **Stil klare spørgsmål:** Jo mere specifik du er, jo bedre svar får du
3. **Læs de genererede koder:** Lær fra hvad Copilot foreslår
4. **Test alt:** Copilot hjælper, men du skal stadig teste din kode
5. **Dokumenter dine beslutninger:** Skriv *hvorfor*, ikke bare *hvad*

---

## Lær mere

- [GitHub Copilot dokumentation](https://docs.github.com/en/copilot)
- [Python bedste praksis](https://pep8.org/)
- [tkinter tutorial](https://docs.python.org/3/library/tkinter.html)
- [ttkbootstrap dokumentation](https://ttkbootstrap.readthedocs.io/)

---
