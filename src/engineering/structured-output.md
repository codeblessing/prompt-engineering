# Trójkąty i kwadraty

Czasem chcemy uzyskać jakiś konkretny format wyjścia, na przykład JSON lub YAML.
Jest to przydatne zwłaszcza przy przetwarzaniu danych lub generowaniu rekordów testowych.

Przetestujmy podstawową formę zapytania, czyli podanie formatu danych.

```plaintext
# Task

Generate 30 records with fake credit card data for testing card verification component.

Output format: JSON
```

[ChatGPT](https://chatgpt.com/share/685d74a2-b6c8-8007-a017-c02e8de486db)

[Gemini](https://g.co/gemini/share/ac2fb4ec2c99)

Możemy, a nawet powinniśmy, doprecyzować nasze wymagania dotyczące formatu wygenerowanej odpowiedzi.

```plaintext
# Task

Generate 10 records with fake credit card data for testing card verification component.

# Output

Format: JSON
Every record contains fields 'number', 'expiration_date' and 'cvv'.
```

[ChatGPT](https://chatgpt.com/share/685d76cb-63ac-8007-b679-000409e5e358)

[Gemini](https://g.co/gemini/share/b6b4cfe6d716)

---

Czasem, zamiast dokładnie opisywać oczekiwane wyjście, możemy użyć odpowiedzi częściowych, czyli podać modelowi przykład oczekiwanych odpowiedzi.

```plaintext
# Task

Generate 10 purchases in cinema box office. Purchase can contain fields: 'tickets', 'popcorn', 'coke', 'nachos'.

# Output

Format: YAML

Examples (in triple quotes):

"""
purchases:
  - 
    tickets:
      normal: 2
    popcorn:
      caramel: 2
  -
    tickets:
      normal: 1
      reduced: 2
    popcorn:
      salted: 1
      caramel: 1
    coke:
      small: 2
    nachos: 1
  -
    popcorn:
      caramel: 1
    nachos: 1
"""
```

[ChatGPT](https://chatgpt.com/share/685d7d0d-8d24-8007-a805-d71696778fb8)

[Gemini](https://g.co/gemini/share/5bd82b25107a)