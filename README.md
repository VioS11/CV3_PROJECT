# CV3_PROJECT
Proiect de deep learning pentru detecția și localizarea multi-clasă a bolilor frunzelor de tomate

## Descriere

Scopul proiectului este dezvoltarea unui sistem de tip object detection capabil să identifice mai multe tipuri de boli ale frunzelor de tomate și să localizeze regiunile afectate prin bounding box-uri.

## Dataset

Va fi utilizat un set de date public disponibil pe Zenodo, cu imagini ale frunzelor de tomate adnotate pentru detecția bolilor în format compatibil YOLO.

## Model

Pentru implementare va fi utilizată o arhitectură din familia YOLO. Varianta exactă a modelului va fi aleasă în funcție de complexitatea setului de date și de resursele hardware disponibile.

## Evaluare

Performanța modelului va fi evaluată utilizând metrici specifice object detection:

- mAP
- Precision
- Recall
- F1-score
- IoU

## Hardware

Antrenarea, testarea și inferența vor fi încercate atât local, cât și în Google Colab, unde poate fi utilizată accelerarea GPU.

## Status

Proiect în dezvoltare.