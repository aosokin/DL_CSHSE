# Материалы курса "Глубинное обучение", прочитанного на [ФКН ВШЭ](https://cs.hse.ru/) осенью 2020г.

## Преподаватели
Лектор: [Антон Осокин](https://aosokin.github.io/)

Семинаристы: [Ирина Сапарина](https://github.com/saparina), [Максим Рябинин](https://www.hse.ru/staff/mryabinin)

[О курсе](lectures/DL20-fall-about.pdf): программа, схема оценки

## Программа курса
* Введение (лекция 1: [слайды](lectures/DL20-fall-lecture1-intro.pdf), [видео](https://youtu.be/k3QZU5a1oRA); [семинар 1](seminars/seminar1/DL20-fall-seminar1.ipynb))
* Основные концепции
  - Автоматическое дифференцирование (лекция 2: [слайды](lectures/DL20-fall-lecture2-backprop.pdf), [видео](https://youtu.be/cKMaEpf4MeU); [семинар 2](seminars/seminar2/DL20-fall-seminar2.ipynb))
  - Виды архитектур (лекция 3: [слайды](lectures/DL20-fall-lecture3-models.pdf), [видео](https://youtu.be/Uim4xLhXjRE); [семинар 3](seminars/seminar3/DL20_fall_seminar3.ipynb))
  - Обучение и регуляризация (лекция 4: [слайды](lectures/DL20-fall-lecture4-training.pdf), [видео](https://youtu.be/kE3AicLd5KE); [семинар 4](seminars/seminar4/DL20_fall_seminar4.ipynb))
  - Best practices (лекция 5: [слайды](lectures/DL20-fall-lecture5-bestpractices.pdf); [семинар 5](seminars/seminar5/looking_for_bugs.ipynb))
* Продвинутые темы
  - Применения для обработки языка (лекция 6: [слайды](lectures/DL20-fall-lecture6-deepnlp.pdf), [видео](https://youtu.be/ID_sIs_dEbE); [семинар 6](seminars/seminar6/DL20_fall_seminar6.ipynb))
  - Применения в компьютерном зрении (лекция 7: [слайды](lectures/DL20-fall-lecture7-deepvision.pdf), [видео](https://youtu.be/d5r6k1czEys); [семинар 7](seminars/seminar7/DL20_fall_seminar7.ipynb))
  - Adversarial X (лекция 8: [слайды](lectures/DL20-fall-lecture8-adversarialX.pdf), [видео](https://youtu.be/hCR8iue9yjM); [семинар 8](seminars/seminar8/DL20_fall_seminar8.ipynb))
  - Вероятностные модели
  - Дифференцируемое программирование
  - Недифференцируемые модели
  - Ускорение и внедрение моделей

## Disclaimer
Курс "Глубинное обучение" разрабатывался не как онлайн-курс, а как классический университетский курс с лекциями и семинарами.
Тем не менее, мы решили выложить все материалы в открытый доступ под [лицензией Apache 2.0](../LICENSE) на случай если они кому-то будут полезны.
Единственная просьба, **пожалуйста, не выкладывайте решения семинаров в открытый доступ!** 
  
## Материалы
Все материалы курса на **русском** языке!

Выложены следующие материалы:
* [Презентации лекций](lectures)
* [Jupyter ноутбуки семинаров](seminars) 

**Пожалуйста, не выкладывайте решения семинаров в открытый доступ!** Мы хотим переиспользовать материалы на следующих итерациях курса.
 
## Технические требования семинаров
Все семинары разрабатывались для выполнения на обычных ноутбуках, т.е., не требуют значительных вычислительных ресурсов (в частности не требуют GPU). Тем не менее требования к железу ненулевые, и на некоторых компьютерах все работает очень медленно. Бесплатные вычислительные ресурсы (в том числе с GPU) можно получить, например, на сайте https://colab.research.google.com.

В рамках курса мы использовали python 3.6, pytorch v1.6.0, torchvision v0.7.0. Поддержка других библиотек и других версий python и pytorch не осуществлялась.
 
Для настройки библиотек мы рекомендуем использовать менеджер пакетов [Anaconda](https://www.anaconda.com/) (есть для Linux, OS X, Windows). Для установки в Linux, OS X и Windows смотрите инструкции на сайте http://pytorch.org/. 
 
