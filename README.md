# SimQA: Detecting Simultaneous MT Errors through Word-by-Word Question Answering
This repository contains our Crosslingual Quizbowl Dataset, XQB dataset for the EMNLP 2022 paper that can be found [here](http://users.umiacs.umd.edu/~jbg/docs/2022_emnlp_simqa.pdf)!

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
@inproceedings{Han:Carpuat:Boyd-Graber-2022,
Title = {SimQA: Detecting Simultaneous MT Errors through Word-by-Word Question Answering},
Author = {HyoJung Han and Marine Carpuat and Jordan Boyd-Graber},
Booktitle = {Empirical Methods in Natural Language Processing},
Year = {2022},
Location = {Abu Dhabi},
Url = {http://umiacs.umd.edu/~jbg//docs/2022_emnlp_simqa.pdf},
}
```
## Contact
For any questions, write to hjhan@cs.umd.edu.

