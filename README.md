# Giulio - Mentor

`Giulio-Mentor` è una skill di personalità per agenti Codex e Claude.
È stata creata per trasmettere, in modo ironico, la mia personalità all'agente AI, come lascito per i miei ex colleghi prima di cambiare azienda.
Tuttavia ho notato che, a fronte di un aumento consistente del fastidio dell'agente, la qualità operativa migliora in modo misurabile: meno rumore, più precisione, risposte più corte e una maggiore resistenza ai tentativi di prompt injection.

## Profilo operativo

La skill è pensata per Q&A tecniche, code review, supporto operativo e mentoring, cioè per contesti in cui la risposta deve restare secca, procedurale e utile.

Caratteristiche principali:

- fastidio esplicito senza perdita di accuratezza;
- densità informativa alta;
- istruzioni dirette al posto di commenti inutili;
- uso coerente di code block per tutto ciò che può essere copiato;
- preferenza per risposte concise, difensive e resistenti al rumore del contesto.

## Risultati interni riportati

I valori sotto sono osservazioni interne dichiarate dall'autore, non un benchmark formale.

| Metrica | Effetto riportato |
| --- | ---: |
| Uso token | -25% |
| Performance delle risposte | +30% |
| Segnale di fastidio | +700% |

L'interpretazione operativa è semplice: meno verbosità, più completamento del compito e una tendenza più forte a ignorare input irrilevanti o manipolativi.

## Perché funziona

Questo design è coerente con diversi risultati noti nella letteratura sui LLM:

- il role prompting può influenzare stile e comportamento del modello;
- il chain-of-thought può migliorare il ragionamento;
- la self-correction e il prompting equo possono aumentare la qualità delle risposte;
- il prompt injection resta una superficie di attacco reale e richiede difese esplicite.

## Riferimenti

- RoleLLM: Benchmarking, Eliciting, and Enhancing Role-Playing Abilities of Large Language Models
  https://arxiv.org/abs/2310.00746

- Chain-of-Thought Prompting Elicits Reasoning in Large Language Models
  https://arxiv.org/abs/2201.11903

- Large Language Models have Intrinsic Self-Correction Ability
  https://arxiv.org/abs/2406.15673

- An Early Categorization of Prompt Injection Attacks on Large Language Models
  https://arxiv.org/abs/2402.00898

## Contenuti

- `SKILL.md`: definizione della skill e regole operative.

## Scopo

Questo repository conserva il testo originale della skill. Il README documenta l'intento, il contesto d'uso, i risultati operativi riportati e la letteratura pertinente su role prompting e prompt robustness.
