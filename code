import sys
import subprocess
import time
import random
 
#Валюта
money = 10000
dollar = 0
#btc = 0
 
#Рейтинг и тд.
rate = 0
 
#Характеристики
heath = 100
kolbaska = 100
sexy = 100
 
alert1 = ""
alert2 = ""
alert3 = ""
 
#Читы
youcheat   = ""
smallmoney = "swallmoney" #+ 5000 Рублей
bigmoney   = "givemoney"  #+ 1000 Долларов
fullstat   = "newlife"    #+ 100% Потребностям
bigboss    = "bigboss"    #+ 5000 Рейтинга
 
 
#Other
lvl = "Легко"
 
lvl1 = "Легко"
lvl2 = "Нормально"
lvl3 = "Сложно"
 
lvl1z = "1"
lvl2z = "2"
lvl3z = "3"
 
stimer = 0
stimertype = 0
ztimer1 = 30
sctimer = 0
course = 0
good = 0
 
sc1= 0
sc2= 0
sc3= 0
sc4= 0
sc5= 0
sc6= 0
sc7= 0
sc8= 0
sc9= 0
sc10= 0
 
while(True):
   
    print("Симулятор Савельева 1.0")
    print("1. Начать игру")
    print("2. Настройки")
    print("3. Помощь")
    print("4. Выход")
    StartS = input("> ")
    subprocess.call('clear', shell=True)
    st1 = "1"
    st2 = "2"# str
    st3 = "3"
    st4 = "4"
   
    if(StartS == st1):
        while(st1):
            rnd = random.randint (0,1)# Здоровье
            rnd1 = random.randint(2,15)# Голод
            rnd2 = random.randint(3,15)# Влечение
 
            rate = rate + 1
            if(kolbaska+rnd1 < 0):
                kolbaska = 0
 
            if(sexy+rnd2 < 0):
                sexy = 0
 
            if(kolbaska <= 0):
                rnds1 = random.randint (1,9)# Здоровье
                rnds2 = random.randint(5,10)# Влечение
                sexy = sexy - rnds1
                heath = heath - rnds2
 
            ztimer1 = ztimer1 + 1#курс доллара
            if(ztimer1 > 30):
                rndh5 = random.randint(15,45)#Случайное значение
                ztimer1 = 0
                course = rndh5
            stimer = stimer + 1
            if(stimer > stimertype):
                heath = heath - rnd
                if(kolbaska > 0):
                    kolbaska = kolbaska - rnd1
                if(sexy > 0):
                    sexy = sexy - rnd2
 
            sctimer = sctimer + 1
            if(sc1 == 1):
                if(sctimer == 3):
                    money = money + 2
                    sctimer = 0
            if(sc2 == 1):
                if(scimer == 3):
                    money = money + 5
                    sctimer = 0
            if(sc3 == 1):
                if(sctimer == 3):
                    money = money + 20
                    sctimer = 0
            if(sc4 == 1):
                if(sctimer == 3):
                    money = money + 50
                    sctimer = 0
            if(sc5 == 1):
                if(sctimer == 3):
                    money = money + 200
                    sctimer = 0
            if(sc6 == 1):
                if(sctimer == 3):
                    dollar = dollar + 6
                    sctimer = 0
 
            if(sc7 == 1):
                if(sctimer == 3):
                    dollar = dollar + 10
                    sctimer = 0
 
            if(sc8 == 1):
                if(sctimer == 3):
                    heath = heath + 2
                    kolbasa = kolbasa + 2
                    sexy = sexy + 2
                    sctimer = 0
 
 
 
           
               
            if(heath < 0):
                print("Вы погибли, нельзя что бы здоровье падало к 0%")
                print("Игра окончена")
                sys.exit(0)
            if(kolbaska < 0):
                print("Внимание! Вы голодаете, уровень здоровья падает!")
            if(sexy < 0):
                print("Внимание! Вам нужен секс, вы можете стать импотентом!")
                print("Уровень голода и здоровья падает!")
           
            if(heath < 30):
                alert1 = " <-- Внимание!"
            if(kolbaska < 35):
                alert2 = " <-- Внимание!"
            if(sexy < 30):
                alert3 = " <-- Внимание!"
 
            if(heath > 30):
                alert1 = ""
            if(kolbaska > 35):
                alert2 = ""
            if(sexy > 30):
                alert3 = ""
               
           
            print("___Валюта:_____________")
            print("Рубли:     "+str(money))
            print("Доллары:   "+str(dollar))
            #print("Биткоины:  "+str(btc))
            print("___Потребности:________")
            print("Здоровье:  "+str(heath)+"%"+str(alert1))
            print("Насыщение: "+str(kolbaska)+"%"+str(alert2))
            print("Влечение:  "+str(sexy)+"%"+str(alert3))
            print("_______________________")
            print("Рейтинг:   "+str(rate))
            print(youcheat)
            print("---------- Карта города ----------")
            print("1. Магазин Колбаса")
            print("2. Библиотека")
            print("3. Проститутки")
            print("4. Работа")
            if(money > 10000):
                print("5. Банк")
            if(rate > 1000):
                print("6. Магазин Sciense ")
            if(rate > 10000):
                print("7. Телевиденье")
            if(rate > 50000):
                print("8. НИИ Морфологии Человека")
               
            tex = input("> ")
            subprocess.call('clear', shell=True)
            if(tex == str("1")):
                subprocess.call('clear', shell=True)
                print("--- Магазин колбаса ---")
                print("1. Доширак  (50   Руб.) (10-30%)(Портит здоровье)")
                print("2. Хлеб     (100  Руб.) (10-19%)")
                print("3. Шаурма   (350  Руб.) (20-40%)(Шанс отравиться 5%)")
                print("4. Пельмени (800  Руб.) (60-90%)(Может исцелить)")
                print("5. Лобстер  (2000 Руб.) (100%  )(+60% Здоровья)")
                print("6. Колбаска (5000 Руб.) (100%  )(Полностью исцеляет)")
                tex1 = input("> ")
                subprocess.call('clear', shell=True)
                if(tex1 == str("1")):
                    if(money > 50):#Проверка достаточно ли денег              
                        money = money - 50 #Трата денег
                        rndh = random.randint(10,30)#Случайное значение
                        rndh1 = random.randint(1,9)#Случайное значение
                        kolbaska = kolbaska + rndh
                        print("Бичпакет.. Не голодный и всего 50 рублей!")
                        heath = heath - rndh1
                        if(kolbaska+rndh > 100):
                            kolbaska = 100
                           
                if(tex1 == str("2")):
                    if(money > 100):#Проверка достаточно ли денег              
                        money = money - 100 #Трата денег
                        rndh = random.randint(10,19)#Случайное значение
                        kolbaska = kolbaska + rndh
                        print("Ну и что, что хлеб? За то не голодный!")
                        if(kolbaska+rndh > 100):
                            kolbaska = 100        
                   
                if(tex1 == str("3")):
                    if(money > 350):#Проверка достаточно ли денег              
                        money = money - 350 #Трата денег
                        rndh = random.randint(20,40)#Случайное значение
                        rndh1 = random.randint(1,10)#Случайное значение(яд)
                        kolbaska = kolbaska + rndh
                        print("Вкусная и не дорогая!")
                        if(rndh1 == 5):
                            rndh = random.randint(2,10)#Случайное значение
                            heath = heath -  rndh
                            print("Вы отравились шаурмой =("+" Вы потеряли: "+str(rndh)+"HP")
                        if(kolbaska+rndh > 100):
                            kolbaska = 100
                           
                if(tex1 == str("4")):
                    if(money > 800):#Проверка достаточно ли денег              
                        money = money - 800 #Трата денег
                        rndh = random.randint(60,90)#Случайное значение
                        rndh1 = random.randint(2,15)#Случайное значение(лечение)
                        heath = heath + rndh1
                        print("Пельмени востановили вам: "+str(rndh1)+"HP")
                        if(rndh1 == 5):
                            heath = heath + 10
                            print("Супер-Исцеление пельменей дополнительно: +10 HP")
                        kolbaska = kolbaska + rndh
                        if(kolbaska+rndh > 100):
                            kolbaska = 100
                        if(heath+rndh1 > 100):
                            heath = 100      
 
 
                if(tex1 == str("5")):
                    if(money > 2000):#Проверка достаточно ли денег              
                        money = money - 2000 #Трата денег
                        kolbaska = kolbaska + 100
                        heath = heath + 60
                        print("Вы прекрасно поели и стали чувствовать себя хорошо.")
                        if(kolbaska > 100):
                            kolbaska = 100  
                        if(heath > 100):
                            heath = 100
                           
                if(tex1 == str("6")):
                    if(money > 5000):#Проверка достаточно ли денег              
                        money = money - 5000 #Трата денег
                        kolbaska = kolbaska + 100
                        heath = heath + 100
                        print("Шикарная колбаса, чувствую себя богом!")
                        if(kolbaska > 100):
                            kolbaska = 100
                        if(heath > 100):
                            heath = 100    
                    else:
                        print("Недостаточно денег друг!")
 
            if(tex == str("2")):
                subprocess.call('clear', shell=True)
               
                print("--- Библиотека ---")
                print('1. Книга "Подсознание человека"')
                print('2. Библия')
                print("3. Комиксы спайдермэн")
                print("4. Общая биология человека")
                print("5. Нейроморфология для даунов")
                print("6. Психология человека")
                print("7. Нищета мозга")
                print("8. Самооборона по технике спецназа")
                print("9. Лучшие кулинарные рецепты 2002")
                print('10.Адольф Гитлер "Еврейские мудрости"')
                tex2 = input("> ")
                subprocess.call('clear', shell=True)
                rate = rate + 5
                if(tex2 == str("4")):
                    rate = rate + 5
                if(tex2 == str("5")):
                    rate = rate + 10
                if(tex2 == str("7")):
                    rate = rate + 15
                 
               
               
            if(tex == str("3")):
                subprocess.call('clear', shell=True)
                print('--- Салон "Сладкая киска" ---')
                print('1. Вероника         (500  Руб.)')
                print('2. Анастасия        (1000 Руб.)')
                print('3. Ирина            (2500 Руб.)')
                print('4. Александра       (5000 Руб.)')
                #print('5. Александра       (1000 Дол.)')
                #print('6. Наталья Ивановна (2500 Дол.)')
                tex3 = input("> ")
                subprocess.call('clear', shell=True)
                if(tex3 == str("1")):
                    if(money > 500):
                        money = money - 500
                        sexy = sexy + 40
                        if(sexy > 100):
                            sexy = 100
                        print("Ты отлично отдохнул, всего - то за 500 руб.")
               
                if(tex3 == str("2")):
                    if(money > 1000):
                        money = money - 1000
                        sexy = sexy + 60
                        heath = heath - 4
                        if(sexy > 100):
                            sexy = 100
                        print("Ты отлично отдохнул, всего - то за 1000 руб.")
                   
                if(tex3 == str("3")):
                    if(money > 2500):
                        money = money - 2500
                        sexy = sexy + 80
                        if(sexy > 100):
                            sexy = 100
                        print("Ты отлично отдохнул, всего - то за 2500 руб.")
                   
                if(tex3 == str("4")):
                    if(money > 5000):
                        money = money - 5000
                        sexy = sexy + 90
                        if(sexy > 100):
                            sexy = 100
                        print("Ты шикарно отдохнул, за 5000 руб.")
                   
                if(money < 500):
                    print("Не достаточно денег!")
                                   
            if(tex == str("4")):
                subprocess.call('clear', shell=True)
                print("--- Работа ---")
                print("1. Сидеть возле храма     (+200  руб.)")
                print("2. Петь в метро           (+350  руб.)")
                print("3. Носить кирпичи         (+600  руб.)")
                if(rate > 1000):
                    print("4. Торговать на базаре    (+1000  руб.)")
                    print("5. Продавать вейпы        (+1200  руб.)")
                    print("6. Работать в магазине    (+2000 руб.)")#Не пошел в шарагу пишу код ^__^
                if(rate > 5000):
                    print("7. Обучать пикапу         (+2500 руб.)")
                    print("8. Работать консультантом (+3000 руб.)")
                    print("9. Работать менеджером    (+5000 руб.)")
                if(rate > 10000):
                    print("10. Работать инженером     (+10 000 руб.)")
                    print("11. Работать попом         (+50 000 руб.)")
                    print("12. Быть президентом       (+5000 дол.  )")
 
               
                tex4 = input("> ")
                subprocess.call('clear', shell=True)
 
                if(tex4 == str("1")):
                    money = money + 200
                   
                if(tex4 == str("2")):
                    money = money + 350
                    rate = rate - 1
                if(tex4 == str("3")):
                    money = money + 600
                    rndh = random.randint(1,4)#Случайное значение
                    heath = heath - rndh
                if(tex4 == str("4")):
                    if(rate > 1000):
                        money = money + 1000
                if(tex4 == str("5")):
                    if(rate > 1000):
                        money = money + 1200
                if(tex4 == str("6")):
                    if(rate > 1000):
                        money = money + 2000
                if(tex4 == str("7")):
                    if(rate > 5000):
                        money = money + 2500
                if(tex4 == str("8")):
                    if(rate > 5000):
                        money = money + 3000
                if(tex4 == str("9")):
                    if(rate > 5000):
                        money = money + 5000
                if(tex4 == str("10")):
                    if(rate > 10000):
                        money = money + 10000
                if(tex4 == str("11")):
                    if(rate > 10000):
                        money = money + 50000
                if(tex4 == str("12")):
                    if(rate > 10000):
                        dollar = dollar + 5000
                       
            if(tex == str("5")):
                if(money > 10000):
                    subprocess.call('clear', shell=True)
                    print("--- Банк ---")
                    print("1. Обменять руб. на дол.")
                    print("2. Обменять дол. на руб.")
                    print("0. Отменить")
                    #print("3. Купить биткоин")
                   
                    tex5 = input("> ")
                    if(tex5 == str("1")):
                        subprocess.call('clear', shell=True)
                        print("-Продать рубли, купить доллар-")
                        print("")
                        print("Рубли:     "+str(money))
                        print("Доллары:   "+str(dollar))
                        print("")
                        print("Курс доллара за 1 дол.: "+str(rndh5))
                        print("Введите количество для продажи, 0 для отмены")
                        coin = input("Купить: ")
                        subprocess.call('clear', shell=True)
                        coin1 = int(coin) * rndh5
                        if(coin1 < money):
                            dollar = dollar + int(coin)
                            money = money - coin1
                           
                        else:
                            print("Недостаточно рублей!")
                            subprocess.call('clear', shell=True)
 
                    if(tex5 == str("2")):
                        subprocess.call('clear', shell=True)
                        print("-Продать доллар, купить рубли-")
                        print("")
                        print("Рубли:     "+str(money))
                        print("Доллары:   "+str(dollar))
                        print("")
                        print("Курс доллара за 1 дол.: "+str(rndh5))
                        print("Введите количество для продажи, 0 для отмены")
                        coin = input("Продать: ")
                        subprocess.call('clear', shell=True)
                        coin1 = int(coin) * rndh5
                        if(int(coin) <= dollar):
                            dollar = dollar - int(coin)
                            money = money + coin1
                        else:
                            print("Недостаточно долларов!")
 
                    #if(tex5 == str("3")):
                    #    print("-Купить биткоины-")
                    #    print("Цена 1 btc : 100 Долларов")
                    #    print("Введите количество для покупки, 0 для отмены")
                    #    coin = input("Купить: ")
                    #    coin1 = int(coin) * 100
                    #    if(coin1 <= dollar):
                    #        dollar = dollar - coin1
                    #        btc = btc + int(coin)
                    #    else:
                    #        print("Недостаточно долларов!")
                     
 
            if(tex == str("6")):
                if(rate > 1000):
                    print("--- Магазин Sciense ---")
                    print("1. Книги С.В. Савельева           (2000    Руб.)")
                    print('2. Книга "Основы гистологии"      (5000    Руб.)')
                    print('3. Микроскоп "Gart I"             (20 000  Руб.)')
                    print('4. Микроскоп "Gart II"            (50 000  Руб.)')
                    print('5. Микроскоп "Nano X              (200 000 Руб.)')#Снова остался дома)) Допишу УЖЕ СЕГОДНЯ ИГРУ
                    print('6. Подобытная макака              (6000    Дол.)')
                    print('7. Нелегальный подопытный человек (10 000  Дол.)')#Привет владу!) Мой мега говнокод почти готов))
                    print('8. Лаборант Макс Островский       (Бесплатно   )')
                    print('9. Прототип томографа             (200 000 Дол.)')
                    if(good == 100):
                        print('10. Томограф высокого разрешения  (2 000 000 Дол.)')
 
                    tex6 = input("> ")
                   
                    if(tex6 == str("1")):
                        if(money >= 2000):
                            sc1 = 1
                            print("Куплены книги С.В. Савельева! Бонус +2 Руб.")
                    if(tex6 == str("2")):
                        if(money >= 5000):
                            sc2 = 1
                            print("Куплена книга по гистологии! Бонус +5 Руб.")
                    if(tex6 == str("3")):
                        if(money >= 20000):
                            sc3 = 1
                            print("Куплен микроскоп! Бонус +20 Руб.")
                    if(tex6 == str("4")):
                        if(money >= 50000):
                            sc4 = 1
                            print("Куплен более мощный микроскоп! Бонус +50 Руб.")
                    if(tex6 == str("5")):
                        if(money >= 200000):
                            sc5 = 1
                            print("Куплен самый мощный микроскоп! Бонус +200 Руб.")
                    if(tex6 == str("6")):
                        if(dollar >= 6000):
                            sc6 = 1
                            print("Подопытный макака куплен! Бонус +6 Дол.")
                    if(tex6 == str("7")):
                        if(dollar >= 10000):
                            sc7 = 1
                            print("Вам удалось достать подопытного человека! Бонус +10 Дол.")
                    if(tex6 == str("8")):
                        print("Бесплатный лаборант Макс Островский, получен! Бонус +2% Ко всему")
                        sc8 = 1
                    if(tex6 == str("9")):
                        if(dollar >= 200000):
                            sc9 = 1
                            print("Прототип томографа куплен! Начните исследование в НИИ")
                    if(tex6 == str("10")):
                        if(good == 100):
                            if(dollar >= 2000000):
                                sc10 = 1
                                print("Томограф высоко разрешения, куплен! Ключевая цель игры достигнута!")
                    else:
                        print("Недостаточно денег!")
                       
            if(tex == str("7")):
                if(rate > 10000):
                    print("--- Телевиденье ---")
                    print('1. Поехать на шоу "Новинки психологии" (5000    Руб.)')
                    print('2. Поехать на шоу "Пусть говорят"      (20 000  Руб.)')
                    print("3. Поехать на радио маяк               (50 000  Руб.)")# Да почему же так сложно заставить себя!
                    print('4. Поехать на шоу "Самый хитрый"       (100 000 Руб.)')# Моя лимбика чертова.. Нечего не хочет
                    print("5. Поехать на конференцию психологов   (250 000 Руб.)")
 
                    tex7 = input("> ")
 
                    if(tex7 == str("1")):
                        if(money >= 5000):
                            print("Вы узнали много нового об психологии!")
                            rate = rate + 500
                    if(tex7 == str("2")):
                        if(money >= 20000):
                            print("Вы отлично поскандалили, и засветились в телике!")
                            rate = rate + 2500
                    if(tex7 == str("3")):
                        if(money >= 50000):
                            print("Вы ответили на вопросы делетантов, ваш рейтинг вырос!")
                            rate = rate + 6500
                    if(tex7 == str("4")):
                        if(money >= 100000):
                            print("Вы показали соплякам, кто тут самый хитрый!")
                            rate = rate + 15000
                    if(tex7 == str("5")):    
                        if(money >= 250000):
                            print("Вы уделали всех психологов, рейтинг вырос!")
                            rate = rate + 50000
            if(tex == str("8")):
                if(rate > 50000):
                    print("--- НИИ Морфологии человека ---")
                    print("Прогресс иследования: "+str(good)+"%")
                    print("1. Работать нейроморфологом (+ 25 000 Руб)")#Ааа... Не ужели я доделал эту игру Т___Т
                    if(sc9 == 1):
                        print("2. Проводить иследование")
 
                    tex9 = input("> ")    
 
                    if(tex9 == str("1")):
                        money = money + 25000
 
                    if(tex9 == str("2")):
                        if(sc9 == 1):
                            good = good + 1
                        if(good >= 100):
                            good = 100
            if(tex == str("smallmoney")):
                money = money + 5000
                subprocess.call('clear', shell=True)
                print("Чит-код активирован!")
                print("+5000 Рублей")
                youcheat = str("Ты читер!")
 
 
            if(tex == str("bigmoney")):
                dollar = dollar + 1000
                subprocess.call('clear', shell=True)
                print("Чит-код активирован!")
                print("+1000 Долларов")
                youcheat = str("Ты читер!")
 
            if(tex == str("fullstat")):
                heath = 100
                kolbaska = 100
                sexy = 100
                subprocess.call('clear', shell=True)
                print("Чит-код активирован!")
                print("Все потребности востановлены")
                youcheat = str("Ты читер!")    
 
            if(tex == str("bigboss")):
                rate = rate + 5000
                subprocess.call('clear', shell=True)
                print("Чит-код активирован!")
                print("+5000 Рейтинга")
                youcheat = str("Ты читер!")
               
    elif(StartS == st2):
        print("Настройки игры:")
        print("Сложность: "+str(lvl))
        print("1. Легко")
        print("2. Нормально")
        print("3. Сложно")
        lvls = input("> ")
        subprocess.call('clear', shell=True)
        if(lvls == lvl1z):
            lvl = lvl1
            heath = 100
            kolbaska = 100
            sexy = 100
            money = 10000
            stimertype = 3
        if(lvls == lvl2z):
            lvl = lvl2
            heath = 80
            kolbaska = 60
            sexy = 90
            money = 5000
            stimertype = 2
        if(lvls == lvl3z):
            lvl = lvl3
            heath = 50
            kolbaska = 40
            sexy = 40
            money = 1000
            stimertype = 1
    elif(StartS == st3):
        subprocess.call('clear', shell=True)
        print("")
        print("---Помощь по игре---")
        print("")
        print("Это текстовый квест, главная задача купить томограф высокого разрешения")
        print("Для этого нужно попасть в НИИ Морфологии Человека (Нужно 50000 рейтинга)")
        print("После нужно собрать 200 000 долларов и купить прототип томографа")
        print("Доллары можно заработать или обменять рубли в банке")
        print("После покупки прототипа, его нужно исследовать в НИИ Морфологии Человека")
        print("Нужно получить результаты исследования, которые должны быть равны 100%")
        print("Далее собери 2 000 000 Долларов, на настоящий томограф высокого разреения")
        print("После покупки томографа откроется уникальная локация, дойди и узнаешь =)")
        print("")
        print("Создатель SS_Richter (Игра создана по фану, в ней горы говнокода и костылей)")
        print("")
        enteer = input("Press Enter")
        subprocess.call('clear', shell=True)
 
       
    elif(StartS == st4):
        subprocess.call('clear', shell=True)
        print("Выход из игры..")
        sys.exit(0)
 
    else:
        subprocess.call('clear', shell=True)
        print("Не корректный ввод!")
        print("Вводите только цифры!")
        time.sleep(3)
        subprocess.call('clear', shell=True)
