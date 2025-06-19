# Zacznij od Bacha...

### ... czyli podstawowe zasady tworzenia zapytań

Zanim przejdziemy do praktyki należy jeszcze powiedzieć kilka słów o modelach językowych, którymi się zajmiemy.

Modele językowe możemy podzielić na kilka klas związanych z ich działaniem.
Podstawowym podziałem będzie podział na modele uzupełniające i modele instrukcyjne.
Modele uzupełniające (Base LLMs/Predictive LLMs) nie będziemy się zajmować, ponieważ są to zasadniczo wielkie łańcuchy Markova i dość ciężko je nawet zakwalifikować do kategorii AI. Zajmiemy się modelami instrukcyjnymi (Instruction Tuned LLMs), czyli takimi, które potrafią przetworzyć zapytanie na zbiór instrukcji i je wykonać.

Następnym podziałem będzie podział na modele zadaniowe i konwersacyjne.
Ponownie zajmiemy się tymi drugimi, ponieważ są one najbardziej rozpowszechnione w codziennym użytku (ChatGPT, Google Gemini, Anthropic Claude, etc.).
Modele konwersacyjne są bardziej zaawansowane od modeli zadaniowych, ponieważ zachowują i potrafią wykorzystać kontekst (historię zapytań).

Trzeci podział, to podział na modele jedno-modalne i wielo-modalne, czyli specjalizujące się w jednej kategorii (np. przetwarzanie języka naturalnego, generowanie grafiki)[jedno-modalne] lub pozwalające na przetwarzanie wielokategoryjne (np. generowanie obrazu i dźwięku, przetwarzanie języka naturalnego i generowanie kodu)[wielo-modalne]. Nas będą interesować modele wielo-modalne.

Ostatni podział, to podział na modele zwykłe i modele wnioskujące. Modele wnioskujące potrafią udzielać bardziej trafnych odpowiedzi i przeprowadzać wnioskowanie logiczne, kosztem dłuższego czasu przetwarzania i większego zużycia zasobów.