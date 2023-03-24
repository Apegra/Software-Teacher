## Döngüler

- [While Loop](#While-Loop)
- [For Loop](#For-Loop)
- [Break](#Break)


### While Loop

> Condition(durum) değişken girişine yalnızca boolean türünde node'lar bağlanabilir. Bağlanan node'un sonucu **True** olduğu sürece **Loop** exec hattındaki node'lar çalıştırılır. Her bir döngüden sonra Condition portu tekrar kontrol edilir bağlanan girdi durumu False olduğu zaman program **Loop** exec hattından çıkıp **Completed** exec hattındaki node'ları çalıştırarak devam eder.
>
> ![While Loop Node](/Node-Grupları/Döngüler/images/while.png)

### For Loop

> **First Index**'ten başlayıp **Last Index**'e kadar sayar. Her bir döngüde **Loop** exec hattındaki node'lar çalışırken **Index** pininden de o döngüye ait sıra sayısını verir. Döngü bittikten sonra program **Completed** exec hattındaki node'ları çalıştırarak devam eder.
>
> ![For Loop Node](/Node-Grupları/Döngüler/images/for.png)
>
> Örneğin terminal çıktısı
>
> ![For Loop Terminal](/Node-Grupları/Döngüler/images/for_terminal.png)

### Break

> While veya for döngüsünden çıkmak istendiği zaman kullanılır. 
>
>Aşağıdaki örnekte While Loop'un Condition girişine True bağlanarak sonsuz döngüye sokulur. Her döngüde program kullanıcıdan boolean türünde bir input ister. Kullanıcıdan gelen değer if ile kontrol edilir. Eğer değer false ise **break** node'u ile while döngüsü kırılarak döngüden çıkılmış olunur. Program Completed exec hattındaki node'ları çalıştırarak devam eder. Eğer kullanıcıdan gelen değer true ise tekrardan döngü Loop hattındaki node'ları çalıştırarak devam eder.
>
> ![Break Node](/Node-Grupları/Döngüler/images/break.png)