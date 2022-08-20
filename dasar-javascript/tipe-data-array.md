# Tipe Data Array

Array adalah tipe data yang berisikan kumpulan data

Array di JavaScript memiliki sifat dinamis, artinya datanya bisa bertambah dengan sendirinya saat kita memasukkan data ke dalam Array

### **Diagram Array**

![](https://lh3.googleusercontent.com/dZ7WbflDc7uuSmiExGHllAqbgDudDTMMCk-mABwzRxjYNza1eMAq\_b3\_48xfgzU8GX-FefwQhqwe3KHsXkWGML7YtW6AxWVOU2t0f5zKy5kZhcwJt0Vkz\_xfErQEDdeIcuEBxdi7tYhLeRjz34X4Ew)

> **Kode : Membuat Array**
>
>

![](https://lh4.googleusercontent.com/ELPx-ZVIYDmKdUdKQtGghjfZG01yQst1r337h9luzh-MagBpyNNguoSnkOn5hbZ\_xxm9v0KRM9PQaTWaDLnF1vL56H8Jwr2XCQgE5w9qp9-lEJxHysOKfsbY9Kv-C1fHUQ0C0zNHe21zpxvU1KKZSg)

### **Cara Kerja Array**

1. Setiap data di Array akan disimpan dalam posisi berurutan, dimana urutan pertama dimulai dari nomor 0
2. Setiap kita menambah data ke Array, otomatis data akan disimpan di urutan terakhir
3. Urutan di Array, kita sebut dengan index

**Cara Kerja Array**

![](https://lh5.googleusercontent.com/z1mFvj9NOtrvLJoTGFMFEf6WOskqdD4Yl0T2C6Vn\_TIMumFaYQs9zXbkOY710kWSAg8VJ1RTsBPfW5\_IupInvH\_w1nVtvDzHqgTmC6SB7m\_CBdpsu4wMnsDoiGFUVUpfR7EZ8XvSOvpsQBPDh3AP-g)

**Kode : Menambah Array**

![](https://lh4.googleusercontent.com/pmMhPVA4mQVM7p\_esuY7y88gtLuXsPFHzRU8JS6OmuqhOGyqR7QMCRmNZxVueqpjYmHrqzC5vKMYOXoZt-hKt0Rr9-O33nbNH2aK1uTVLA-0tB7pdJuYViCsMpdI9VVrPdieu4V03iYjckzHNLSnYA)

### **Operasi di Array**

| Operasi                   | Keterangan                                                     |
| ------------------------- | -------------------------------------------------------------- |
| **array.push(value)**     | **Menambah data ke Array**                                     |
| **array.length**          | **Untuk mendapatkan panjang Array**                            |
| **array\[index]**         | **Mendapat data di posisi index**                              |
| **array\[index] = value** | **Mengubah data di posisi index**                              |
| **delete array\[index]**  | **Menghapus data di posisi index, namun index tidak bergeser** |

**Kode : Operasi di Array**

![](https://lh3.googleusercontent.com/qdPI8gZ7ekX0Me0E7onyUs-WIGI6uDolqA21BdzHSxa\_EDa4BYCmxmL9Cg5idw5qMfqefkdOB-FJJU8rJRYi\_mlPtA9czliJt8kfes9F4tYgssVxFzW9GOWk0e6pJ\_ecX2RRORzDmB9EO0owONclUg)

{% hint style="warning" %}
**Perlu Diingat**

Data di dalam Array tidak ada batasannya harus data apa

Jadi kita bisa memasukkan data apapun ke dalam Array

Bahkan kita juga bisa memasukkan Array ke dalam Array jika kita mau
{% endhint %}
