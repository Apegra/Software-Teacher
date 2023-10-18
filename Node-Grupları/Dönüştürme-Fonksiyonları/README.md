## Dönüştürme Fonksiyonları

- [Int](#Int)
- [Float](#Float)
- [Str](#Str)
- [Bool](#Bool)


### Int

> Değişken girişine bağlanan node'u integer türüne çevirir.  

    Boolean:
        True -> 1
        False -> 0

    Float:
        5.849 -> 5

> ![Int Node](https://github.com/Apegra/Software-Teacher/blob/main/Node-Grupları/Dönüştürme-Fonksiyonları/images/int.png?raw=true)

### Float

> Değişken girişine bağlanan node'u float türüne çevirir.  

    Integer:
        25 -> 25.0

    Boolean:
        True -> 1.0
        False -> 0.0

> ![Float Node](https://github.com/Apegra/Software-Teacher/blob/main/Node-Grupları/Dönüştürme-Fonksiyonları/images/float.png?raw=true)

### Str

> Değişken girişine bağlanan node'u string türüne çevirir.  

    Integer:
        58 -> "58"

    Float:
        73.9 -> "73.9"

    Boolean:
        True -> "True"
        False -> "False"

> ![Str Node](https://github.com/Apegra/Software-Teacher/blob/main/Node-Grupları/Dönüştürme-Fonksiyonları/images/str.png?raw=true)

### Bool

> Değişken girişine bağlanan node'u boolean türüne çevirir.  

    Integer:
        62 -> True
        0 -> False
        - 0 Haricindeki tüm değerler True sonucunu verir.

    Float:
        9.780 -> True
        0.0 -> False
        - 0.0 Haricindeki tüm değerler True sonucunu verir.

    String:
        "Hello" -> True
        "" -> False
        - Boş string haricindeki tüm değerler True sonucunu verir.

> ![Bool Node](https://github.com/Apegra/Software-Teacher/blob/main/Node-Grupları/Dönüştürme-Fonksiyonları/images/bool.png?raw=true)