# Классификация музыки по настроению (MTG‑Jamendo)

Учебный проект по курсу «Искусственный интеллект» (Samsung).  
Реализовано несколько подходов к определению настроения музыкальных треков:

- **Baseline** – логистическая регрессия на усреднённых мел‑спектрограммах
- **VGGish** – transfer learning с предобученной аудиомоделью
- **CNN** – собственная свёрточная сеть на мел‑спектрограммах
- **CatBoost**  – градиентный бустинг на усреднённых мел‑спектрограммах
- **CatBoost (статья)** – CatBoost + изотоническая калибровка (https://na-journal.ru/6-2024-informacionnye-tekhnologii/13295-klassifikaciya-muzyki-po-nastroeniyu-s-pomoshchyu-algoritmov-mashinnogo-obucheniya)

