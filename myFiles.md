# Описание алгоритмов сортировки и сравнение их производительности
---
![d](300-300b.jpg)
## Вступление
---
На эту тему написано уже немало статей. Однако я еще не видел статьи, в которой сравниваются все основные сортировки на большом числе тестов разного типа и размера. Кроме того, далеко не везде выложены реализации и описание набора тестов. Это приводит к тому, что могут возникнуть сомнения в правильности исследования. Однако цель моей работы состоит не только в том, чтобы определить, какие сортировки работают быстрее всего (в целом это и так известно). В первую очередь мне было интересно исследовать алгоритмы, оптимизировать их, чтобы они работали как можно быстрее. Работая над этим, мне удалось придумать эффективную формулу для сортировки Шелла
## Описание основных сортировок и их реализация
---
Я постараюсь кратко и понятно описать сортировки и указать асимптотику, хотя последнее в рамках данной статьи не очень важно (интересно же узнать реальное время работы). О потреблении памяти в дальнейшем ничего писать не буду, замечу только, что сортировки, использующие непростые структуры данных (как, например, сортировка деревом), обычно потребляют ее в больших количествах, а остальные сортировки в худшем случае только создают вспомогательный массив. Также существует понятие стабильности (устойчивости) сортировки. Это значит, что относительный порядок элементов при их равенстве не меняется. Это тоже в рамках данной статьи неважно (в конце концов, можно просто прицепить к элементу его индекс), однако в одном месте пригодится.
## Сортировка пузырьком / Bubble sort
---

## Шейкерная сортировка / Shaker sort
---

## Сортировка расческой / Comb sort
---

## Сортировка вставками / Insertion sort
---

## Сортировка Шелла / Shellsort