# MÁV utastájékoztató

Ez a HTML oldal a MÁV menetrendjét mutatja, amely segít az utasoknak az eligazodásban és az információk megszerzéséről


### 📌 Funkciók
- 🚉 Induló és érkező vonatok
- ⏰ Állomás, indulási és érkezési idők mutatása
- 🎨 Könnyen átlátható, dizájnos

### 🚀 Használat
Nyisd meg a `https://github.com/Milicicaa/2025_01_30_MAV_utastajekoztato.git` weboldalt a böngészőben, és a rendszer betölti az aktuális adatokat.
#### 🌍 Élő demó

A projekt élőben megtekinthető az alábbi linken:  
[🔗 MÁV Utastájékoztató](https://github.com/Milicicaa/2025_01_30_MAV_utastajekoztato.git)

### 🏗️ Alap HTML szerkezet
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
                <th>8:43:03</th>
                <th></th>
                <th></th>
                <th></th>
                <th></th>
                <th><img src="mav-logo.png" alt="MÁV logó" height="60px"></th>
            </tr>
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
            <tr class="paratlan"> 
                <td>9:22</td>
                <td></td>
                <td>IC</td>
                <td>Szeged</td>
                <td>Szatymaz-Kistelek</td>
                <td>4</td>
            </tr>          
            <tr>
                <td>9:24</td>
                <td></td>
                <td>SZ</td>
                <td>Lakitelek</td>
                <td>Tiszaalpár</td>
                <td>1</td>
            </tr>         
            <tr class="paratlan"> 
                <td>9:27</td>
                <td></td>
                <td>IC</td>
                <td>Nyugati** Budapest</td>
                <td>Cegléd-Kecskemét</td>
                <td>5</td>
            </tr>       
            <tr>
                <td>9:30</td>
                <td></td>
                <td>IC</td>
                <td>Szeged</td>
                <td>Szatymaz-Kistelek</td>
                <td>3</td>
            </tr>
        </tbody>
    </table>

    <a href="indulo_vonatok.html">Induló vonatok</a>
</body>
</html>
```

## 🎨 CSS Stílusok
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
