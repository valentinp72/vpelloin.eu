+++
title = "Valentin Pelloin"
aliases = [
    "/about"
]
date = "2020-09-06"
lastmod = "2024-07-22"
+++

## About Me

{{< figure class="avatar no-photoswipe" src="/avatar-mono.jpg" nolink="yes" alt="avatar" >}}

I'm a researcher working on spoken and natural language processing issues.
Interested in computer science and artificial intelligence, I defended [my PhD thesis]({{< ref "#thesis2024" >}} "PhD thesis") on "Spoken language understanding in human-computer dialogue systems in the era of pretrained models" in Le Mans University (France).

<!-- ## Research Interest -->

I am currently working at [INA](https://www.ina.fr/), the French National Audiovisual Institute, as a researcher on speech issues related to audiovisual contents. My current main research interest are Automatic Speech Recognition (ASR), speech and speaker recognition, and end-to-end information extraction.
<!-- I am currently doing my PhD at LIUM, within the [AISSPER](https://aissper.univ-avignon.fr) (Artificial Intelligence for Semantically controlled SPEech UndeRstanding) ANR project. The goal of the [AISSPER](https://aissper.univ-avignon.fr) project is to offer new algorithms in order to solve spoken language understanding tasks. [AISSPER](https://aissper.univ-avignon.fr) aims at building end-to-end artificial intelligence systems capable of extracting semantic concepts directly from the speech signal. -->

## Publications

<!-- https://flamingtempura.github.io/bibtex-tidy/ -->

<div>
<ol class="publications">

#### 2026

{{< publication
	id="lrec2026_a"
	title="Data Selection Effects on Self-Supervised Learning of Audio Representations for French Audiovisual Broadcasts"
	authors="Valentin Pelloin, Lina Bekkali, Reda Dehak, David Doukhan"
	year="2026"
	where="Fifteenth International Conference on Language Resources and Evaluation (LREC 2026), Palma (Mallorca), Spain"
    pdf="http://www.lrec-conf.org/proceedings/lrec2026/pdf/2026.lrec2026-1.802.pdf"
	doi="10.63317/4kdn23nttrh4"
	hal="https://hal.science/hal-05632822"
>}}
@inproceedings{pelloin-etal-2026-data,
  title = {Data Selection Effects on Self-Supervised Learning of Audio Representations for French Audiovisual Broadcasts},
  author = {Pelloin, Valentin and Bekkali, Lina and Dehak, Reda and Doukhan, David},
  booktitle = {Proceedings of the Fifteenth Language Resources and Evaluation Conference (LREC 2026)},
  month = {May},
  year = {2026},
  pages = {10221--10232},
  address = {Palma, Mallorca, Spain},
  publisher = {European Language Resources Association (ELRA)},
  editor = {Piperidis, Stelios and Bel, Núria and van den Heuvel, Henk and Ide, Nancy and Krek, Simon and Toral, Antonio},
  doi = {10.63317/4kdn23nttrh4},
  abstract = {Audio and speech self-supervised encoder models are now widely used for a lot of different tasks. Many of these models are often trained on clean segmented speech content such as LibriSpeech. In this paper, we look into how the pretraining datasets of such SSL (Self-Supervised Learning) models impact their downstream results. We build a large pretraining corpus of highly diverse TV and Radio broadcast audio content, which we describe with automatic tools. We use these annotations to build smaller subsets, which we use to train audio SSL models. Then, we evaluate the models on multiple downstream tasks such as automatic speech recognition, voice activity and music detection, or speaker recognition. The results show the potential of pretraining SSL models on diverse audio content without restricting it to speech. We also perform a membership inference attack to evaluate the encoder ability to memorize their training datasets, which highlight the importance of data deduplication. This unified training could bridge speech and music machine learning communities.}
  }
{{< /publication >}}

{{< publication
	id="lrec2026_b"
	title="Pantagruel: Unified Self-Supervised Encoders for French Text and Speech"
	authors="Phuong-Hang Le, Valentin Pelloin, Arnault Chatelain, Maryem Bouziane, Mohammed Ghennai, Qianwen Guan, Kirill Milintsevich, Salima Mdhaffar, Aidan Mannion, Nils Defauw, Shuyue Gu, Alexandre Audibert, Marco Dinarelli, Yannick Estève, Lorraine Goeuriot, Steffen Lalande, Nicolas Hervé, Maximin Coavoux, François Portet, Étienne Ollion, Marie Candito, Maxime Peyrard, Solange Rossato, Benjamin Lecouteux, Aurélie Nardy, Gilles Sérasset, Vincent Segonne, Solène Evain, Diandra Fabre, Didier Schwab"
	year="2026"
	where="Fifteenth International Conference on Language Resources and Evaluation (LREC 2026), Palma (Mallorca), Spain"
    pdf="http://www.lrec-conf.org/proceedings/lrec2026/pdf/2026.lrec2026-1.799.pdf"
	doi="10.63317/573q4exhmpgd"
	hal="https://hal.science/hal-05627744"
>}}
@inproceedings{le-etal-2026-pantagruel,
  title = {Pantagruel: Unified Self-Supervised Encoders for French Text and Speech},
  author = {Le, Phuong-Hang and Pelloin, Valentin and Chatelain, Arnault and Bouziane, Maryem and Ghennai, Mohammed and Guan, Qianwen and Milintsevich, Kirill and Mdhaffar, Salima and Mannion, Aidan and Defauw, Nils and Gu, Shuyue and Audibert, Alexandre Daniel and Dinarelli, Marco and Estève, Yannick and Goeuriot, Lorraine and Lalande, Steffen and Hervé, Nicolas and Coavoux, Maximin and Portet, François and Ollion, Étienne and Candito, Marie and Peyrard, Maxime and Rossato, Solange and Lecouteux, Benjamin and Nardy, Aurélie and Sérasset, Gilles and Segonne, Vincent and Evain, Solène and Fabre, Diandra and Schwab, Didier},
  booktitle = {Proceedings of the Fifteenth Language Resources and Evaluation Conference (LREC 2026)},
  month = {May},
  year = {2026},
  pages = {10168--10191},
  address = {Palma, Mallorca, Spain},
  publisher = {European Language Resources Association (ELRA)},
  editor = {Piperidis, Stelios and Bel, Núria and van den Heuvel, Henk and Ide, Nancy and Krek, Simon and Toral, Antonio},
  doi = {10.63317/573q4exhmpgd},
  abstract = {We release Pantagruel models, a new family of self-supervised encoder models for French text and speech. Instead of predicting modality-tailored targets such as textual tokens or speech units, Pantagruel learns contextualized target representations in the feature space, allowing modality-specific encoders to capture linguistic and acoustic regularities more effectively. Separate models are pre-trained on large-scale French corpora, including Wikipedia, OSCAR and CroissantLLM for text, together with MultilingualLibriSpeech, LeBenchmark, and INA-100k for speech. INA-100k is a newly introduced 100,000-hour corpus of French audio derived from the archives of the Institut National de l’Audiovisuel (INA), the national repository of French radio and television broadcasts, providing highly diverse audio data. We evaluate Pantagruel across a broad range of downstream tasks spanning both modalities, including those from the standard French benchmarks such as FLUE or LeBenchmark. Across these tasks, Pantagruel models show competitive or superior performance compared to strong French baselines such as CamemBERT, FlauBERT, and LeBenchmark2.0, while maintaining a shared architecture that can seamlessly handle either speech or text inputs. These results confirm the effectiveness of feature-space self-supervised objectives for French representation learning and highlight Pantagruel as a robust foundation for multimodal speech-text understanding.}
  }
{{< /publication >}}

{{< publication
	id="lrec2026_c"
	title="spINAch: A Diachronic Corpus of French Broadcast Speech Controlled for Speakers' Age and Gender"
	authors="Simon Devauchelle, David Doukhan, Rémi Uro, Lucas Ondel Yang, Valentin Pelloin, Olympia Imbert-Brégégère, Véronique Lefort, Kévin Picard, Emeline Seignobos, Albert Rilliard"
	year="2026"
	where="Fifteenth International Conference on Language Resources and Evaluation (LREC 2026), Palma (Mallorca), Spain"
    pdf="http://www.lrec-conf.org/proceedings/lrec2026/pdf/2026.lrec2026-1.459.pdf"
	doi="10.63317/58hgwvgvkz6g"
>}}
@inproceedings{devauchelle-etal-2026-spinach,
  title = {spINAch: A Diachronic Corpus of French Broadcast Speech Controlled for Speakers' Age and Gender},
  author = {Devauchelle, Simon and Doukhan, David and Uro, Remi and Ondel, Lucas and Pelloin, Valentin and Imbert-Brégégère, Olympia and Lefort, Véronique and Picard, Kévin and Seignobos, Emeline and Rilliard, Albert},
  booktitle = {Proceedings of the Fifteenth Language Resources and Evaluation Conference (LREC 2026)},
  month = {May},
  year = {2026},
  pages = {5805--5820},
  address = {Palma, Mallorca, Spain},
  publisher = {European Language Resources Association (ELRA)},
  editor = {Piperidis, Stelios and Bel, Núria and van den Heuvel, Henk and Ide, Nancy and Krek, Simon and Toral, Antonio},
  doi = {10.63317/58hgwvgvkz6g},
  abstract = {We present spINAch, a large diachronic corpus of French speech from radio and television archives, balanced by speakers’ gender, age (20-95 years old), and spanning 60 years from 1955 to 2015. The dataset includes over 320 hours of recordings from more than two thousand speakers. The methodology for building the corpus is described, focusing on the quality of collected samples in acoustic terms. The data were automatically transcribed and phonetically aligned to allow studies at a phonemic level. More than 3 million oral vowels have been analyzed to propose their fundamental frequency and formants. The corpus, available to the community for research purposes, is valuable for describing the evolution of Parisian French through the representation of gender and age. The presented analyses also demonstrate that the diachronic nature of the corpus allows the observation of various phonetic phenomena, such as the evolution of voice pitch over time (which does not differ by gender in our data) and the neutralization of the /a/-/ɑ/ opposition in Parisian French during this period.}
  }
{{< /publication >}}

#### 2024

{{< publication
	id="interspeech2024_a"
	title="Automatic Classification of News Subjects in Broadcast News: Application to a Gender Bias Representation Analysis"
	authors="Valentin Pelloin, Lena Dodson, Émile Chapuis, Nicolas Hervé, David Doukhan"
	year="2024"
	where="Interspeech 2024, Kos, Greece"
    pdf="https://www.isca-archive.org/interspeech_2024/pelloin24_interspeech.pdf"
	doi="https://doi.org/10.21437/Interspeech.2024-1854"
>}}
@inproceedings{pelloin24_interspeech,
  author={Valentin Pelloin and Lena Dodson and \'Emile Chapuis and Nicolas Hervé and David Doukhan},
  title={{Automatic Classification of News Subjects in Broadcast News: Application to a Gender Bias Representation Analysis}},
  year=2024,
  booktitle={Proc. Interspeech 2024},
  pages={3055--3059},
  doi={10.21437/Interspeech.2024-1854},
  }
{{< /publication >}}

{{< publication
	id="interspeech2024_b"
	title="Gender Representation in TV and Radio: Automatic Information Extraction methods versus Manual Analyses"
	authors="David Doukhan, Lena Dodson, Manon Conan, Valentin Pelloin, Aurélien Clamouse, Mélina Lepape, Géraldine Van Hille, Cécile Méadel, Marlène Coulomb-Gully"
	year="2024"
	where="Interspeech 2024, Kos, Greece"
    pdf="https://www.isca-archive.org/interspeech_2024/doukhan24_interspeech.pdf"
	doi="https://doi.org/10.21437/Interspeech.2024-1921"
>}}
@inproceedings{doukhan24_interspeech,
  author={David Doukhan and Lena Dodson and Manon Conan and Valentin Pelloin and Aurélien Clamouse and Mélina Lepape and Géraldine {Van Hille} and Cécile Méadel and Marlène Coulomb-Gully},
  title={{Gender Representation in TV and Radio: Automatic Information Extraction methods versus Manual Analyses}},
  year=2024,
  booktitle={Proc. Interspeech 2024},
  pages={3060--3064},
  doi={10.21437/Interspeech.2024-1921}
  }
{{< /publication >}}

{{< publication
	id="thesis2024"
    title="La compréhension de la parole dans les systèmes de dialogues humain-machine à l'heure des modèles pré-entraînés"
	authors="Valentin Pelloin"
	year="2024"
	where="Le Mans University (PhD thesis)"
    pdf="https://theses.hal.science/tel-04446162v1/file/2024LEMA1002.pdf"
    hal="https://theses.hal.science/tel-04446162"
>}}
@phdthesis{pelloin2024,
  title = {{La compr{\'e}hension de la parole dans les syst{\`e}mes de dialogues humain-machine {\`a} l'heure des mod{\`e}les pr{\'e}-entra{\^i}n{\'e}s}},
  author = {Pelloin, Valentin},
  year = 2024,
  month = Jan,
  number = {2024LEMA1002},
  url = {https://theses.hal.science/tel-04446162},
  school = {{Le Mans Universit{\'e}}},
  keywords = {Spoken language understanding ; Automatic speech recognition ; Neural networks ; Pretrained models ; Self-Supervised models ; Attention mechanisms ; Semantic concepts extraction ; Deep learning ; Compr{\'e}hension de la parole ; Reconnaissance automatique de la parole ; R{\'e}seaux de neurones ; Mod{\`e}les pr{\'e}-Entra{\^i}n{\'e}s ; Mod{\`e}les auto-Supervis{\'e}s ; M{\'e}canismes d'attention ; Extraction de concepts s{\'e}mantiques ; Apprentissage profond},
  type = {Theses},
  pdf = {https://theses.hal.science/tel-04446162/file/2024LEMA1002.pdf},
  hal_id = {tel-04446162},
  hal_version = {v1}
}
{{< /publication >}}

#### 2022

{{< publication
	id="slt2022"
	title="On the Use of Semantically-Aligned Speech Representations for Spoken Language Understanding"
	authors="Gaëlle Laperrière, Valentin Pelloin, Mickaël Rouvier, Themos Stafylakis and Yannick Estève"
	year="2022"
	where="SLT 2022, Doha, Qatar"
	pdf="https://arxiv.org/pdf/2210.05291.pdf"
	doi="https://doi.org/10.1109/SLT54892.2023.10023013"
>}}
@inproceedings{laperriere22_slt,
  title = {On the Use of Semantically-Aligned Speech Representations for Spoken Language Understanding},
  author = {Laperrière, Gaëlle and Pelloin, Valentin and Rouvier, Mickaël and Stafylakis, Themos and Estève, Yannick},
  year = 2023,
  booktitle = {2022 IEEE Spoken Language Technology Workshop (SLT)},
  volume = {},
  number = {},
  pages = {361--368},
  doi = {10.1109/SLT54892.2023.10023013}
}
{{< /publication >}}

{{< publication
	id="interspeech2022"
	title="ASR-Generated Text for Language Model Pre-training Applied to Speech Tasks"
	authors="Valentin Pelloin, Franck Dary, Nicolas Herve, Benoit Favre, Nathalie Camelin, Antoine Laurent and Laurent Besacier"
	year="2022"
	where="Interspeech 2022, Incheon, South Korea"
    pdf="https://www.isca-archive.org/interspeech_2022/pelloin22_interspeech.pdf"
	doi="http://doi.org/10.21437/Interspeech.2022-352"
>}}
@inproceedings{pelloin22_interspeech,
  author={Valentin Pelloin and Franck Dary and Nicolas Hervé and Benoit Favre and Nathalie Camelin and Antoine Laurent and Laurent Besacier},
  title={{ASR-Generated Text for Language Model Pre-training Applied to Speech Tasks}},
  year=2022,
  booktitle={Proc. Interspeech 2022},
  pages={3453--3457},
  doi={10.21437/Interspeech.2022-352}
  }
{{< /publication >}}

{{< publication
	id="wacl2022"
	title="Using ASR-Generated Text for Spoken Language Modeling"
	authors="Nicolas Hervé, Valentin Pelloin, Benoit Favre, Franck Dary, Antoine Laurent, Sylvain Meignier and Laurent Besacier"
	year="2022"
	where="ACL 2022 - Workshop on Challenges & Perspectives in Creating Large Language Models (Association for Computational Linguistics), Dublin, Ireland"
	pdf="https://aclanthology.org/2022.bigscience-1.2.pdf"
	doi="http://doi.org/10.18653/v1/2022.bigscience-1.2"
>}}
@inproceedings{herve2022,
  title = {Using {ASR}-Generated Text for Spoken Language Modeling},
  author = {Herv{\'e}, Nicolas  and Pelloin, Valentin  and Favre, Benoit  and Dary, Franck  and Laurent, Antoine  and Meignier, Sylvain  and Besacier, Laurent},
  year = 2022,
  month = may,
  booktitle = {Proceedings of BigScience Episode {\#}5 -- Workshop on Challenges {\&} Perspectives in Creating Large Language Models},
  publisher = {Association for Computational Linguistics},
  address = {virtual+Dublin},
  pages = {17--25},
  doi = {10.18653/v1/2022.bigscience-1.2},
  url = {https://aclanthology.org/2022.bigscience-1.2}
}
{{< /publication >}}

{{< publication
	id="lrec2022_a"
	title="The Spoken Language Understanding MEDIA Benchmark Dataset in the Era of Deep Learning: data updates, training and evaluation tools"
	authors="Gaëlle Laperrière, Valentin Pelloin, Antoine Caubrière, Salima Mdhaffar, Nathalie Camelin, Sahar Ghannay, Bassam Jabaian and Yannick Estève"
	year="2022"
	where="LREC 2022 - Language Resources and Evaluation Conference 2022, Marseille, France"
	pdf="http://www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.171.pdf"
	hal="https://hal.science/hal-03706938"
>}}
@inproceedings{laperriere2022_b,
  title = {The Spoken Language Understanding MEDIA Benchmark Dataset in the Era of Deep Learning: data updates, training and evaluation tools},
  author = {Gaëlle Laperrière, Valentin Pelloin, Antoine Caubrière, Salima Mdhaffar, Nathalie Camelin, Sahar Ghannay, Bassam Jabaian and Yannick Estève},
  year = 2022,
  month = {June},
  booktitle = {LREC 2022},
  pages = {1595--1602},
  address = {Marseille, France},
  publisher = {European Language Resources Association},
}
{{< /publication >}}

{{< publication
	id="lrec2022_b"
	title="Impact Analysis of the Use of Speech and Language Models Pretrained by Self-Supersivion for Spoken Language Understanding"
	authors="Salima Mdhaffar, Valentin Pelloin, Antoine Caubrière, Gaëlle Laperriere, Sahar Ghannay, Bassam Jabaian, Nathalie Camelin and Yannick Estève"
	year="2022"
	where="LREC 2022 - Language Resources and Evaluation Conference 2022, Marseille, France"
	pdf="http://www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.316.pdf"
	hal="https://hal.archives-ouvertes.fr/hal-03706925"
>}}
@inproceedings{mdhaffar2022,
  title = {Impact Analysis of the Use of Speech and Language Models Pretrained by Self-Supersivion for Spoken Language Understanding},
  author = {Salima Mdhaffar, Valentin Pelloin, Antoine Caubrière, Gaëlle Laperriere, Sahar Ghannay, Bassam Jabaian, Nathalie Camelin and Yannick Estève},
  year = 2022,
  month = {June},
  booktitle = {LREC 2022},
  pages = {2949--2956},
  address = {Marseille, France},
  publisher = {European Language Resources Association},
}
{{< /publication >}}

{{< publication
	id="jep2022_a"
	title="Architectures neuronales bout-en-bout pour la compréhension de la parole"
	authors="Valentin Pelloin, Nathalie Camelin, Antoine Laurent, Renato De Mori and Sylvain Meignier"
	year="2022"
	where="JEP 2022 - Journées d'Études sur la Parole 2022, Noirmoutier, France"
    pdf="https://www.isca-archive.org/jep_2022/pelloin22_jep.pdf"
	hal="https://hal.science/hal-03770548"
	doi="http://doi.org/10.21437/JEP.2022-87"
>}}
@inproceedings{pelloin2022jep,
  title = {Architectures neuronales bout-en-bout pour la compréhension de la parole},
  author = {Valentin Pelloin, Nathalie Camelin, Antoine Laurent, Renato De Mori and Sylvain Meignier},
  year = 2022,
  month = {June},
  booktitle = {JEP 2022},
  address = {Noirmoutier, France},
  pages = {823--832},
  doi = {10.21437/JEP.2022-87}
}
{{< /publication >}}

{{< publication
	id="jep2022_b"
	title="Le benchmark MEDIA revisité : données, outils et évaluation dans un contexte d’apprentissage profond"
	authors="Gaëlle Laperrière, Valentin Pelloin, Antoine Caubrière, Salima Mdhaffar, Nathalie Camelin, Sahar Ghannay, Bassam Jabaian and Yannick Estève"
	year="2022"
	where="JEP 2022 - Journées d'Études sur la Parole 2022, Noirmoutier, France"
    pdf="https://www.isca-archive.org/jep_2022/laperriere22_jep.pdf"
	hal="https://hal.science/hal-03770588"
	doi="http://doi.org/10.21437/JEP.2022-51"
>}}
@inproceedings{laperriere2022_a,
  title = {Le benchmark MEDIA revisité : données, outils et évaluation dans un contexte d’apprentissage profond},
  author = {Gaëlle Laperrière, Valentin Pelloin, Antoine Caubrière, Salima Mdhaffar, Nathalie Camelin, Sahar Ghannay, Bassam Jabaian and Yannick Estève},
  year = 2022,
  month = {June},
  booktitle = {JEP 2022},
  address = {Noirmoutier, France},
  pages = {481--490},
  doi = {10.21437/JEP.2022-51}
}
{{< /publication >}}



#### 2021
{{< publication
	id="icassp2021"
	title="End2End Acoustic to Semantic Transduction"
	authors="Valentin Pelloin, Nathalie Camelin, Antoine Laurent, Renato de Mori, Antoine Caubrière, Yannick Estève and Sylvain Meignier"
	year="2021"
	where="ICASSP 2021 - 2021 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)"
	pdf="https://arxiv.org/pdf/2102.01013.pdf"
	doi="https://doi.org/10.1109/ICASSP39728.2021.9413581"
>}}
@inproceedings{pelloin2021,
  title = {End2End Acoustic to Semantic Transduction},
  author = {Pelloin, Valentin and Camelin, Nathalie and Laurent, Antoine and De Mori, Renato and Caubrière, Antoine and Estève, Yannick and Meignier, Sylvain},
  year = 2021,
  booktitle = {ICASSP 2021 - 2021 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)},
  volume = {},
  number = {},
  pages = {7448--7452},
  doi = {10.1109/icassp39728.2021.9413581},
  url = {https://ieeexplore.ieee.org/document/9413581}
  }
{{< /publication >}}

#### 2020
{{< publication
	id="lambdamu2020"
	title="Technologies sémantiques et accès à l’information dans le prescrit SNCF"
	authors="Coralie Reutenauer, Luce Lefeuvre, Aurélie Fouqueray, Thibault Prouteau, Valentin Pelloin, Cédric Lopez, Camelin Nathalie, Frédérique Segond, Dugué Nicolas and Didier Bourigault"
	year="2020"
	where="22ème Congrès de Maîtrise des Risques et de Sûreté de Fonctionnement, Institut pour la Maîtrise des Risques, Oct 2020, Le Havre (e-congrès), France"
	pdf="https://hal.science/hal-03476574/document"
	hal="https://hal.science/hal-03476574/"
>}}
@inproceedings{reutenauer2020,
  title = {{Technologies s{\'e}mantiques et acc{\`e}s {\`a} l'information dans le prescrit SNCF}},
  author = {Reutenauer, Coralie and Lefeuvre, Luce and Fouqueray, Aur{\'e}lie and Prouteau, Thibault and Pelloin, Valentin and Lopez, C{\'e}dric and Nathalie, Camelin and Segond, Fr{\'e}d{\'e}rique and Nicolas, Dugu{\'e} and Bourigault, Didier},
  year = 2020,
  month = Oct,
  booktitle = {{Lambda Mu 22 (e-congr{\`e}s) - 22{\`e}me Congr{\`e}s de Ma{\^i}trise des Risques et de S{\^u}ret{\'e} de Fonctionnement, Institut pour la Ma{\^i}trise des Risques}},
  address = {Le Havre (e-congr{\`e}s), France},
  url = {https://hal.archives-ouvertes.fr/hal-03476574},
  hal_id = {hal-03476574},
  hal_version = {v1}
}
{{< /publication >}}

{{< publication
	id="recital2020"
	title="Apprentissage de plongements de mots sur des corpus en langue de spécialité : une étude d’impact"
	authors="Valentin Pelloin and Thibault Prouteau"
	year="2020"
	where="Actes de la 6e conférence conjointe Journées d'Études sur la Parole (JEP, 33e édition), Traitement Automatique des Langues Naturelles (TALN, 27e édition), Rencontre des Étudiants Chercheurs en Informatique pour le Traitement Automatique des Langues (RECITAL, 22e édition)"
	pdf="https://www.aclweb.org/anthology/2020.jeptalnrecital-recital.13.pdf"
	hal="https://hal.science/hal-02786198v3"
>}}
@inproceedings{pelloin2020,
  title = {Apprentissage de plongements de mots sur des corpus en langue de sp{\'e}cialit{\'e} : une {\'e}tude d{'}impact},
  author = {Pelloin, Valentin and Prouteau, Thibault},
  year = 2020,
  month = 6,
  booktitle = {Actes de la 6e conf{\'e}rence conjointe Journ{\'e}es d'{\'E}tudes sur la Parole (JEP, 33e {\'e}dition), Traitement Automatique des Langues Naturelles (TALN, 27e {\'e}dition), Rencontre des {\'E}tudiants Chercheurs en Informatique pour le Traitement Automatique des Langues (R{\'E}CITAL, 22e {\'e}dition). Volume 3 : Rencontre des {\'E}tudiants Chercheurs en Informatique pour le TAL},
  publisher = {ATALA et AFCP},
  address = {Nancy, France},
  pages = {164--178},
  url = {https://aclanthology.org/2020.jeptalnrecital-recital.13},
  language = {French}
}
{{< /publication >}}


</ol>
</div>

## Other work

- [svd2vec](https://github.com/valentinp72/svd2vec), a Python library that converts words to vectors using PMI and SVD


<!-- enabling modal boxes -->
<script type="text/javascript" src="/modal.js"></script>

<!-- mastodon link verification -->
<div style="display:none"><a rel="me" href="https://mastodon.social/@valentinp72"><!-- nothing --></a></div>
