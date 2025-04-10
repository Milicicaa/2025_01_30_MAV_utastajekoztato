# MÁV utastájékoztató

Ez a HTML oldal a MÁV menetrendjét mutatja, amely segít az utasoknak az eligazodásban és az információk megszerzésében


### 📍 Mik a funkciói?
- 🚂 Induló és érkező vonatok
- 🕰 Állomás, indulási és érkezési idők mutatása
- ✨ Könnyen átlátható, dizájnos

### 🧐 Hogyan kell használni?
Nyisd meg a `https://github.com/Milicicaa/2025_01_30_MAV_utastajekoztato.git` weboldalt a böngészőben, majd a rendszer betölti a jelenlegi adatokat
#### 🔴 Élő demó

Tekintsd meg a projektet élőben:
[📎 MÁV Utastájékoztató](https://github.com/Milicicaa/2025_01_30_MAV_utastajekoztato.git)

### ⚙️ Alap HTML szerkezet
```html
<!DOCTYPE html>
<html lang="hu">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Máv utastájékoztató</title>

    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <table>
        <thead>
            <tr>
                <th>Tervezett érkezés</th>
                <th>Érkezés</th>
                <th>Vonat</th>
                <th>Honnan</th>
                <th>Hova</th>
                <th>Vágány</th>
            </tr>
        </thead>

        <tbody>
            <tr class="paratlan"> 
                <td>8:30</td>
                <td>8:42</td>
                <td>IC</td>
                <td>Szeged</td>
                <td>Szatymaz-Kistelek</td>
                <td>5</td>
            </tr> 
            <tr>
                <td>9:22</td>
                <td></td>
                <td>SZ</td>
                <td>Szentes</td>
                <td>Csongrád</td>
                <td>2</td>
            </tr>    
        </tbody>
    </table>

    <a href="indulo_vonatok.html">Induló vonatok</a>
</body>
</html>
```

## 🪅 CSS Stílusok
```css
table {
    border: 1px solid;
    background-color: rgb(35, 110, 35);
    color: rgb(255, 255, 255); /* betűszín */
    font-family: 'Courier New'; /* betűtípus */
    font-size: 30px; /* betűméret */
  }

  #keses {
    background-color: rgb(203, 172, 233);
  }

  .paratlan {
    background-color: rgb(118, 197, 131);
  }
```
