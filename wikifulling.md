## Как дополнять информацию в Wiki?

### Раздел "Клавиатуры"
Файл [_keyboards.md_](keyboards.md) – это список созданных сообществом, а так же другими русскоязычными авторами, эргономичных и эксперементальных клавиатур.  
Формируется по хронологическому принципу в под-категориях.  
В нём – краткое описание клавиатуры и ссылки на более развёрнутое.  
Оно может быть или в папке [**/Keyboards**](Keyboards), или – внешней ссылкой.
Описания клавиатур в папке – или как отдельный md-файл, или, если изображений много, в виде вложенной под-папки.  
[Шаблон описания клаватуры](/Keyboards). [Образец описания](Keyboards/x16/x16.md).

### Раздел "Авторы"
Странички авторов размкещаются в соответственной [папке](/Authors). Список авторов – в документе **[authors.md](authors.md)**  
Он формируется на основе более раннего списка из klavarog/chat  
Шаблон для самопиара – [уже есть](Authors/Author_article_tmpl.md) в соответствующей [папке](/Authors).

### Раздел "Статьи"
Это опять же – список в [файле](articles.md) из внутренних и внешних ссылок, и [папка/Articles](Articles), если статья размещается здесь.

### Раздел "Компоненты и технологии"
требует решения, насколько объёмно он будет заполнен?  
Отдельная статья на каждый компонент, который кто-нибудь и где-нибудь использовал? В сообществе? В мире?  
Или краткие обзорные статьи по каждому виду компонентов? Со ссылками на другие источники?

Разделы **Документация** и **Прошивки с контроллерами** – скорее всего, будут дополнены.
  

## Тем, кто ранее не пользовался Githab:
(важные особенности в работе!)

Что бы **внести изменения** в текст Вики 
- переходишь в корневую ветку Вики
- копируешь(форкаешь) её всю к себе в аккаунт (или на комп)
- вносишь правки и дополнения в нужные документы
- отправляешь на рассмотрение в основную ветку, откуда ты взял исходник (это Pull Request называется)
- там эти изменения должен одобрить её основатель

Сложные названия файлов – с нижним подчёркиванием или - !  

**! Через web-интефейс не возможно:**  
- удалять папки – необходимо удалить все файлы внутри
- переназывать файлы изображений – только удалить и загрузить с новым именем

**Создание нового файла из старого через переименование не работает!!!**  
Переименованием вы просто создадите новый файл, а старый, нередактированный, потеряете!  
Необходимо скопировать исходник в буфер обмена и создавать новый файл!

Для того что бы **создать папку** – пишите её название через слэш при создании нового файла  
Чтобы создать новую **папку для изображений** создавайте новый пустой файл "Новая-папка/.gitkeep" 

**Git ориентирован на работу через терминал!!!**  
  
  
