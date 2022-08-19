# Space Invaders by Grigory Plakhotnikov

Space Invaders - классическая аркадная видеоигра, цель которой - отразить отаки спускающихся с неба пришельцев. Эта версия была разработана в качестве финального проекта для курса How to Code: Simple Data, который предлагается Университетом Британской Колумбии через платформу edX. Код написан на языке Racket.

Space Invaders is a classic arcade game. The goal is to defeat wave after wave of descending aliens with a horizontally moving laser to earn as many points as possible. This version was made as a final project for How to Code: Simple Data course offered by University of British Columbia via edX. Programming language: Racket.

## Видеопрезентация / Video Presentation
https://www.youtube.com/watch?v=2u3IOFVctPw

## Особенности / Features

- Запуск из виртуального окружения Racket
- Случайная позиция и направление пришельцев. Направление меняется на противоположное, когда они ударяются о стену
- Управление позицией танка кнопками "вправо" и "влево", "пробел" для запуска ракеты
- Когда любой из пришельцев достигает земли, игра прекращается
----------
- Can be executet in Racket environment
- Invaders appear randomly along the top of the screen. When they hit a wall they  bounce off and continue in the other direction
- The tank moves right and left at the bottom of the screen when you press the arrow keys. It fires missiles straight up from its current position when you press the space bar
- When an invader reaches the bottom of the screen, the game is over

## Стек технологий / Tech

- [Racket](https://racket-lang.org/) - a modern dialect of Lisp and a descendant of Scheme

## Как запустить проект / Installation

Откройте файл space-invaders.rkt в программе DrRacket. Нажмите Run и запустите главную функцию командой (main G0) в консоли.
```sh
(main G0)
```
Open the file space-invaders.rkt in DrRacket. Click Run and execute the main function by typing (main G0) in the console.

## О разработчике / Development
(с) Grigory Plakhotnikov