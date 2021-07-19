# Lenkova Iulianna
| About me                                |
| ------------- |:-----------------------:|
| Name          | Iulianna Lenkova        |
| DOB           | 26.08.1997              |
| Location      | Russia, St.Petersburg   |

| Contacts                                                 |
| ------------- |:----------------------------------------:|
| Tel.          | +79811852702                             |
| Email         | lana6797@gmail.com                       |
| GitHub        | https://github.com/Sloulama              |

## Brief description
Graduate of the Polytechnic University who wants to develop towards front-end development. In the future, I want get employed at EPAM.

## Higher Education

- **_Peter the Great St. Petersburg Polytechnic University_** | Masters Degree - Software Engineering

## Skills
- C++ - basic
- Java - basic  
- Git
- Pascal
- SQL - basic  
Familiar with Android Studio, IDEA, CLion, VS, RStudio, PostgreSQL, Linux command line, Selenium.

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

## IT Experience

| Courses                                 |
| ------------- |:-----------------------:|
| Technopolis QA Testing       | сompleted               |
| JS/FE Pre-School             | in the process          |

## Languages
- Russian - native
- English - B1
- French -  basic
