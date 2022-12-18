<div align="center">

<h1>Telematic Tableau connector</h1>

**Owner:** Zhukov Max

**Contacts:** [Maxim.Zhukov@softline.com](Maxim.Zhukov@softline.com)

</div>

> Это репозиторий кастомного коннектора данных Microsoft Power BI Custom Data Connector, разработанного [max-zorn](https://github.com/max-zorn).<br>
> Коннекторы данных создаются с использованием языка M.<br> Пожалуйста, смотрите предварительно справочные материалы [Power Query Connector Developer Reference](https://docs.microsoft.com/en-us/power-query).<br> Используйте и модифицируйте  код из  [telematics-pbi-connector/code](https://github.com/novemdata/telematics-pbi-connector/tree/main/code) под собственные нужды с помощью [official manual](https://github.com/microsoft/DataConnectors#quickstart).

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 📖 Описание

Этот настраиваемый коннектор данных  `Tableau WDC` позволяет получать и визуализировать данные из следующих методов API:
- CompareScoring (Скоринг)
- CrashList (Список аварий)
- Vouchers (Ваучеры)

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 🎯 Ожидает реализации
- [ ] первое
- [ ] второе
- [ ] третье

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 🔗 Ссылки
+ [Confluence]()
+ [Production]()
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## ☁️ Развертывание функции

Шаг 1: Получите ключ и домен для вашей учетной записи API.

Шаг 2: Скачайте файл `TelematicsAPI.mez` из репозитория [telematics-pbi-connector/build](https://github.com/novemdata/telematics-pbi-connector/tree/main/build).

Шаг 3: Скопируйте этот файл в папку `C:\Users\<Your_User_Name>\Documents\Microsoft Power BI Desktop\Custom Connectors`.

>Если папка не существует, то создайте ее.

Шаг 4: Откройте `Power BI Desktop`, и установите `"(Not recommended) Allow any..."` в разделе `Options/Data Extensions`.

<img width="800" alt="image" src="https://user-images.githubusercontent.com/40857648/116013033-9ac55300-a636-11eb-9ee5-36c9fcffb99d.png" >

Шаг 5: Перезагрузите `Power BI Desktop` и перейдите в раздел `"Get Data"`.

<img width="800" alt="image" src="https://user-images.githubusercontent.com/40857648/116012985-55a12100-a636-11eb-941f-0d7153e0daf6.png">

Шаг 6: Найдите онлайн сервис `"TelematicsAPI (Beta)` и выберите его.

<img width="800" alt="image" src="https://user-images.githubusercontent.com/40857648/116013190-7cac2280-a637-11eb-938c-7356873abb14.png">

Шаг 7: Введите URL Вашего API аккаунта.

<img width="800" alt="image" src="https://user-images.githubusercontent.com/40857648/116013284-0e1b9480-a638-11eb-8610-9f49b2303871.png">

Шаг 8: Введите `API key` от Вашего аккаунта.

<img width="800" alt="image" src="https://user-images.githubusercontent.com/40857648/116013324-4cb14f00-a638-11eb-9e4d-c559fbadf8a7.png">

Шаг 9: Теперь вы можете выбирать объекты из своей учетной записи и либо сразу загружать данные, либо сначала преобразовывать их.

<img width="800" alt="image" src="https://user-images.githubusercontent.com/40857648/116013402-afa2e600-a638-11eb-9fea-310b4c0623cd.png">

## 💻 Использование
