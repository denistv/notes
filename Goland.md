### Отладка с помощью Delve
В поставке Goland может идти устаревший отладчик. Чтобы пофиксить, [устанавливаем dlv](https://github.com/go-delve/delve) в свой юзерспейс и прописываем в файле `/home/denistv/GoLand-2022.2.6/bin/goland64.vmoptions` путь до установленного бинаря **dlv**:
```
-Ddlv.path=/home/denistv/go/bin/dlv
```
