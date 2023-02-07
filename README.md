# About Dataset
Welcome to the Traditional Indian Texts dataset! This dataset is a collection of some of the most seminal works in Indian history, starting with the Charak Samhita. We plan to add more texts to this collection soon, covering a wide range of topics and perspectives like Chanakya Neeti.  
## 1. Charak-Samhita
Welcome to the Charak Samhita dataset! Charak Samhita is an ancient Indian Ayurvedic text, considered to be one of the foundational texts of this traditional medical system. Charak Samhita  covers various aspects of Ayurvedic medicine such as anatomy, physiology, pathology, and treatment. The data has been sourced from Wisdomlib has been carefully curated to ensure accuracy and authenticity. By providing access to this valuable resource, we hope to facilitate the preservation and advancement of Ayurvedic knowledge..

### About Data collection methodology

The data has been web-scraped from the Wisdomlib using the Python library BeautifulSoup.

### Description of the data
```

Root ayurveda/
  -Sub charak-samhita/
    -Sub 1.Sutrasthana (Sutra Sthana) — General Principles
        -chapters
    -Sub 2.Nidanasthana (Nidana Sthana) — Section on Pathology
        -chapters
    -Sub 3.Vimanasthana (Vimana Sthana) — Section on Measure
        -chapters
    -Sub 4.Sharirasthana (Sharira Sthana) — Section on Human Embodiment
        -chapters
    -Sub 5.Indriyasthana (Indriya Sthana) — Section on Sensorial Prognosis
        -chapters
    -Sub 6.Cikitsasthana (Cikitsa Sthana) — Section on Therapeutics
        -chapters
    -Sub 7.Kalpasthana (Kalpa Sthana) — Section on Pharmaceutics
        -chapters
    -Sub 8.Siddhisthana (Siddhi Sthana) — Section on Successful Treatment
        -chapters
```

### Dataset formats

format of data is .json

```
[
    {
        "verse_id"="1";
        "text"="We shall now expound the chapter entitled";
    }
]
```