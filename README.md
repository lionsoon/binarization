## Метод бинаризации Оцу

requirements:  
PIL: `pip install Pillow`

Запуск скрипта:  
`pyhton otsu.py Dataset`

### Комментарий

Алгоритм работает не очень хорошо. В первую очередь потому, что порог бинаризации находится глобально. 
Из-за этого блики и тени сильно портят итоговую картинку.  
Существует несколько улучшений алгоритма. Я планирую реализвать 2D метод Оцу для сравнения и допушить его сюда. 

Среднее время работы: `0.037 с/МП`
