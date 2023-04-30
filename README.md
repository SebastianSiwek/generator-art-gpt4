# Blog Post Generator

Ten skrypt generuje artykuły na podstawie podanych słów kluczowych. Używa modelu GPT-4 do generowania tematu, wstępu, spisu treści, akapitów treści i zakończenia. Wynikowy wpis jest zapisywany jako dokument .docx.

## Wymagania

Upewnij się, że zainstalowałeś następujące biblioteki:

- openai
- python-docx

Możesz zainstalować wymagane biblioteki, używając polecenia:

pip install openai python-docx

## Użycie

1. Uzyskaj klucz API dla modelu GPT-4 od OpenAI.
2. W pliku skryptu, zamień "WPROWADŹ-SWÓJ-KLUCZ-API" na swój własny klucz API.
3. Uruchom skrypt, wprowadzając następujące informacje:

   - Nazwa branży
   - Główne słowo kluczowe
   - Dodatkowe słowa kluczowe

4. Skrypt wygeneruje i zapisze wpis na bloga w formacie .docx w folderze "Wygenerowane wpisy".

## Struktura kodu

Kod składa się z następujących funkcji:

- `generate_topic()`: Generuje temat wpisu na bloga.
- `generate_outline()`: Generuje spis treści wpisu.
- `generate_intro()`: Generuje wstęp wpisu.
- `generate_paragraph()`: Generuje akapity treści na podstawie spisu treści.
- `generate_summary()`: Generuje zakończenie wpisu.
- `create_blog_post_docx()`: Tworzy dokument .docx z wygenerowanymi treściami.
- `main`: Główna funkcja skryptu, która łączy wszystkie powyższe funkcje.

## Autor

Sebastian Siwek, kontakt: sebastiansiwekseo@gmail.com

## Licencja

Ten projekt jest udostępniany na licencji MIT. Możesz go dowolnie modyfikować i dystrybuować, pod warunkiem zachowania informacji o autorze oraz licencji.

## Wsparcie

Jeśli potrzebujesz pomocy związanej z tym skryptem, skontaktuj się ze mną poprzez mail lub zgłoś problem na stronie repozytorium.

## Kontrybucje

Wszystkie pomysły na ulepszenia, nowe funkcje lub napotkane błędy są mile widziane. Prosimy o tworzenie zgłoszeń na stronie repozytorium GitHub lub, jeśli jesteś zainteresowany(a) współpracą, o tworzenie pull requestów z proponowanymi zmianami.
