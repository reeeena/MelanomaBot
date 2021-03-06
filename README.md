# MelanomaBot
Телеграм-бот для повышения осведомленности людей о меланоме

## Цель бота: 
Повышение осведомленности о таком заболевании как меланома - наиболее опасной разновидности рака кожи, о мерах предосторожности, которые нужно соблюдать, чтобы снизить риск возникновения данного заболевания. Помимо этого целью является также оказание пользователю помощи в определении, стоит ли проконсультироваться со специалистом по поводу беспокоящего его родимого пятна.

## Функционал:
* Проверка родимого пятна по фотографии: пользователь загружает фотографию родимого пятна, нейросеть, обученная на 2637 изображениях определяет, есть ли поводы для беспокойства. Если нейросеть определила пятно как безопасное, бот сообщает, что скорее всего поводов для беспокойства нет и предлагает обсудить симптомы в формате теста. Если же нейросеть определила пятно как злокачественное, пользователь получает рекомендацию обратиться к специалисту и предложение найти клинику поблизости. 
* Функция /melanoma: Бот предоставляет текстовую информацию о заболевании
* Функция /risk: Бот предоставляет текстовую информацию о факторах риска  заболевания.
* Функция /precautions: Бот предоставляет текстовую информацию о мерах предосторожности, которые могут помочь снизить вероятность появления и развития заболевания.
* Функция /test: Бот задает пользователю последовательные вопросы о характеристиках его родимого пятна. Если ни один из опасных факторов не обнаружен, бот отвечает, что поводов для беспокойства нет. Если присутствует хотя бы один подозрительный фактор, пользователь получает рекомендацию обратиться к специалисту и предложение найти клинику поблизости.
* Функция /advice Бот задаёт вопросы в формате теста, ответив на которые, пользователь получает персонализированный совет.
