# Looping

Apa yang akan kamu lakukan saat disuruh mencetak kalimat berulang-ulang?

Misalnya:

“Tolong tampilkan kalimat `"Tutorial Javascript!"` di website saya sebanyak 10 kali”

Mungkin kamu bisa menuliskannya dengan fungsi `document.write()` sebanyak 10 kali seperti ini:

```html
document.write("<p>Tutorial Javascript!</p>");
document.write("<p>Tutorial Javascript!</p>");
document.write("<p>Tutorial Javascript!</p>");
document.write("<p>Tutorial Javascript!</p>");
document.write("<p>Tutorial Javascript!</p>");
document.write("<p>Tutorial Javascript!</p>");
document.write("<p>Tutorial Javascript!</p>");
document.write("<p>Tutorial Javascript!</p>");
document.write("<p>Tutorial Javascript!</p>");
document.write("<p>Tutorial Javascript!</p>");
```

kode : hasil&#x20;

![](<../.gitbook/assets/image (1).png>)

{% hint style="info" %}
Bagaimana kalau nanti dia mau menampilkan sebanyak `1000` kali. Pasti capek donk ngetiknya. Karena itu, kita harus menggunakan **perulangan**.
{% endhint %}

{% hint style="warning" %}
Perulangan akan membantu kita mengeksekusi kode yang berulang-ulang, berapapun yang kita mau.
{% endhint %}

## Perulangan For

For adalah salah satu kata kunci yang bisa digunakan untuk melakukan perulangan. Blok kode yang terdapat di dalam for akan selalu diulangi selama kondisi for terpenuhi

Sintak Perulangan For

```javascript
for( init statement ; kondisi ; post statement ){
   // block perulangan
}
```

{% hint style="info" %}
Init statement akan dieksekusi hanya sekali di awal sebelum perulangan

Kondisi akan dilakukan pengecekan dalam setiap perulangan, jika true perulangan akan dilakukan, jika false perulangan akan berhenti

Post statement akan dieksekusi setiap kali diakhir perulangan

Init statement, Kondisi dan Post Statement tidak wajib diisi, jika Kondisi tidak diisi, berarti kondisi selalu bernilai true
{% endhint %}

**Kode : Perulangan For**

![](https://lh3.googleusercontent.com/TQwJJeHqeU6RF21UiMzA-d9Y4G9M6covjfTCRF-h0oNdfL0NClvmtmWAlT6Gc65sUgZJLEtxfIRswOlgcjmXgNZs0IZjGjlQHnJP4F-g4wRVZpXPpjLmmzHCi\_wB8htKO9kMQuWkiAa-BoziVrl22Q)

## **Perulangan While**

While loop adalah versi perulangan yang lebih sederhana dibanding for loop**.** Di while loop, hanya terdapat kondisi perulangan, tanpa ada init statement dan post statement

Kode : While Loop

![](https://lh3.googleusercontent.com/0mKNnAAmMMMRi2xxI97yDaoEBDRtZGhDUTIRKO9ewh9QBIclYWDngxrwsZn1ibUrTEdfrAWBFHOhMr-sQoLeJwCTa5dF59GkPnPEe-hWpK45rqCAfNqHlNFFq4w0oickgkSN9imK\_hbil0S-X6RBfg)

## Perulangan **Do While**

Do While loop adalah perulangan yang mirip dengan while

Perbedaannya hanya pada pengecekan kondisi

Pengecekan kondisi di while loop dilakukan di awal sebelum perulangan dilakukan, sedangkan di do while loop dilakukan setelah perulangan dilakukan

Oleh karena itu dalam do while loop, minimal pasti sekali perulangan dilakukan walaupun kondisi tidak bernilai true

**Kode : Do While Loop**

![](https://lh4.googleusercontent.com/qm2fQZ9mMhjiN9dlS\_17HIHju\_PnIN21o1I\_DyQyq3OCNIdJVLK9RPOats5ZKceR4FcfTzXmqzJ3SLO1incy6yNn5xS3Rv2VtQ3fRpvrp13ffzx5yf9-c1Ssub77kU0R4yQsr\_hxvktfA-\_fNh7Ukg)

## **Perulangan** For In

For In merupakan perulangan for yang digunakan untuk mengiterasi seluruh data property di object atau index di array. Walaupun for in bisa digunakan untuk Array, namun tidak direkomendasikan untuk Array, karena biasanya kita jarang sekali butuh data index untuk Array, kita bisa menggunakan For Of (yang dibahas setelah ini)

Kode : For In di Object

![](https://lh3.googleusercontent.com/wxxBU9\_87HSDroPsdMoZoAG1pgzlitzyUK7MRWlQ00w2r029\_uUel-TtgNdAF7udb1INvyBd4gTSI42wBu239PNRKO5aw\_SKLFQ4YrOxt7KsM962eyMBCra0eMDfWmQviA-7uIVxh3bwRBfSZlHF7g)

**Kode : For In di Array**

![](https://lh3.googleusercontent.com/jAYqxTJ5wd9tq4oRspVaYNoEExrW8k6oew-dYDTkKdydLMgi0DZ-oL5Ah7GeArBtYHSCb2ny7FZKs2TVfxdj3CDCrzJScrSrCwRPaKDNd-op4-qMzgKXZM2Z9eIuHr8wKKlCWnMgxqumfJYM8ZNYAw)

## **Perulangan For Of**

Jika For In digunakan untuk melakukan iterasi property atau index, berbeda dengan For Of, ini digunakan untuk melakukan iterasi terhadap isi value dari iterable object, seperti Array, String dan lain-lain**.** For of tidak bisa digunakan untuk melakukan iterasi data di object, karena object bukanlah iterable.

**Kode : For Of di Array**

![](https://lh5.googleusercontent.com/aFruOygzTF5Bxi5Cq\_tQZVdn1sNvklZuuasKRnzVYwFDrpflM2CU0vYbyC7llud6hA8k8v-M551ZPP6\_ULrSP8rK9hgwAYxXmBxAhHV8\_EeCGW-Hkok2je7n6\_5Opury5-DvQrnMinYChLQD-a1U2g)

**Kode : For Of di String**

![](https://lh4.googleusercontent.com/sACSY4gou3gmf1JcOjiYTm1RCiQc\_jmkEkoYtaS9FwYTYkrvEg-6LsCw7RpAnvEguXcyoCefqqO5QKBxmp2DNtGlBsYB7xRyLIyXGa2IVSFbVWRvxsD1qbAS-Z4kNQxoq\_usf3nhm8wsKrxI5HtXwA)
