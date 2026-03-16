# Fables-DTR: A Corpus of Fables Annotated for Discourse and Temporal Relations

## 🗂 Overview

**Fables-DTR** is a multilingual parallel corpus of 45 Aesop's fables annotated for **discourse** and **temporal relations**. The dataset is provided in **UIMA XML 1.1 format**, compatible with the INCEpTION annotation platform, and is designed to support research in:

- Discourse coherence
- Temporal sequencing
- Narrative structure
- Cross-linguistic semantics

This **repository** includes the texts in:
- 🇵🇹 European Portuguese (included annotations)
- 🇵🇱 Polish
- 🇺🇸 English

---

## 🧠 Annotation Scheme
The annotation scheme harmonizes ISO standards:

- **ISO 24617-1**: Time and events (SemAF-Time)
- **ISO 24617-8**: Discourse relations (SemAF-DR-Core)


### 📌 Entity Structures

- **Events**: Annotated with:
  - `tense`: `past`, `present`, `future`
  - `aspectual type`: `state`, `process`, `transition`
  - `polarity`: `positive`, `negative`
- **Situations**: Represent discourse relation arguments (e.g., cause, goal, result)
- **Signals**: Lexical markers (e.g., *because*, *although*, *when*) that explicitly indicate discourse relations

### 🔗 Link Structures

- **Discourse Links**: Capture semantic relations such as:
  - `Cause`, `Purpose`, `Concession`, `Expansion`, `Elaboration`, `Asynchrony`, `Synchrony`, etc.
- **Temporal Links**: Encode temporal relations:
  - `before`, `after`, `simultaneous`, `identity`
- **Signal Links**: Connect signals to the arguments they introduce

---

## 📄 Format

- **Format**: `UIMA XML 1.1`
- **Annotation Tool**: INCEpTION
- **Annotation Layers**:
  - `event`, `situation`, `signal` (entities)
  - `discourseLink`, `temporalLink`, `signalLink` (relations)

---

## 🔍 Use Cases

This dataset is suitable for:

- Temporal relation extraction
- Narrative structure analysis
- Cross-linguistic studies of coherence and aspect

---

## 📚 Citation

If you use this dataset, please cite the corresponding publication (to be updated upon acceptance).

---

## 📄 License

Licensed under the Apache License, Version 2.0

---
