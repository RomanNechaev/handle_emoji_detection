# Интерактивное приложение для распознавания жестов на основе эмодзи из набора «Рука с одним пальцем»

Для распознавания жестов на основе ключевых точек используется пакет из **MediaPipe** (https://ai.google.dev/edge/mediapipe/solutions/vision/hand_landmarker).

## Интерактивное взаимодействие с пользователем

Пользователи могут зарабатывать бонусные очки за демонстрацию жестов на основе эмодзи из набора https://symbl.cc/ru/emoji/people-and-body/hand-single-finger/. Эти очки отображаются в реальном времени на экране.

## Пайплайн работы приложения
![image](https://github.com/user-attachments/assets/755f312f-2295-4b3d-bcf0-47c46815749a)

Нейронка обучалась на датасете, сгенерированным вручную посредством захвата `правильных` позиций руки посредством того же mediapipe api.
Датасет лежит в `keypoint.csv`.

## Пример работы
<img width="1278" alt="hand_example" src="https://github.com/user-attachments/assets/7562a767-e97c-42a5-9b48-9294a65effc5">

## За основу взят репозиторий  - https://github.com/kinivi/hand-gesture-recognition-mediapipe/tree/main
