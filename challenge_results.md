---
layout: page
title: SASV2022 Challenge results
---

## Results
The first SASV challenge has received **23** valid submissions.
This page contains the ranks, system description, and the correlation between metrics.

### Ranks
Below table presents the results sorted by SASV-EER(%) on the evaluation set.
- `Baseline1_v2` is an improved version of the Baseline1 from the evaluation plan with additional softmax applied to the CM output. Details will be addressed in the challenge summary paper.
- Teams with equal SASV-EER is displayed in alphabetical order.
- Results are cross-validated with the reported values of the system description. The final performances correspond to the result of evaluating entire submissions using the same software developed by the organisers for fairness.

| Rank | Team Name | SASV-EER | SV-EER | SPF-EER|
--|--|--|--|--
|1| IDVoice | 0.13 | 0.11 | 0.17|
|2| DKU-OPPO | 0.21 | 0.46 | 0.19|
|3| HYU | 0.28 | 0.28 | 0.28|
|4| DoubleRoc | 0.37 | 0.45 | 0.26|
|5| FlySpeech | 0.56 | 0.86 | 0.35|
|5| IRLAB | 0.56 | 0.73 | 0.43|
|7| VicomSpeech | 0.84 | 0.97 | 0.58|
|8| CUHK-NTU | 0.89 | 1.06 | 0.73|
|9| MARG | 1.15 | 1.42 | 0.76|
|10| NII_TJU | 1.19 | 1.32 | 1.14|
|11| UR-AIR | 1.34 | 1.70 | 1.08|
|12| Clips | 1.36 | 1.75 | 0.76|
|13| Orange_Lium | 1.47 | 2.44 | 0.56|
| | Baseline1-v2 | 1.71 | 1.67 | 1.77|
|14| VTCC | 1.86 | 2.42 | 0.97|
|15| DeepASV | 2.48 | 3.80 | 0.65|
|16| SHELEZYAKA | 2.77 | 3.54 | 0.54|
|17| Xmuspeech | 2.89 | 4.28 | 0.89|
|18| HCCL | 4.30 | 5.62 | 1.21|
|19| Magnum | 4.48 | 7.10 | 1.08|
|20| CAU-KU | 4.95 | 9.05 | 0.28|
|21| Tandem | 6.22 | 11.92 | 0.77|
| | Baseline2 | 6.54 | 11.99 | 0.78|
|22| DHU | 12.48 | 19.14 | 7.00|
| | Baseline1 | 19.31 | 35.31 | 0.67|
|23| Souvik | 24.32 | 48.92 | 0.71|

### System descriptions
Below are system descriptions from each team sorted in alphabetical order.
- System descriptions received after the deadline are reflected. Thus, discrepancy may exist between the performances reported above.

<details><summary>Links of descriptions</summary>
<div markdown="1">
- [Team CAU-KU]({{ site.url }}/pdfs/2022_descriptions/CAU-KU.pdf)
- [Team Clips]({{ site.url }}/pdfs/2022_descriptions/Clips.pdf)
- [Team CUHK-NTU]({{ site.url }}/pdfs/2022_descriptions/CUHK-NTU.pdf)
- [Team DeepASV]({{ site.url }}/pdfs/2022_descriptions/DeepASV.pdf)
- [Team DHU]({{ site.url }}/pdfs/2022_descriptions/DHU.pdf)
- [Team DKU-OPPO]({{ site.url }}/pdfs/2022_descriptions/DKU-OPPO.pdf)
- [Team DoubleRoc]({{ site.url }}/pdfs/2022_descriptions/DoubleRoc.pdf)
- [Team FlySpeech]({{ site.url }}/pdfs/2022_descriptions/FlySpeech.pdf)
- [Team HCCL]({{ site.url }}/pdfs/2022_descriptions/HCCL.pdf)
- [Team HYU]({{ site.url }}/pdfs/2022_descriptions/HYU.pdf)
- [Team IDVoice]({{ site.url }}/pdfs/2022_descriptions/IDVoice.pdf)
- [Team IRLAB]({{ site.url }}/pdfs/2022_descriptions/IRLAB.pdf)
- [Team Magnum]({{ site.url }}/pdfs/2022_descriptions/Magnum.pdf)
- [Team MARG]({{ site.url }}/pdfs/2022_descriptions/MARG.pdf)
- [Team NII-TJU]({{ site.url }}/pdfs/2022_descriptions/NII-TJU.pdf)
- [Team Orange-Lium]({{ site.url }}/pdfs/2022_descriptions/Orange-Lium.pdf)
- [Team SHELEZYAKA]({{ site.url }}/pdfs/2022_descriptions/SHELEZYAKA.pdf)
- [Team Souvik]({{ site.url }}/pdfs/2022_descriptions/Souvik.pdf)
- [Team Tandem]({{ site.url }}/pdfs/2022_descriptions/Tandem.pdf)
- [Team UR-AIR]({{ site.url }}/pdfs/2022_descriptions/UR-AIR.pdf)
- [Team VicomSpeech]({{ site.url }}/pdfs/2022_descriptions/VicomSpeech.pdf)
- [Team VTCC]({{ site.url }}/pdfs/2022_descriptions/VTCC.pdf)
- [Team Xmuspeech]({{ site.url }}/pdfs/2022_descriptions/Xmuspeech.pdf)
</div>
</details>


### Relationship of SASV-EER with SV-EER and SPF-EER
<img src='{{ "/images/SASV2022_result_correlation.png" | relative_url }}' style='max-width: 100%;' />