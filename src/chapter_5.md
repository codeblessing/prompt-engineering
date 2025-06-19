# Jaka piękna katastrofa...

... czyli podstawowe błędy popełniane przy trworzeniu zapytań.

### Brak kontekstu i konkretnego celu

```plaintext
Stwórz obraz w stylu romantycznym.
```

Powyższe zapytanie w wielu przypadkach nawet nie przyniesie rezultatu, ponieważ modelowi brakuje danych potrzebnych do wykonania polecenia (np. ChatGPT zapyta o tematykę obrazu, kolorystykę i inne detale).

### Zbyt dokładne zapytanie

```plaintext
ROLE: You are a technical writer with 17 years of experience in the consumer electronics industry, especially focused on Bluetooth-enabled wearable devices. You hold ISO-9001 documentation compliance certification and have authored over 400 product manuals.

TASK: Write a 1,473-word product review of a fictional Bluetooth-powered smart scarf, “ThermoWrap Pro 7.2.” The review must follow the exact section breakdown below and include a precise number of sentences per section.

TARGET AUDIENCE: A niche group of early adopters aged 34–37 who live in temperate climates with mild seasonal variability and own at least two other smart textiles.

SECTION OUTLINE (with strict constraints):

    Introduction (exactly 5 sentences)

        Begin with a rhetorical question

        Include the full product name twice

        Reference Q3 weather patterns in the U.S. Midwest

    Unboxing Experience (exactly 7 sentences)

        Describe packaging using only tactile adjectives

        Mention the inclusion of a multilingual quick-start guide

        Include one sentence in passive voice

    Technical Specifications (exactly 9 sentences)

        List at least 12 specific tech specs using metric units

        Include charging time in minutes and standby time in hours

        Reference the firmware version at least twice

    User Experience (exactly 11 sentences)

        Simulate a user's first three days of wearing it (hour-by-hour breakdown)

        Mention temperature settings in both Celsius and Fahrenheit

        Include a quote from a fictional user named “Ari K.”

    Connectivity & App Integration (exactly 6 sentences)

        Reference both iOS and Android connectivity

        Mention Bluetooth version and encryption method

        Avoid using the words “fast,” “seamless,” or “intuitive”

    Battery Life & Charging (exactly 8 sentences)

        Compare its battery performance with three other fictional wearables

        Mention charging cable length in millimeters

        Describe LED behavior during charging

    Pros & Cons Table (2-column markdown table)

        Include exactly 6 rows

        All items must be phrased in parallel grammatical structure

        Pros must contain only active verbs, Cons only passive constructions

    Final Verdict (exactly 3 sentences)

        Avoid any superlatives

        Mention one potential use case for librarians

        End with a culturally neutral idiom involving weather

STYLE & TONE RULES:

    Use British spelling

    Avoid any words with more than three syllables in the Verdict section

    No emojis, contractions, or rhetorical exclamations anywhere in the document

LENGTH ENFORCEMENT: Final word count must be between 1,470 and 1,475 words. Include a word count at the bottom of the text.
```

Tak, w tym przypadku chyba nie trzeba tłumaczyć dlaczego rezultat nie jest najefektywniejszy...

### Używanie zaprzeczeń

Ciekawą cechą modeli językowych jest to, że - podobnie jak ludziom - nieco lepiej idzie im przetwarzanie instrukcji bezpośrednich aniżeli przeczących.
W większości przypadków użycie zaprzeczenia nie skończy się armageddonem, ale lepiej używać ich oszczędnie.

Dlatego zamiast takiego zapytania:

```plaintext
Write a poem about birds flying away.

Don't use british english.
Don't use semicolon.
Don't use emoji.
Don't use simple words.
```

lepiej jest użyć następującego:

```plaintext
Write a poem about birds flying away.

Use american english.
Use full sentences.
Use only words.
Use rich vocabulary.
```

### Zbyt wiele zadań w jednym zapytaniu

```plaintext
Create image of Nicholas Cage as Batman and soundtrack piece for epic thriller movie.
```

To zapytanie może zadziałać, ale w zdecydowanej większości przypadków nie przyniesie oczekiwanego rezultatu.\
W promptowaniu jak w programowaniu - Single Responsibility Principle.