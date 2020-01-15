# Course_Project_AI_Severstal_Steel_Defect_Detection
This course work is devoted to solving the problem of finding defects on a sheet of metals


This section describes the steps you need to take to complete the training and testing process
  Отже, як користуватись всім тим, що тут є:
    1. Вам потрібно скачати дані з https://www.kaggle.com/c/severstal-steel-defect-detection/data та замінити їх замість фолдеру severstal-steel-defect-detection
    2. Вам потрібно скачати натреновані ваги - model.pth, якщо ви захочете перевірити мою, вже готову реалізацію та помістити цей файл у input/unet-starter-model-file
    3.  Тепере перед тим як тренувати нейронну мережу вам потрібно завантажити всі необхідні бібліотеки via pip install -r requirements.txt
    4. І фінальний крок ви повнні вибрати, чи ви хочете і тренувати і тестувати нейронну мережу, чи лише тестувати.
        4.1 Якщо ви хочете тестувати:
              1. Запустіть файл Test.ipynb
        4.2 Якщо ви хочете і тренувати і тестувати:
              У вас є дві опції виконувати це все одним файлом або двома (при декомпозиції краще розуміється суть)
              4.2.1. Якщо ви хочете одним файлом - запустіть YaroslavBoiko_Main.ipynb
              4.2.2.  Якщо ви хочете двома файлами - запустіть спершу Train.ipynb, а тоді тест
    5.Отримані результати ви можете перевірити на кегл.
