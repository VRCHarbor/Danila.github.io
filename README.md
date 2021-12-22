# Отчет о лабораторных работах
# Студент группы [ИДБ-18-07](https://github.com/stankin/design-part-1/wiki/list-idb-18-07) [Лузанчук Д.Д.](https://github.com/VRCHarbor)

## <b>Лабораторная 1</b>

### UML-модель "разработки веб-сервиса"

[Файл конфигурации](https://github.com/VRCHarbor/Danila.github.io/blob/main/labWork1.rsf)

![01_A0](https://user-images.githubusercontent.com/62661818/133085138-20eae7cc-1bee-4b6e-a9df-ce20617cfaf9.png)

### Диаграмма модели

![image](https://user-images.githubusercontent.com/62661818/133085310-0649fa37-a076-4062-bc40-0b9cebae6a0b.png)

### Диаграмма прецедентов

![image](https://user-images.githubusercontent.com/62661818/133087021-70009137-e8a2-4e7b-9cdf-4d4e8ed92746.png)


## **Лабораторная 2**

### Диаграма IDF0

![01_A0](https://user-images.githubusercontent.com/62661818/147070600-bdf34115-9b56-4c56-8956-bebc5cd8a73a.png)

### Дочерняя диаграмма PDC

![02_A0](https://user-images.githubusercontent.com/62661818/147070417-905416d2-948d-472a-8af7-136cdf3de880.png)

**А1 - управлять разработкой**

Управляющая компания (УК) занимается процессами составления задач для разработчиков и тестировщиков на основании фидбеков пользователей и результатов генерации новых предложений по разработке.  

**А2 - Разработать модуль**

Разработчики по постановкам задач реализуют необходимые для работы WEB-сервиса функции и производят исправления по мере поступления запросов об ошибках со стороны тестировщиков и конечных пользователей

**А3 - Проверить готовность версии**

Тестировщики получают задачи для тестирования и производят необходимые для их реализации приготовления (составлени тестовых данных и тестовой документации), пока объект тестирования не прийдет от группы разработчиков. 


### DFD-Диаграмма процесса "управлять разработкой"

![01_A0](https://user-images.githubusercontent.com/62661818/147071093-592bd947-dc2b-4ce1-9031-7fb2563d15d5.png)

### usecase diagram

![fPB1hj9068NNTvxYpzspk8MbCLZq6LYFxGWDfMEcWox416gY2qtq0NHXNBYjn2eMAQ_mpnjvMfgcGNPtCHFuvfmpvnyOfrOQkrh68br4oNDfv99aOBMXL-B6by5YPlGg2ISw1fhE8wl4pIDZzCipyMD88DGcLAQFNejUu2fLWKpL_](https://user-images.githubusercontent.com/62661818/147077345-a10a619b-c52f-4ad7-9bbd-f16a5dd58e91.png)


## Лабораторная 3

### DFD-Диаграмма процесса "Разработать модуль"

![01_A0](https://user-images.githubusercontent.com/62661818/147082511-967773c1-c63f-4086-ab0c-68bd841b4c0c.png)

### Диаграмма последовательности

![TPFHQXD158QlEqznoBLv0I5IqmiHyKxmUf8TufhDJfoTjOW8JGegg1IyyT9MV81jxTBDLhUlSEQD_6Scj6kbK1Pcvl-_yvzpcjt2IcFBHIQAUPelfP4BabEh3RqLEsCvdS-CBlDaJsUuUluYjKhiF3H6xyURSGO9XDeaolIltWbPMfsNY](https://user-images.githubusercontent.com/62661818/147086458-aa8f7bec-abeb-443d-a8ba-1c00e14fe1ae.png)

Разработчик в процессе разработки выполняет множество действий по реализации функционала и визуала проекта. Чтобы распределить процесс разработки для работы используется git-репозиторий и KanBan-доска компании, где формируются задачи исходя из требований конечных потребителей и предложений по проекту внутри компании. Разработчик получает сформированную задачу и ТЗ по ней. При наличии вопросов разработчик выясняет различные моменты с ее составителем. По введение в суть задачи разработчик создает свою ветку в GIT-репозитории с ID своей задачи, которую он берет с последнего коммита главной ветки проекта в качестве родительского для нее. При произведении правок по проекту разработчик создает запрос на слияние (merge-request) с главной веткой проекта в GIT'е. На момент запроса производится проверка кода (Code review) более квалифицированными специалистами компании. В случае возникновения недочетов или ошибок - задача возвращается на доработку, пока не будут внесены все требуемые исправления. После code review производится слияние с главной веткой проекта. После ожидается поступление новых задач от конечных пользователей или управляющей компании (УК).

### ER-диаграмма

![fP3DJW8n58NNz2aQbYOiv6Th45QkDN5TcGeJXfQqKrce2H2Z9YxOkb7Z6w2HE1Aeht3xHdRQcJ2Ji7CrTxvpxicvRSkOY5YD8YI78HiJGKQOz2cBhr6bGth3lk2A1LqUSO7F1s5CKULO23xnf1DPYpLo4L1HHBUeaASaxH59yRyZNJ5yo](https://user-images.githubusercontent.com/62661818/147095848-7ba76ebb-7466-4a64-9a65-db4695569371.png)

Задачи являются основным двигателем в работе по совершенствованию проекта разработки WEB-сервиса и они сосстоит из: Ошибок версии, несоответствий требованиям, потоков задач, Code review и сроков.


## [Лабораторная 4-6](https://github.com/Space-Discovery/SpaceDiscoveryGame.io/wiki/%D0%9E%D1%82%D1%87%D0%B5%D1%82-%D0%BE-%D1%80%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B5-web---%D0%B8%D0%B3%D1%80%D1%8B-Space-Discovery)

