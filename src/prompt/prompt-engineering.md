# Prompt Engineering

Jak można się domyślić z nazwy - prompt engineering to umiejętność tworzenia i wykorzystywania zapytań w taki sposób by były one efektywne, 
a przede wszystkim - działające 😉.

OpenAI (to ci od ChatGPT i DALL·E) definiuje prompt engineering w swojej dokumentacji w następujący sposób:

> Prompt engineering is the process of writing effective instructions for a model, such that it consistently generates content that meets your requirements.

Myślę, że ciężko byłoby to lepiej opisać - prompt engineering jest sztuką tworzenia zapytań, które **stale (*każdorazowo*)** zwracają rezultaty możliwie spełniające nasze wymagania. Ta stałość jest istotna, ponieważ modele językowe bazują na sieciach neuronowych, a więc są niedeterministyczne - każde wywołanie (nawet z dokładnie takim samym zapytaniem) może dać różne odpowiedzi.

Z tego powodu do tworzenia zapytań trzeba podchodzić jednocześnie bardzo precyzyjnie i elastycznie (podobnie jak do projektowania stron internetowych - stałe wymiary się nie sprawdzą, ale brak odpowiednich ograniczeń doprowadzi do [w najlepszym przypadku] brzydkich, a w najgorszym przypadku - nieużywalnych witryn). \
Równie podobnie jak w projektowaniu stron internetowych, w pisaniu dobrych promptów nie ma jednego rozwiązania - każdy przypadek jest indywidualny i jedyne z czego możemy skorzystać to pewne dobre wzorce i inspiracje, które są mieszaniną teorii i doświadczenia eksperymentalnego.

Wiemy już czym jest prompt engineering w teorii, czas więc w praktyce poznać wzorce i metody projektowania efektywnych zapytań.
A więc jedźmy, nikt nie woła...