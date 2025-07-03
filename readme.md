# KONEKCJA - Galeria Zdjęć

Strona z galerią zdjęć z automatycznym deploymentem na GitHub Pages.

## Link do strony
[https://dianagryczon.github.io/stona-git/](https://dianagryczon.github.io/stona-git/)

## Technologie

- **HTML** - struktura strony
- **CSS** - stylowanie i efekty
- **GitHub Actions** - automatyczny CI/CD
- **GitHub Pages** - hosting

## Deployment

Pipeline uruchamia się przy każdym push na `main`:

1. **Test** - sprawdza czy są wszystkie pliki
2. **Deploy** - wrzuca stronę na GitHub Pages

### Testy sprawdzają obecność:
- `index.html`
- `style.css`
- zdjęć
