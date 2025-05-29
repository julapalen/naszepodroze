# Podsumowanie projektu strony NaszePodroze.pl

## Wstęp

Strona została wykonana w ramach projektu szkolnego, korzystając z darmowego szablonu internetowego udostępnionego przez BootstrapMade. Praca polegała głównie na zastępowaniu gotowych bloków tekstu własnymi treściami oraz wklejaniu zdjęć w odpowiednie miejsca w kodzie HTML.

Nie wymagało to zaawansowanej wiedzy informatycznej, ponieważ większość elementów (np. układ strony, przyciski, karty, nawigacja) była już predefiniowana w szablonie dzięki wykorzystaniu frameworka Bootstrap.

## Praca z szablonem

Szablon był już wyposażony w gotowe elementy graficzne i układy, dzięki czemu nie było potrzeby zaawansowanej znajomości programowania. Większość elementów, takich jak nagłówki, karty, przyciski czy nawigacja, była predefiniowana przez framework Bootstrap.

### Przykład podmiany tekstu

Aby zmienić tytuł strony lub nagłówek, wystarczyło edytować odpowiedni fragment kodu HTML:

```html
<h1 class="mb-2 mb-lg-0">Contact</h1>
```
Zmieniłam na:

```html
<h1 class="mb-2 mb-lg-0">O autorce</h1>
```
Podobnie można było zmienić opisy, podpisy pod zdjęciami czy inne treści.

### Wstawianie własnych zdjęć

Aby podmienić zdjęcie, wystarczyło zmienić atrybut `src` w tagu `<img>`, np.:

```html
<img src="assets/img/ja.jpeg" alt="Moje zdjęcie">
```

Wystarczyło skopiować własny plik graficzny do folderu `assets/img/` i podać jego nazwę w kodzie.

### Linki do mediów społecznościowych

Linki do profili szkoły na Facebooku czy Instagramie były wstawione za pomocą tagu `<a>`:

```html
<a href="https://www.facebook.com/lo1.opole"><i class="bi bi-facebook"></i></a>
<a href="https://www.instagram.com/lo1.opole/"><i class="bi bi-instagram"></i></a>
```

Aby zmienić link, wystarczyło podmienić adres w atrybucie `href`.
Ikony ```bi bi-facebook``` etc. były już gotowe w szablonie.

## Przykład gotowego bloku z danymi autorki

```html
<div class="card text-center p-4 shadow">
  <img src="assets/img/ja.jpeg" alt="Julia Paleń" class="img-fluid rounded-circle mb-3" style="width: 180px; height: 180px; object-fit: cover; margin: 0 auto;">
  <h2 class="mb-1">Name Surname</h2>
  <p class="mb-1">Description</p>
  <p class="mb-1">Address</p>
  <p class="mb-1"><i class="bi bi-envelope"></i> <a href="mailto:<paste_mail>">Mail Address</a></p>
</div>
```

## Wstawianie filmiku z YouTube

Aby dodać filmik z YouTube na stronę, skorzystałam z trybu osadzenia (embed) dostępnego na YouTube. Wystarczyło kliknąć przycisk „Udostępnij” pod wybranym filmem, a następnie wybrać opcję „Osadź”. YouTube wygenerował gotowy kod HTML, który można było wkleić w odpowiednie miejsce w pliku strony.

Przykładowy kod osadzenia wyglądał tak:

```html
<iframe width="560" height="315" src="https://www.youtube.com/embed/ID_FILMU" title="YouTube video player" frameborder="0" allowfullscreen></iframe>
```

Wystarczyło skopiować ten kod i wkleić go do pliku HTML, aby filmik pojawił się na stronie. Tego sposobu nauczyłam się z poradnika dostępnego w internecie.
Podmieniłam przykłądowy filmik dostępny w szablonie.

## Wybieranie ikon – interaktywne Bootstrap Icons

Podczas pracy nad stroną korzystałam z serwisu [Bootstrap Icons](https://icons.getbootstrap.com/), który umożliwia szybkie wyszukiwanie i wybieranie ikon. Wystarczyło wpisać nazwę lub słowo kluczowe w wyszukiwarce na stronie, a serwis wyświetlał pasujące ikony.

Po wybraniu odpowiedniej ikony, serwis generował gotowy fragment kodu HTML, np.:

```html
<i class="bi bi-camera"></i>
```

Wystarczyło skopiować ten kod i wkleić go w odpowiednie miejsce w pliku HTML, aby wybrana ikona pojawiła się na stronie. Dzięki temu łatwo mogłam dostosować wygląd strony do własnych potrzeb, wybierając spośród wielu dostępnych ikon.

## Karuzele zdjęciowe i efekty

Szablon zawierał gotowe karuzele zdjęciowe oraz efekty przejść, dzięki czemu nie musiałam samodzielnie ich tworzyć ani konfigurować. Wystarczyło jedynie podmienić przykładowe zdjęcia na własne, zachowując odpowiednią strukturę folderów i nazw plików. Wszystkie animacje i efekty wizualne były już zaimplementowane w szablonie, co znacznie ułatwiło pracę nad stroną.

## Podsumowanie

Projekt nie wymagał specjalistycznej wiedzy informatycznej. Wystarczyło podstawowe zrozumienie struktury pliku HTML oraz umiejętność kopiowania i podmieniania fragmentów kodu. Dzięki gotowemu szablonowi Bootstrap praca była prosta i polegała głównie na edycji tekstów oraz wstawianiu własnych zdjęć.

---

**Szablon wykorzystany w projekcie pochodzi ze strony BootstrapMade i jest dostępny za darmo do użytku niekomercyjnego.**
