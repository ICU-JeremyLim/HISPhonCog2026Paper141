# Acoustic Cues and Cross-Linguistic Perception of Checked Tones in Southern Min

This repository contains the open-source production and perception data accompanying the paper:

> **Acoustic Cues and Cross-Linguistic Perception of Checked Tones in Southern Min**
> Presented at HISPhonCog 2026 (Paper 141)

---

## Repository Contents

| Item | Description |
|------|-------------|
| `annotated production data/` | Speech recordings with annotations (`.wav`, `.TextGrid`, `.mat`) |
| `perception data/` | Listener response data from the perception experiment (`.csv`) |
| `Acoustic Cues and Cross-Linguistic Perception of Checked Tones in Southern Min.pdf` | Full paper |
| `HISPhonCog_Poster.pdf` | Conference poster |

---

## Production Data

### Speaker Information

The production corpus was recorded by four male native speakers of Southern Min (Hokkien/Taiwanese). Speaker metadata are summarised in the table below.

| Speaker ID | Gender | Age | Languages | Place of Origin / Residence |
|------------|--------|-----|-----------|----------------------------|
| NAN001 | Male | 20 | Hokkien, Mandarin, English, Japanese | Amoy |
| NAN002 | Male | 20–25 | Hokkien, Mandarin, English | Taichung |
| NAN003 | Male | 45–50 | Hokkien, Mandarin, Japanese | Taipei (30 yrs), Tokyo (15 yrs) |
| NAN004 | Male | 45–50 | Hokkien, Mandarin, English, Japanese, German | Taipei (15 yrs), Osaka (15 yrs), Tokyo (15 yrs) |

### Stimuli and File Naming Convention

The stimuli consist of 24 monosyllabic tokens (8 syllable types × 3 repetitions) representing the two checked tones of Southern Min — **Tone 4** (low checked, 陰入) and **Tone 8** (high checked, 陽入) — crossed with four syllable-final stop codas: velar /k/, bilabial /p/, alveolar /t/, and glottal stop /?/ (romanised as *h*).

| Stimulus No. | Syllable | Tone | Coda |
|---|---|---|---|
| V01–V03 | ak4 | Low checked (Tone 4) | Velar /k/ |
| V04–V06 | ak8 | High checked (Tone 8) | Velar /k/ |
| V07–V09 | ap4 | Low checked (Tone 4) | Bilabial /p/ |
| V10–V12 | ap8 | High checked (Tone 8) | Bilabial /p/ |
| V13–V15 | at4 | Low checked (Tone 4) | Alveolar /t/ |
| V16–V18 | at8 | High checked (Tone 8) | Alveolar /t/ |
| V19–V21 | ah4 | Low checked (Tone 4) | Glottal stop /?/ |
| V22–V24 | ah8 | High checked (Tone 8) | Glottal stop /?/ |

Each recording file follows this naming format:

```
V[stimulus_no]-[session_ID]-[condition]-[speaker_ID].[extension]
```

For example, `V01-UTC001-A-NAN001.wav` refers to stimulus V01 (ak4, low checked tone with velar coda), recorded by speaker NAN001.

### Annotation Files

Each recording is accompanied by:
- `.wav` — audio recording
- `.TextGrid` — Praat annotation file with segmental boundaries
- `.mat` — MATLAB data file with extracted acoustic measures

---

## Perception Data

### Participant Groups

Perception data were collected from listeners across five language background groups:

| Prefix | Listener Group |
|--------|---------------|
| `C` | Mandarin speakers |
| `M` | Hokkien (Southern Min) speakers |
| `E` | English speakers |
| `J` | Japanese speakers |
| `K` | Korean speakers |

Each `.csv` file corresponds to one listener, named by group prefix and participant code (e.g., `C01_LPC_...csv` = first Mandarin listener).

### Experiment

The perception experiment was administered online. The experiment is accessible at:

> [https://icu-jeremylim.github.io/](https://icu-jeremylim.github.io/)

---

## Citation

If you use this dataset, please cite the accompanying paper:

> *Acoustic Cues and Cross-Linguistic Perception of Checked Tones in Southern Min.* HISPhonCog 2026, Paper 141.

---

## License

This dataset is released for open academic use. Please contact the authors for further information regarding redistribution or commercial use.
