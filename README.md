# ABCDE
Сравнение Стратегий Разностной Эволюции Для Метода Приближенных Байесовских Вычислений.
_______________________________________________________________________________________
В репозитории реализацию метода приближенного байесовского вычислений с разностной эволюцией и 5 стратегиями мутации в файле "strategies.ipynb".
Датасет: 
- "Х.csv"- набор геномных данных нута, состоящий из 407 генотипов и 6642 маркеров SNP.
- "y.csv" - признак, масса тысячи семян (TSW).

В папке "Results and visualization files":
Визуализация: для построения графиков эволюции гиперпараметров и значений RMSE по популяциям, а также гистограммы TSW в файле "results_visualization.ipynb"
этот файл использует результаты методов которые сохранены в csv-файлах "<strategy>_results.csv"
Информация о популяциях и испытаниях также сохранена в csv-файлах "<strategy>_trials.csv"

