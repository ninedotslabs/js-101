# Variable

variable adalah pemberian nama pada sebuah alamat pada memori.

Cara membuat variable?

```
var name = "John"
```

variable di atas bernama "name" isinya berupa String yaitu John.

mengapa kita butuh variable? agar sesuatu dapat digunakan berulang2, maka kita simpan saja di dalam variable.

```
document.getElementById("#container_x").text = "Test"
document.getElementById("#container_x").className = "container"
document.getElementById("#container_x").append(document.getElementById("#container_y"))
```

contoh di atas betapa ngerinya ketika kita tidak menyimpan sesuatu ke dalam variable

```
var container_x = document.getElementById("#container_x")
var container_y = document.getElementById("#container_y")
container.text = "Test"
container.className = "container"
container.append(container_y)
```

lebih rapi dan mudah dibaca bukan? dan tidak ada mengulang-ulang syntax yang panjang.