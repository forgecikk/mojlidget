# mojlidget# N8N Chat Widget

Nowoczesny widget czatu dla platformy N8N, inspirowany interfejsem Voiceflow.

## Funkcje

- Nowoczesny, responsywny design
- Płynne animacje i przejścia
- Wsparcie dla ciemnego motywu
- Dostosowywalne style i kolory
- Obsługa markdown w wiadomościach
- Animacja "typing" (pisania)

## Instalacja

### Opcja 1: Użycie CDN (zalecane)

Dodaj link do pliku CSS w sekcji `<head>` Twojej strony:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/forgecikk/mojlidget@main/style.css">
```

### Opcja 2: Instalacja lokalna

1. Skopiuj zawartość pliku `style.css` do swojego projektu
2. Dodaj link do lokalnego pliku CSS:

```html
<link rel="stylesheet" href="ścieżka/do/twojego/style.css">
```

## Dostosowanie

Możesz dostosować wygląd widgetu modyfikując zmienne CSS w sekcji `:root`:

```css
:root {
  --chat--color-primary: #4F46E5;
  --chat--color-secondary: #10B981;
  /* ... inne zmienne ... */
}
```

## Licencja

MIT 
