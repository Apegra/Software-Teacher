## Temel Fonksiyonlar

- [Print](#Print)
- [String Input](#String-Input)
- [Integer Input](#Integer-Input)
- [Float Input](#Float-Input)
- [Boolean Input](#Boolean-Input)
- [If-Else](#If-Else)
- [Len](#Len)


### Print

> İçerisine yazılan metni veya kendisine bağlanan değişkenin değerini terminal ekranına yazar.
>
> ![Print Node](/Node-Grupları/Temel-Fonksiyonlar/images/print.png)

### String Input

> İçerisinde yazılan soru ile kullanıcıdan string türünde değer alır. Değişken çıkışı kullanılarak diğer node'lara bağlantı yapıldığında kullanıcıdan alınan değer çağrılabilir.
>
> ![String Input Node](/Node-Grupları/Temel-Fonksiyonlar/images/string_input.png)

### Integer Input

> İçerisinde yazılan soru ile kullanıcıdan integer türünde değer alır. Değişken çıkışı kullanılarak diğer node'lara bağlantı yapıldığında kullanıcıdan alınan değer çağrılabilir.
>
> ![Integer Input Node](/Node-Grupları/Temel-Fonksiyonlar/images/integer_input.png)

### Float Input

> İçerisinde yazılan soru ile kullanıcıdan float türünde değer alır. Değişken çıkışı kullanılarak diğer node'lara bağlantı yapıldığında kullanıcıdan alınan değer çağrılabilir.
>
> ![Float Input Node](/Node-Grupları/Temel-Fonksiyonlar/images/float_input.png)

### Boolean Input

> İçerisinde yazılan soru ile kullanıcıdan boolean türünde değer alır. Değişken çıkışı kullanılarak diğer node'lara bağlantı yapıldığında kullanıcıdan alınan değer çağrılabilir.
>
> ![Boolean Input Node](/Node-Grupları/Temel-Fonksiyonlar/images/boolean_input.png)

### If-Else

> Condition(durum) değişken girişine yalnızca boolean türünde node'lar bağlanabilir. Bağlanan node'un sonucu **True** ise True exec hattındaki node'lar çalıştırılırken eğer bağlanan node'un sonucu **False**  ise False exec hattındaki node'lar çalıştırılır. Bağlanan girdi duruma göre True veya False exec hattının biri çalıştıktan sonra program Completed exec hattındaki node'ları çalıştırarak devam eder.
>
> Aşağıdaki örnekte 5 sayısının 10'dan büyük olup olmadığı kontrol edilmektedir. 5, 10'dan küçük olduğu için sonuç False olur ve False exec hattındaki node'lar çalıştırılır. False exec hattındaki tüm node'lar çalıştırıldıktan sonra program Completed exec hattındaki node'ları çalıştırarak devam eder.
>
> ![If-Else Node](/Node-Grupları/Temel-Fonksiyonlar/images/if_else.png)
>
> Örneğin terminal çıktısı :
>
> ![If-Else Terminal](/Node-Grupları/Temel-Fonksiyonlar/images/if_else_terminal.png)

### Len

> Kendisine bağlanan string türündeki bir değişkenin karakter sayısını verir.
>
> ![Len](/Node-Grupları/Temel-Fonksiyonlar/images/len.png)
