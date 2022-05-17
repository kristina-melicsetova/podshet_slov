# podshet_slov
predlozhenie = str(input())
n = len(predlozhenie)#подсчитываем сколько элементов всписке
slova = 0 #изначальное количество слов
for i in range(0,n-1):
    if predlozhenie[i] != ' ' and predlozhenie[i+1] == ' ' :# если первый элемент буква , а воторой прбел засчитываем слово
        slova +=1
 
print(slova +1) #добавляем посднее слово
