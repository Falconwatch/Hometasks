# Readme - Diabets

## **Данные**
В данном проекте 4 файла:  
`diabets/data/raw/diabetes_train_analysis.csv` - датасет для обучения, инфа о здоровье  
`diabets/data/raw/diabetes_train_info.csv` - датасет для обучения, инфа о пациенте    
`diabets/data/raw/diabetes_test_analysis.csv` - датасет для тестирования, инфа о здоровье  
`diabets/data/raw/diabetes_test_info.csv` - датасет для тестирования, инфа о пациенте  

## **Задача**
- **Данные**: таблицы с информацией о пациенте (age,height,weight,gender,cholesterol,gluc,smoke,alco,active,pressure,diabetes,ket), 
id - идентификатор пациента.    
- **Таргет**: колонка `diabetes` - факт наличия диабета у пациента.      
- **Метрика**: `f1_score`.     

## **Задание**
Сделайте команды/скрипты для решения задачи: 1) тюнинг (подбор гиперпараметров и т.п.), если требуется, 2) обучение и 3) предикт.
Каждая команда должна принимать на вход названия файлов для применения и пути для сохранения результатов.  
Так же рекомендуется зафиксировать окружение, использовать конфиги и makefile для примеров и воспроизведения команд.  
PS: обратите внимнаие на mlflow, hydra, poetry
