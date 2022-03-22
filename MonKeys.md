# MonKeys

## Страницы тестирования

* [Лента](#Feed) (Л)
  * Кнопка раскрыть
* [Лайки](#Like) (Л)

* [Совпадения](#Match) (В)
* [Чаты](#Chats) (В)

* [Регистрация](#Signup) (М)
* [Логин](#Login) (М)
* [Тапбар](#Tapbar) (М)
  
* [Профиль](#Profile) (И)
* [Настройки и создание профиля](#Settings) (И)

### <a name="Feed"></a> Лента

#### &emsp;Кнопка раскрыть

#### &emsp;&emsp;Позитивные
##### &emsp;&emsp;&emsp;Нажатие на центральную кнопку на карточке должно открыть подробное описание
<div style="width: 100%; display: flex;">
<img src="assets/feed/Screenshot 2022-03-13 at 21.40.47.png" width=200 style="margin: 0 auto;"> </div>

##### &emsp;&emsp;&emsp;После нажатия открывается подробное описание
<div style="width: 100%; display: flex;">
<img src="assets/feed/Screenshot 2022-03-13 at 21.41.19.png" width=200 style="margin: 0 auto;"> </div>


#### &emsp;&emsp;Негативные

### <a name="Like"></a> Лайки

### <a name="Match"></a> Совпадения

* Поле "Поиск"
  * ✅ При вводе символов выводятся все совпадения с таким вхождением
  * ❌ После удаления введенных символов в поиск, список совпадений должен иметь прежний вид

     БАГ: пропадает выделение новых совпадений
    <div style="width: 100%; display: flex;">
      <div style="display: flex; flex-direction: column; margin-right: 20px">
        <img src="assets/match/1.jpg" width=200>
        <span>до ввода текста в поле "Поиск"</span>
      </div>
      <div style="display: flex; flex-direction: column; align-items: flex-start;">
        <img src="assets/match/2.jpg" width=200>
        <span>После удаления симоволов из поля "Поиск"</span>
      </div>
    </div>
* Список совпадений
  * ✅ При нажатии на совпадение открывается чат с человеком
  * ✅ Совпадения с людьми, с которыми еще нет чата, подсвечиваются как новые
  * ✅ При нажатии на новое совпадение, оно перестаеит подсвечиваться и открывается чат

### <a name="Chats"></a> Чаты

* ✅ При нажатии на превью чата открывается чат


### <a name="Signup"></a> Регистрация

### <a name="Login"></a> Логин

### <a name="Tapbar"></a> Тапбар

### <a name="Profile"></a> Профиль

### <a name="Settings"></a> Настройки и создание профиля
