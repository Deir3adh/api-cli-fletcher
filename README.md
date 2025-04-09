# api-cli-fetcher
`api-cli-fetcher` to aplikacja CLI napisana w Pythonie, która umożliwia pobieranie danych z wybranego API i zapisanie ich do pliku w formacie JSON. Aplikacja jest zaprojektowana w celu łatwego pobierania i przetwarzania danych z różnych źródeł API, a następnie zapisywania tych danych w pliku na lokalnym dysku.

## Instrukcje instalacji

Aby rozpocząć pracę z projektem, najpierw musisz sklonować repozytorium na swoje konto GitHub:

1. Otwórz stronę repozytorium na GitHubie.
2. Kliknij przycisk **Fork** w prawym górnym rogu strony, aby sklonować repozytorium do swojego konta GitHub.
3. Sklonuj repozytorium na swoje lokalne urządzenie:

   ```bash
   git clone https://github.com/Deir3adh/api-cli-fetcher.git

## Przykłady komend
./cli_fetcher 
--fetch oznacza, że aplikacja ma pobrać dane z API.
--url to adres API, z którego aplikacja ma pobrać dane.
https://api.example.com/data 
--output data.json  to nazwa pliku, do którego dane mają zostać zapisane w formacie JSON.

## Mozliwosc rozszerzenia aplikacji
Aby dodać nowe źródło danych, wystarczy zaimplementować funkcję, która pobiera dane z nowego API. Możesz to zrobić w głównym pliku aplikacji, dodając obsługę nowego URL i zapisywanie wyników do pliku JSON.

----
