# TLHomeWork3

![изображение](https://github.com/Veser4/TLHomeWork3/assets/109903763/a9474972-de56-4663-b024-84f1a9ecbc69)

https://drive.google.com/file/d/11s0LsQ1bnlquiz9npMcLvslV853GYjsj/view?usp=sharing


База данных содержит информацию(таблицы) о герое, его характеристиках, расах, классах и предметах. 
# Описание
1. Герой(Hero):
  1.1. Имя(FirstName)
  2. Фамилия(LastName)
  3. Характеристики(FeatureId)
  4. Класс(ClassId)
  5. Раса(Raceid)
2. Предмет(Thing):
  1. Название(Name)
  2. Цена(Cost)
  3. ID героя к которому прикрпелён предмет(HeroId)
3. Класс(Class):
  1. Название(Name)
4. Раса(Race):
  1. Название(Name)
5. Характеристики(Feature):
  1. Интеллект(Intelligence)
  2. Ловкость(Agility)
  3. Сила(Strength)
   
# Связи:
1. Таблица Герой(Hero):
  1 С Классом(Class), как множество к одному, через ClassId
  2. С Расой(Race), как множество к одному, через ClassId
  3. С Характеристиками(Feature), как один к одному, через FeatureId
2. Таблица Предмет(Thing):
  1. C Героем(Hero), как один к одному, через HeroId
