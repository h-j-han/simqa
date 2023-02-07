# SimQA: Detecting Simultaneous MT Errors through Word-by-Word Question Answering
This repository contains our Crosslingual Quizbowl Dataset, XQB dataset for the EMNLP 2022 paper that can be found [here](https://aclanthology.org/2022.emnlp-main.378/)!

## Data Statistics
| Language | # Question | # Sentences |
|----------|------------|-------------|
| Polish   | 512        | 1661        |
| Spanish  | 148        | 603         |

## Sample
|            | Text                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Source     | Tę współrzędną wyznacza kąt dwuścienny między półpłaszczyzną  południka zerowego a półpłaszczyzną południka przechodzącego przez  określony punkt na powierzchni Ziemi. Tę miarę liczy się od południka  zerowego (Greenwich) aż do południka 180°. Aby otrzymać punkt, nazwij  tę długość, która może przyjmować miary od 0° do 180° i może być  wschodnia lub zachodnia.                                                                                                                                                                                |
| Answer-src | Długość geograficzna                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| Human      | This coordinate is determined by the dihedral angle found between the  half-plane prime meridian and the half-plane meridian which passed  through a specific point on the Earth's surface. This measure is counted  from the prime meridian (Greenwich) to the 180° meridian. To gain a  point, give the name of the length, which can measure between 0° to 180°  and can be east or west.                                                                                                                                                              |
| Answer-tgt | Longitude                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |



|            | Text                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Source     | W 1899 Halford Mackinder twierdził, że jest pierwszą osobą, która  wspięła się na tę górę, a ludzie Kikuju nazywają tę górę Kirinyaga ,  co oznacza „tę ze strusiem”, podczas gdy Masajowie wierzą, że ich  przodkowie zeszli z tej góry na początku czasu. Góra ta jest głównym  obszarem zlewiska rzeki Tana, największej rzeki w kraju, która może  być również nazywana tak samo jak ta góra. Aby zdobyć punkt, podaj  nazwę tej drugiej najwyższej góry w Afryce.                                                                                    |
| Answer-src | Mount Kenia                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| Human      | In 1899, Halford Mackinder claimed that he was the first person to  climb this mountain, and the people of Kikuyu named this mountain  "Mount Kirinyaga", meaning „the one with the ostrich”, while the  people of Maasai believe that their ancestors descended from this  mountain at the beginning of time. This mountain is the main  catchment area of the Tana river, the largest river in the country,  which is sometimes refered to by the same name as the mountain.  To gain a point, enter the name of the second highest mountain in Africa. |
| Answer-tgt | Mount Kenya                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |


## Reference
If you use any contents of this repository, please cite us. 
```
@inproceedings{han-etal-2022-simqa,
    title = "{S}im{QA}: Detecting Simultaneous {MT} Errors through Word-by-Word Question Answering",
    author = "Han, HyoJung  and
      Carpuat, Marine  and
      Boyd-Graber, Jordan",
    booktitle = "Proceedings of the 2022 Conference on Empirical Methods in Natural Language Processing",
    month = dec,
    year = "2022",
    address = "Abu Dhabi, United Arab Emirates",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.emnlp-main.378",
    pages = "5598--5616",
    abstract = "Detractors of neural machine translation admit that while its translations are fluent, it sometimes gets key facts wrong. This is particularly important in simultaneous interpretation where translations have to be provided as fast as possible: before a sentence is complete. Yet, evaluations of simultaneous machine translation (SimulMT) fail to capture if systems correctly translate the most salient elements of a question: people, places, and dates. To address this problem, we introduce a downstream word-by-word question answering evaluation task (SimQA): given a source language question, translate the question word by word into the target language, and answer as soon as possible. SimQA jointly measures whether the SimulMT models translate the question quickly and accurately, and can reveal shortcomings in existing neural systems{---}hallucinating or omitting facts.",
}
```
## Contact
For any questions, write to hjhan@cs.umd.edu.

