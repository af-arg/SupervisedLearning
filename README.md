# SupervisedLearning

**Цель исследования**: Факторы активности покупателей в интернет-магазине «В один клик» 

Интернет-магазин «В один клик» продаёт разные товары: для детей, для дома, мелкую бытовую технику, косметику и даже продукты. Отчёт магазина за прошлый период показал, что активность покупателей начала снижаться. Привлекать новых клиентов уже не так эффективно: о магазине и так знает большая часть целевой аудитории. Возможный выход — удерживать активность постоянных клиентов. Сделать это можно с помощью персонализированных предложений.

**Цель исследования** - разработать решение, которое позволит персонализировать предложения постоянным клиентам, чтобы увеличить их покупательскую активность.

**Задачи:** 
1. Выполнить предобработку данных;
2. Отобрать наблюдения для построения модели;
3. Разработать модель, предсказывающую вероятность снижения покупательской активности;
4. Разработать рекомендации по повышению покупательской активности для одного из выделенных сегментов.

**Имеющиеся данные:** 
1. Данные о поведении покупателя на сайте, о коммуникациях с покупателем и его продуктовом поведении;
2. Данные о выручке, которую получает магазин с покупателя;
3. Данные о времени, которое покупатель провёл на сайте в течение периода;
4. Данные о среднемесячной прибыли покупателя за последние 3 месяца.

**Использованные модели:**
1. Классификатор, основанный на методе K ближайших соседей;
2. Классификатор, основанный на модели дерева решений;
3. Классификатор, основанный на методе опорных веторов;
4. Логистическая регрессия.

**Результат:**
Лучший результат на тестовой выборке показала модель решающего дерева с ROC-AUC в ~0.865
