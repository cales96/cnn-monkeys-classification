# cnn-monkeys-classification
In this project I present the best classifier I built, using CNN to classify Monkey images predicting the species of the captured animals. The model is chosen in terms of accuracy and loss performance in the validation set, chosen among the many through an ablation study.
The model is trained on the dataset available on Kaggle (https://www.kaggle.com/slothkong/10-monkey-species), it present 1367 images, divided in traing and validation set, labelled in 10 classes:

| Label | Latin Name            | Common Name               |
|-------|-----------------------|---------------------------|
| n0    | alouatta_palliata     | mantled_howler            |
| n1    | erythrocebus_patas    | patas_monkey              |
| n2    | cacajao_calvus        | bald_uakari               |
| n3    | macaca_fuscata        | japanese_macaque          |
| n4    | cebuella_pygmea       | pygmy_marmoset            |
| n5    | cebus_capucinus       | white_headed_capuchin     |
| n6    | mico_argentatus       | silvery_marmoset          |
| n7    | saimiri_sciureus      | common_squirrel_monkey    |
| n8    | aotus_nigriceps       | black_headed_night_monkey |
| n9    | trachypithecus_johnii | nilgiri_langur            |


