# HTML

- Dokuments - līdzīg kā WORD
- HTML apraksta dokumenta saturu

---

## Dokumenta saturs:

- Teksts / Virsraksti
- Attēli / Video / Audio
- Formas / Ievadlauki / Pogas

## Kam nav VSCODE:

- https://stackblitz.com/edit/js-bpmrbn?file=index.html

---


## HTML tag:

### Vienkāršs:

```html
<a></a>
```

- taga vārds (tag name): `a`
- atverošais tags (opening tag): `<a>`
- aizverošais tags (closing tag): `</a>`

### Ar atribūtiem:

```html
<a href="https://google.com" title="Google">Link to google</a>
```

- atribūta vārds (attibute name): `href`
- atribūta vērtība (attribute value): `https://google.com`

### Viss tags kopumā:

- atverošais tags: `<a ...>`
- atribūti (attributes):
  - href - `href="https://google.com"`
  - title - `title="Google"
- taga saturs: "Link to google"
- aizverošais tags: `</a>`

---

## HTML versija:

HTML 5

```HTML
<!DOCTYPE html>
```

---

## Dokuments:

```HTML
<!DOCTYPE html>
<html>
    <head></head>
    <body></body>
</html>
```

- Elementi ir, kā kastes viena otrā iekšā:

```
[ { ( saturs ) } (bilde) ]
```

```
    ( saturs )
        |
        v
  {            } (bilde)
        |           |
        v           v
[                        ]
```

### Galva (<head>)

- Meta-dati
- Dokumenta nosaukums
- Dokumenta ikona
- Atbalstītie ekrāni
- "valoda" - burtu simbolu tips
- Kā Google un Facebook saprast Tavu lapu
- u.c.

### Saturs (<body>)

- Virsraksti
- Teksts
- Bildes
- Saites
- JavaScript
- u.c.

```HTML
<h1>Lielākais virsraksts</h1>
<p>Paragrāfs ar tekstu</p>
<img src="attēla/atrašanās/vieta.png" alt="attēla nosaukums">
<a href="saites/mērķis">Mana saite</a>
```

#### Attēli (unsplash):

- https://source.unsplash.com/rW-I87aPY5Y/800x600
- https://source.unsplash.com/{photo-id}/{size}
