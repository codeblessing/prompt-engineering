# Intro

## Czym w ogóle jest prompt?

Prompt to nic innego jak dane odebrane od użytkownika.
O ile tradycyjnie w informatycznym świecie określenie to istnieje od dawna, to dopiero w kontekście 
modeli językowych jego zastosowanie zostało rozpowszechnione i nieco rozszerzono jego znaczenie.

W przypadku LLM prompt jest zapytaniem zadawanym modelowi przez użytkownika, rozszerzonym o kontekst danych i oczekiwanych zachowań.

## Prompt engineering. A po co to komu?

Ze względu na budowę i działanie modeli sieci neuronowych (patrz [rozdział 4](./chapter_4.md)) uzyskanie
oczekiwanej odpowiedzi od modelu językowego nie jest tak proste jak mogłoby się wydawać.
Aby zmaksymalizować szanse na uzyskanie pożądanych odpowiedzi trzeba zrozumieć procesy stojące za udzielaniem odpowiedzi
i w odpowiedni sposób zadać pytanie. (Swoją drogą, do czego to doszło, że wykorzystujemy socjotechniki względem komputerów...)

Prompt engineering jest więc niczym innym jak próbą opanowania chaosu nazywanego sztuczną inteligencją w celu uzyskania odpowiedzi
wyglądających na poprawne (powiązany XKCD poniżej). \
Nie jest to żadna konkretna technologia czy metodologia gwarantująca poprawne wyniki,
a raczej zestaw wskazówek i wzorców, które w większości przypadków pomagają osiągnąć pożądany rezultat.

![](https://imgs.xkcd.com/comics/machine_learning.png)