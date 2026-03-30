# Language Translation Token Analysis

This project analyzes the change in token count when translating medical text from English to Spanish using OpenAI's `gpt-4o` model.

## Key Insights

1. For a typical English to Spanish sentence translation, token count increased by about 28%.
2. Simple sentences, on average, have a higher percentage token increase than complex sentences.
   **Why**: Complex sentences, especially in a technical domain like medicine, are often more literal and less idiomatic. The terminology translates more directly, leading to a smaller proportional change.
3. Token change for simple sentences is highly variable (IQR spanning from 23% to 44%) whereas token change for complex sentences is very consistent and predictable.
