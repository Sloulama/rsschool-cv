# Ленькова Юлианна

| Обо мне                                 |
| ------------- |:-----------------------:|
| Имя           | Юлианна Ленькова        |
| Дата рождения | 26.08.1997              |
| Место прожив. | Россия, Санкт-Петербург |

| Контакты                                                 |
| ------------- |:----------------------------------------:|
| Tel.          | +79811852702                             |
| Email         | lana6797@gmail.com                       |
| GitHub        | https://github.com/Sloulama              |

## Описание
Выпускница СПБПУ им. Петра Великого 2021 года. Работаю учителем информатки с 2019 в средней образователной школе г. Санкт-Петербург. Заинтересована развиваться как тестировщик и frontend-разработчик.

## Образование

- **_Санкт-Петербургский Политехнический Университет Петра Великого_** | Программная инженерия - Магистр

## Опыт работы
- 2019 - по н.в. учитель информатки школы №65 с углубленным изучением французского языка.
## Skills
- C++ - basic
- Java - basic  
- Git
- Pascal
- SQL - basic  
Знакома с Android Studio, IDEA, CLion, VS, RStudio, PostgreSQL, Linux command line, Selenium.

## Code Example
```java
public class DeleteCatalogPage extends BasePage {

    private static final By deleteButton = By.xpath(".//*[@class='layer_hld mus_playlist-remove']//*[@class='form']//*[contains(text(),'Удалить')]");

    public DeleteCatalogPage(WebDriver driver) {
        super(driver);
    }

    public void delete() {
        driver.findElement(deleteButton).click();
    }

    public void check() {
        checkVisibleElement("No delete button", deleteButton);
    }
}
```

## Курсы

| Courses                                 |
| ------------- |:-----------------------:|
| Technopolis QA Testing       | сompleted               |
| JS/FE Pre-School             | in the process          |

## Languages
- Russian - native
- English - B1
- French -  basic
