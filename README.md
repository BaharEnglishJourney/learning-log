# Learning Log

A weekly record of my path from English teaching (TEFL) into linguistics and language technology: what I study, what I build, and what I still don't understand.

**Started:** December 2026

**Currently reading:**
- George Yule, *The Study of Language* (Dec 2026 – Mar 2027)
- Dan Jurafsky & James H. Martin, *Speech and Language Processing* (from Apr 2027)

**Also working on:** Python, corpus linguistics with AntConc, Italian, IELTS Academic

---

## How this log works

- One entry per week, newest at the top.
- Each entry has five parts: date, what I studied, what I built, questions I still have, and Yule bridge notes.
- **Yule bridge notes:** after each Yule chapter, 2–3 lines on *how a computer would deal with this*. They link linguistics to NLP.

---

## Entries

<!--
Copy this template for each new week and paste it just below "## Entries",
above the previous week's entry.

### Week N · DD – DD Month YYYY

**What I studied**
-

**What I built**
-

**Questions I still have**
-

**Yule bridge notes (how a computer would deal with this)**
-
-->

### Week 1 · 1 – 4 Dec 2026 (short week)

**What I studied**
- **Linguistics:** Yule, *The Study of Language*: the preface and ch. 1 *The origins of language*
- **Python:** set up [Python + VS Code]; *Python for Everybody* ch. 1 (Why should you learn to write programs?)
- **Italian:** *Nuovo Espresso 1*, 20 minutes a day
- **English:** general English practice
- **Daniel Kahneman,** *Thinking, Fast and Slow*, ch. 1–2

**What I built**
- HTML study pages for *Nuovo Espresso 1*, units 1–3
  [Unit 1](lesson-01-primi-contatti.html) ·
  [Unit 2](lesson-02-io-e-gli-altri.html) ·
  [Unit 3](lesson-03-buon-appetito.html)
- This GitHub account and the `learning-log` repository

**Questions I still have**
- If a model learns grammar from data alone, does that **weaken** the innateness hypothesis, or not? (The model needs far more data than a child.)
- Can a model that has never *heard* language really understand **intonation**, such as sarcasm or questions without question words? (→ Phonetics and phonology chapters)


**Yule bridge notes (how a computer would deal with this)**
- *The origins of language:*
**Topic:** How did humans get language? And what does that tell us about how machines "get" language?


## 1. Chapter summary

Nobody knows for sure how language began. Spoken language probably developed between **100,000 and 50,000 years ago**, and writing only about **5,000 years ago**. Speech leaves no fossils, so all theories are speculation. Yule describes **seven sources**:

| Source | Main idea | Main problem |
|---|---|---|
| **Divine** | Language was a gift from God or the gods | Isolated children develop no language (Akbar, Victor, Genie) |
| **Natural sound** | First words copied natural sounds ("bow-wow") or emotional cries ("pooh-pooh") | Most things make no sound; cries are made on in-breaths |
| **Musical** | Melody and intonation came before words (Darwin) | Birds and whales sing too, but they don't talk |
| **Social interaction** | Sounds used to coordinate group work ("yo-he-ho") | Apes live in groups but never developed speech |
| **Physical adaptation** | Teeth, lips, tongue, a lower larynx and a longer pharynx made speech possible | A body that *can* speak doesn't guarantee language |
| **Tool-making** | Combining rocks to make tools ≈ combining sounds to make messages; both use the left hemisphere | Hard to prove the link |
| **Genetic** | Humans are born with a language capacity (innateness hypothesis) | Says *that* we have it, not *how* it appeared |

---

## 2. Linguistics → NLP connections

### 2.1 From "natural sounds" to "computers"
The speculation about how language began has slowly shifted. Early explanations were based on **natural and physical sources of sound**, such as humans imitating nature. Later explanations compare the brain to a **computer** that is *programmed* or *pre-wired* to learn language. But there is a key difference. A computer is programmed by humans, while the human "program" is believed to come from **biology and genetics**.

### 2.2 The nature vs. nurture debate in NLP
NLP has its own version of the **nature vs. nurture** debate:

- **Nurture (learning from data):** modern language models start with almost no knowledge of language. They learn everything from huge amounts of text.
- **Nature (built-in structure):** older rule-based systems were given grammar rules from the start. This is a bit like the **innateness hypothesis** and Chomsky's **Universal Grammar**.

Even data-driven models are not completely "blank." Their architecture has built-in tendencies (called *inductive biases*). But these are general-purpose. They are not language-specific rules like Universal Grammar.

### 2.3 FOXP2: a warning about the "one gene / one neuron" idea
When FOXP2 was discovered, it was called "**the language gene**." Later research showed it is one gene among many. It mostly affects control of mouth and face movements, and it also exists in mice and songbirds.

NLP has a similar trap. Researchers sometimes find a single "neuron" or feature inside a language model that seems responsible for one behavior. Usually that behavior is actually **spread across many parts** of the model. Language in a model depends on many parts, just as language in humans depends on many genes.

