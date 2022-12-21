# Essential Stuff

## Html import links

Google font

``` html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
```

Ionicon

``` html
<script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
<script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>
```

---

## Colors

### Background color

``` css
--bg-white: hsla(0, 0%, 100%, 1);
--bg-light-gray: hsla(240, 1%, 83%, 1);
--bg-jet: hsla(0, 0%, 18%, 1);
--bg-eerie-black: hsla(0, 0%, 13%, 1);
--bg-rich-black-fogra-29: hsla(229, 23%, 9%, 1);
--bg-smoky-black: hsla(0, 0%, 6%, 1);
--bg-black: hsla(0, 0%, 0%, 1);
```

### Gradient color

``` css
--gradient-1: linear-gradient(to top, var(--bg-black) 0%, transparent 40%);
--gradient-2: radial-gradient(circle at 75% 100%, hsla(79, 100%, 70%, 0.3) 0%, transparent 100%);
```

### Text color

``` css
--text-white: hsla(0, 0%, 100%, 1);
--text-light-gray: hsla(240, 1%, 83%, 1);
--text-rich-black-fogra-29: hsla(216, 42%, 12%, 1);
--text-smoky-black: hsla(0, 0%, 6%, 1);
--text-black: hsla(0, 0%, 0%, 1);
```

### Border color

``` css
--border-white: hsla(0, 0%, 100%, 1);
--border-light-gray: hsla(240, 1%, 83%, 1);
--border-gainsboro: hsla(220, 13%, 91%, 1);
--border-eerie-black: hsla(0, 0%, 13%, 1);
--border-smoky-black: hsla(0, 0%, 6%, 1);
```

## Typography

``` css
--fontFamily-recoleta: 'Recoleta';
--fontFamily-roboto: 'Roboto', sans-serif;

--fontSize-1: 4.6rem;
--fontSize-2: 4.5rem;
--fontSize-3: 4rem;
--fontSize-4: 3rem;
--fontSize-5: 2.4rem;
--fontSize-6: 1.8rem;
--fontSize-7: 2rem;
--fontSize-8: 1.6rem;
--fontSize-9: 1.5rem;
--fontSize-10: 1.4rem;

--weight-regular: 400;
--weight-medium: 500;
```

## Spacing

``` css
--section-spacing: 70px;
```

## Border Radius

``` css
--radius-pill: 500px;
--radius-circle: 50%;
```

## Transition

``` css
--transition-1: 0.25s ease;
--transition-2: 0.5s ease;
--transition-3: 1000ms cubic-bezier(0.03, 0.98, 0.52, 0.99) 0s;
--cubic-in: cubic-bezier(0.51, 0.03, 0.64, 0.28);
--cubic-out: cubic-bezier(0.05, 0.83, 0.52, 0.97);
```
