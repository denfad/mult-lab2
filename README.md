# Лабораторные работы 2 по курсу "Мультимедиа"
Выволнил: Фадеев Д.В.

Группа: М8О-410Б-21

## Используемые датасеты
**Лабраторная 6:** классификация ножей и пистолетов https://www.kaggle.com/datasets/leventoz/knife-vs-pistol

**Лабраторная 7:** сегментация полипов при эндоскопии https://www.kaggle.com/datasets/debeshjha1/kvasirseg

**Лабраторная 8:** обнаружение дронов https://www.kaggle.com/datasets/cybersimar08/drone-detection

## Лабораторные работы
- [Лабораторная №6 Проведение исследований с моделями классификации](lab6.ipynb) 
- [Лабораторная №7 Проведение исследований с моделями семантической сегментации](lab7.ipynb) 
- [Лабораторная №8 Проведение исследований с моделями обнаружения объектов](lab8.ipynb) 

## Результаты

### Лабраторная 6
Модель|Метрики обычного бейзлайна| Метрики улучшенного бейзлайна   |
|---|---|---------------------------------|
|Свёрточный классификатор|max_acc = 0.96| max_acc = 0.84|
|Трансформерный классификатор|max_acc = 0.96 | max_acc = 0.92 |
|Мой свёрточный классификатор|max_acc = 0.62 | max_acc = 0.64  |
|Мой трансформерный классификатор|max_acc = 0.4 | max_acc = 0.4 |

### Лабраторная 7
Модель|Метрики обычного бейзлайна| Метрики улучшенного бейзлайна   |
|---|---|---------------------------------|
|Свёрточный классификатор|IoU = 0.77 Acc = 0.84| IoU = 0.79 Acc = 0.87|
|Трансформерный классификатор|IoU = 0.32 Acc = 0.74 | IoU = 0.3 Acc = 0.3 |
|Мой свёрточный классификатор|IoU = 0.28 Acc = 0.34 | IoU = 0.28 Acc = 0.34  |
|Мой трансформерный классификатор|IoU = 0.25 Acc = 0.3 | IoU = 0.18 Acc = 0.2 |

### Лабраторная 8
Модель|Метрики обычного бейзлайна| Метрики улучшенного бейзлайна   |
|---|---|---------------------------------|
|YOLOv8n|mAP@0.5 = 0.542| mAP@0.5 = 0.542|
|Моя YOLOv8n|mAP@0.5 = 0.0341 | mAP@0.5 = 0.0292  |