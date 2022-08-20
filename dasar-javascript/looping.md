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

