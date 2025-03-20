## Máv utstájékoztató

Ez a projekt egy egyszerű webes felületet biztosít a MÁV vonatindulások és érkezések megjelenítésére. A weboldal <strong>HTML</strong> és <strong>CSS</strong> segítségével készült, és egy táblázatos formátumban jeleníti meg az aktuális menetrendet.

### 📌funkciók

<- 🚉 Induló és érkező vonatok listázása táblázatban
- ⏰ Állomás, indulási és érkezési idők megjelenítése
- 🎨 Felhasználóbarát, letisztult dizájn
>

### 🚀 Használat

Egyszerűen nyisd meg a https://gerinova01.github.io/MAV_utastajekoztato/index.html weboldalt a böngészőben, és a rendszer betölti az aktuális adatokat.

### 🌍 Élő demó

A projekt élőben megtekinthető az alábbi linken: [Máv utstájékoztató](https://gerinova01.github.io/MAV_utastajekoztato/index.html)

## 🏗️ Alap HTML szerkezet

```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MAV_utastsajekoztato</title>
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
            <tr>
                <td>8:30</td>
                <td id="keses">8:42</td>
                <td>IC</td>
                <td>Szeged</td>
                <td>Szatymaz-Kistelek</td>
                <td>5</td>
            </tr>
            <tr class="paratlan_sor">
                <td>9:22</td>
                <td></td>
                <td>SZ</td>
                <td>Szentes</td>
                <td>Csongrád</td>
                <td>2</td>
            </tr>
            <tr>
                <td>9:22</td>
                <td></td>
                <td>IC</td>
                <td>Szeged</td>
                <td>Szatymaz-Kistelek</td>
                <td>4</td>
            </tr>
            <tr class="paratlan_sor">
                <td>9:24</td>
                <td></td>
                <td>SZ</td>
                <td>Lakitelek</td>
                <td>Tiszaalpár</td>
                <td>1</td>
            </tr>
            <tr>
                <td>9:27</td>
                <td></td>
                <td>IC</td>
                <td>Nyugati**Budapest</td>
                <td>Cegléd-Kecskemét</td>
                <td>5</td>
            </tr>
            <tr class="paratlan_sor">
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

```css

border: 1px solid;
    border-collapse: collapse;
  }
  
  table {
    width: 60%; /* weboldal szélessége */
    background-color: rgb(12, 121, 12);  /* háttérszín */
    color: rgb(232, 238, 235); /* betűszín */
    font-family: 'Courier New', Courier, monospace;
    font-size: 25px;
  }
  
  th {
    background-color: rgb(35, 85, 143);
  }
  #keses{
    background-color: crimson;
  }
  .paratlan_sor{
    background-color: rgb(109, 165, 26);
  }

  ```
  