## Лабораторная работа №4
### **Вывод**
<div style="font-size: smaller; font-family: Arial; line-height: 1.6;">
В результате проведения лабораторной работы №4 была обучена модель <span style="font-weight: bold">K-средних</span> на трех различных датасетах: digits(датасет с цифрами), wine(датасет с сортами вина), cancer(датасет с данными о раковых опухолях).

Данные во всех трех датасетах были предварительно изучены при помощи их визуализации и разделены на тренировочные и тестовые.

Датасет с цифрами состоял из значений пикселей изображений цифр размерностью 8x8 пикселей и имел 10 возможных результатов (Арабские цифры от 0 до 9). 

Данные в датасете с винами представляли из себя значения 13 различных признаков, такие как: процент содержания алкоголя, яблочной кислоты, фенола, оттенок вина и т.д. Ответы были разделены на 3 класса.

В датасете с раковыми опухолями содержались данные о 30 разных признаках, определяющих тип опухоли(доброкачественная или злокачественная).

После обучения на датасетах с цифрами модель K-средних показала наибольшую точность - 99%. В случае с датасетом с раковыми опухолями был получен результат в 92%. В то же время модель, обученная на данных о винах она смогла выдать лишь 76% точности.

Возможно модель плохо справилась с данными о винах, из-за частых пересечений значений признаков между разными сортами вин. Из-за этого модель чаще путала один сорт вина с другим.

Данные о раковых опухолях хоть и содержали намного больше признаков, но были лучше кластеризованы и делились лишь на 2 класса (в отличие от 3 в случае с винами). Благодаря этому модели было намного легче определить является ли рак доброкачественным или злокачественным.

Наконец, в датасете с цифрами можно довольно точно различить что изображено на картинке, благодаря сильному контрасту между темными пикселями (задний фон) и светлыми (цифра). Значения пикселей также сильно отличаются, поэтому модели удавалось легко отличить светлые пиксели и по их расположению выбрать верный ответ.
</div> 
