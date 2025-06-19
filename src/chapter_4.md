# Incertitudo sola res certa est

## Podstawy działania sieci neuronowych

Za konwersacyjnymi modelami językowymi stoją sieci neuronowe - technologia symulująca działanie ludzkiego mózgu.

Sieci neuronowe są gigantycznymi wielowymiarowymi przestrzeniami tensorowymi, które przyjmują określoną liczbę parametrów wejściowych i zwracają rezultaty, również w postaci tensorów. To co odróżnia sieci neuronowe od zwykłych wielowymiarowych macierzy to mechanizm wstecznej propagacji błędów oraz mechanizmy pamięci gradientów przetwarzania (np. LSTM). Wyżej wymienione mechanizmy pozwalają na uczenie sieci neuronowej, co zmienia tensory wzorców.

Kolejnym, gigantycznym krokiem rozwojowym w sieciach neuronalnych są sieci wnioskujące, wykorzystujące tzw. łańcuch myśli (Chain-of-Thoughts, CoT). Te sieci nie tylko są wytrenowane do wykonywania konkretnych zadań czy udzielania odpowiedzi na podstawie wyuczonych wzorców, ale potrafią dynamicznie wnioskować kolejne kroki na podstawie danych otrzymanych od użytkownika i wyciągniętych z baz wiedzy. Jeśli kogoś interesuje dokładny opis działania tych sieci, to zachęcam do przejrzenia artykułów [w tym poście](https://www.linkedin.com/posts/%C5%82ukasz-musia%C5%82-49b88226b_ai-machinelearning-chainofthought-activity-7332895070301401088-H6xF).

Ze względu na probabilistyczną naturę wyboru tensorów wyjściowych sieci neuronowe są permanentnie niedeterministyczne, a więc nawet dla identycznego zapytania mogą udzielić różnych odpowiedzi. Ze względu na tę własność zapytania do modeli wykorzystujących sieci neuronowe powinny zawierać jak najwięcej informacji, ale powinny pozostawić przestrzeń dla mechanizmów wnioskujących - zbyt precyzyjne zapytanie może owocować nieefektywnością przetwarzania, nie gwarantując przy tym deterministyczności.