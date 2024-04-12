### How Node works

# Nauka Node.js

Witaj w repozytorium poświęconym nauce Node.js! Ten projekt zawiera przykładowe pliki JavaScript, które demonstrują różne koncepcje i funkcjonalności w środowisku Node.js. Poniżej znajdziesz krótkie opisy każdego pliku:

## 1. event-loop.js

Plik `event-loop.js` ilustruje działanie pętli zdarzeń w Node.js oraz wykorzystanie asynchronicznych operacji wejścia/wyjścia. Zawiera kod, który prezentuje działanie funkcji `setTimeout`, `setImmediate`, `fs.readFile`, `process.nextTick` oraz `crypto.pbkdf2Sync`.

## 2. events.js

W `events.js` pokazane są podstawowe funkcje obiektu EventEmitter oraz jego użycie w praktyce. Tworzony jest także serwer HTTP, który wykorzystuje zdarzenia do obsługi żądań oraz zamykania serwera.

## 3. modules

W tym pliku znajduje się przykład wykorzystania modułów w Node.js, zarówno z użyciem `module.exports`, jak i `exports`. Demonstruje także mechanizm cachowania modułów.

## 4. streams.js

`streams.js` prezentuje różne podejścia do przetwarzania strumieni danych w Node.js. W przykładzie wykorzystane są strumienie do przesyłania zawartości pliku do klienta HTTP.

## Instrukcje uruchomienia

1. Sklonuj repozytorium na swój lokalny komputer.
2. Upewnij się, że masz zainstalowanego Node.js.
3. Otwórz terminal w głównym katalogu repozytorium.
4. Uruchom każdy plik przy użyciu komendy `node nazwa-pliku.js`, na przykład `node event-loop.js`.

Mam nadzieję, że te przykłady będą pomocne w nauce Node.js. Jeśli masz jakiekolwiek pytania lub sugestie, śmiało dodawaj issues lub kontaktuj się ze mną bezpośrednio.

Dziękuje za skorzystanie z tego repozytorium!
