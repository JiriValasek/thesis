# Diplomová práce
---

Repozitář vytvořený za účelem verzování a koordinace.

Plánovaný termín odevzdání: 6.5.2024 (rezerva 1W)

[Online verze pro prohlédnutí](master_thesis.rst)


## Žurnál

Žurnál prováděné činnosti pro zpětnou dohledatelnost, evidenci a jednodušší korekci směřování práce.

**Formát:**
> &lt;Datum&gt; [ &lt;odpočet&gt;, &lt;počet_normostran&gt;/60 ] &lt;strávený čas&gt; 
> - &lt;bod_činnosti&gt;


### 9.3.2024 [ D-57, 2/60] - 0h
- NIL

### 8.3.2024 [ D-58, 2/60] - 0h
- NIL

### 7.3.2024 [ D-59, 2/60] - 3h
- Dokončení [přednášky][2]
- Dopsání žurnálu

### 6.3.2024 [ D-60, 2/60] - 3h
- Dokončení [přednášky][1], započetí rychlé rekapitulace [přednášky 10 | RNN z cs231n][2], pro lepší porozomění architektur za generátory i detektory deepfake.
- Zakládání a nastavování repozitáře.

- Během předášky jsem zjistil potřebu osvěžení si:
  - [Evidence Lower Bound](https://en.wikipedia.org/wiki/Evidence_lower_bound)
  - [Variational Bayesian methods](https://en.wikipedia.org/wiki/Variational_Bayesian_methods)

### 5.3.2024 [ D-61, 2/60 ] - 3h
- Na základě studování materiálů jsem zjistil potřebu prohloubit znalosti v oblasti UI používané ke generování obrázků. Dle svých zkušeností jsem nakonec přešel na [přednášku 13 | generativní modely z Stanfordského cs231n][1], kde vysvětlují dobře stravitelnou formou a zároveň mají vše pěkně referencované. 

- Během předášky jsem zjistil potřebu osvěžení si statistiky:
  - [Likelihood](https://en.wikipedia.org/wiki/Likelihood_function)
  - [Kullback–Leibler divergence](https://en.wikipedia.org/wiki/Kullback%E2%80%93Leibler_divergence)
  - [Expectation-Maximization](https://en.wikipedia.org/wiki/Expectation%E2%80%93maximization_algorithm)
  - [Maximum likelihood estimation](https://en.wikipedia.org/wiki/Maximum_likelihood_estimation)
  
- Začal jsem tento dokument zpětně k začátku týdne, pro účely:
  - koordinace
  - získání lepšího odhadu času
  - jednoduššího zpětného dohledání zdrojů  

### 4.3.2024 - 4h
- Na základě čtení způsobů generace deep fakes z [Masood - Deepfakes generation and Detection](https://link.springer.com/article/10.1007/s10489-022-03766-z) jsem se rozhodl prohloubit si znalosti v oblasti používaných UI pro vytváření deepfakes - VAE, GAN. Začal jsem:
  - [Gretton - NIPS 2016 Workshop on Adversarial Learning](https://www.gatsby.ucl.ac.uk/~gretton/papers/testing_workshop.pdf)
  - [Baeldung - VAE vs GAN](https://www.baeldung.com/cs/vae-vs-gan-image-generation)
  - [Lecture 13 | VAE - COMS4995 Columbia Uni](https://www.cs.columbia.edu/~zemel/Class/Nndl-2021/files/lec13.pdf)
  - [TowardsDataScience - GAN](https://towardsdatascience.com/understanding-generative-adversarial-networks-gans-cd6e4651a29)
  - [TowardsDataScienc - VAE](https://towardsdatascience.com/understanding-variational-autoencoders-vaes-f70510919f73?gi=84edd2db419d)

- Během studování jsem zjistil potřebu prohlobení znalostí z matematiky:
  - [Variational Bayesian methods](https://en.wikipedia.org/wiki/Variational_Bayesian_methods)
  - [Inverse transform sampling](https://en.wikipedia.org/wiki/Inverse_transform_sampling)
  - [Rejection sampling](https://en.wikipedia.org/wiki/Rejection_sampling)
  - [Metropolis–Hastings algorithm](https://en.wikipedia.org/wiki/Metropolis%E2%80%93Hastings_algorithm)

- Tvorba obrázků do DP (Face-swap)
  - Vygeneroval jsem fotky postav pomocí [MidJourney](https://www.midjourney.com/)
  - Na fotkách jsem udělal vzájemný face-swap pomocí [faceswapper.ai](https://faceswapper.ai)


### 3.3.2024 - 4h

- Vyhledávání nejaktuálnějších článků se záměrem najít co nejaktuálnější datasety, modely pro generování i detekci.

- Nalezené články:

| Datum přijetí | HREF | Poznámky |
|---|---|---|
| v3 z 15.2.2024 | [A Review of Deep Learning-based Approaches for Deepfake Content Detection](https://arxiv.org/abs/2202.06095) | Transformers, 12 datasetů |
| 16.12.2023 | [A Contemporary Survey on Deepfake Detection: Datasets, Algorithms, and Challenges](https://www.mdpi.com/2079-9292/13/3/585) | Schémata modelů na detekci deepfakes |
| 26.10.2023 | [A Comprehensive Review of DeepFake Detection Using Advanced Machine Learning and Fusion Methods](https://www.mdpi.com/2079-9292/13/1/95#table_body_display_electronics-13-00095-t002) | Schémata modelů na generování |
| 19.9.2023 | [Deepfake Attacks: Generation, Detection, Datasets, Challenges, and Research Directions](https://www.mdpi.com/2073-431X/12/10/216) | Detection clues, 12 datasetů |
| 15.6.2023 | [A survey on deepfake video detection datasets](https://www.researchgate.net/publication/374142887_A_survey_on_deepfake_video_detection_datasets) | 13 datasetů, poslední z Jul 21 |
| 21.5.2023 | [Deepfakes: evolution and trends](https://link.springer.com/article/10.1007/s00500-023-08605-y) | Motivace za vývojem deepfake, použití, trendy |
| 11.8.2022 | [Hybrid Transformer Network for Deepfake Detection](https://arxiv.org/abs/2208.05820) | Detekce pomocí transformeru |
| 2.2.2022 | [A literature review and perspectives in deepfakes: generation, detection, and applications ](https://link.springer.com/article/10.1007/s13735-022-00241-w) | hrozby, kategorie Entire Image Synthesis |

## Poznánky k praktické části

### GCP/Vertex AI
- [YT - List (asi) všech google tutoriálů](https://www.youtube.com/playlist?list=PLIivdWyY5sqJdmVMjLI8iCul14XkTRosn)
- [YT - Custom models on Vertex AI](https://www.youtube.com/watch?v=VRQXIiNLdAk)
- [GGL - Custom models on Vertex AI](https://cloud.google.com/vertex-ai/docs/start/training-guide)
- [Medium - Keras on GCP](https://medium.com/@natu.neeraj/training-a-keras-model-on-google-cloud-ml-cb831341c196)

## Vývoj
1. Nainstalujte [pandoc](https://github.com/jgm/pandoc)
2. Přidejte cestu k pandoc do PATH v proměnných prostředí
3. Do `.git/config` přidejte:
   - Git hooks: přidejte hookspath pod `[core]`
      ```ini
        [core]
          hookspath = .githooks/
      ```
   - Konfiguraci `git wdiff` pro docx
      ```ini
      [diff "pandoc"]
        textconv=pandoc --to=markdown
        prompt = false
      [alias]
        wdiff = diff --word-diff=color --unified=1
      ```
- Změny ve wordu zobrazíte přes `git wdiff`

## Notes & Links
- [Markdown CheatSheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [Tracking word changes in git](https://olickel.com/tracking-word-documents-with-git)

[1]:https://www.youtube.com/watch?v=5WoItGTWV54
[2]:https://www.youtube.com/watch?v=6niqTuYFZLQ