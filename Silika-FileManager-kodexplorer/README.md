 ## Silika-FileManager
Во время выполнения теста неизбежно будут генерироваться файлы которые куда нибудь надо сохранить.
В нашем распоряжении 
Модуль Go Docker Runner
POST:>> /fsapi/runKod 
 
Xela07ax (R)  | Модуль
------------- | -------------
<img src="artworks-arq96i.jpg" width="150"/>   | Реализация Ui, для файлового менеджера  Go Silika Api. 

 ### О проекте

 Так как модули для js не интегрируются с коробки, с гитхабом, проект будет завернут в готовый каркас SilicaFront.
 Описание будет ниже.
 
 Каркас (платформа) - Vue Js, Quasar Dev  
Протокол обмена сообщениями: Http 1.1 в связке с Axios, технология "Longpool", логика которого прописана в "Store -> Actions" (можуль Vuex)

## Запуск
```sh
λ cd sources\
λ yarn
λ quasar dev
or
λ npx quasar dev
```
* При возникновении ошибки:  
```
"quasar" не является внутренней или внешней
командой, исполняемой программой или пакетным файлом.
```
используйте вариант λ npx quasar dev или установите Quasar Cli глобально  

* Информация о тестовой среде:
```
λ quasar dev
    Dev mode.......... spa
    Pkg quasar........ v1.12.13
    Pkg @quasar/app... v2.0.6
    Debugging......... enabled
λ node -v
    v14.14.0
λ yarn -v
    1.22.5
λ systeminfo
    Название ОС:                      Майкрософт Windows 10 Pro
    Версия ОС:                        10.0.19041 Н/Д построение 19041
    Дата установки:                   16.10.2020, 11:20:58
```

* Вывод успешного запуска
```
λ npx quasar dev
    DONE  Compiled successfully in 9625ms                                                                                           13:51:32
    
    
     N  App dir........... C:\Users\Tester\Projects\GitHub\Silika-FileManager\sources
        App URL........... http://localhost:8080
        Dev mode.......... spa
        Pkg quasar........ v1.12.13
        Pkg @quasar/app... v2.0.6
        Transpiled JS..... yes (Babel)
    
    i ｢wds｣: Project is running at http://0.0.0.0:8080/
    i ｢wds｣: webpack output is served from
     App · Opening default browser at http://localhost:8080
```


