# Daria Shcherbinina
## Contacts
* __Phone__: +7(968)-112-20-14
* __Location__: Chelyabinsk
* __Email__: [dakis1408@gmail.com](dakis1408@gmail.com)
* __GitHub__: [SnovaDasha7](SnovaDasha7)

## About me
I am a civil engineer by education. But I decided to change my professional activity and become front-end developer. I really want to become a cool front-end developer. And improve your English level.

## Skills
* HTML
* CSS
* JS (basic functions, JQuery)
* PHP
* Figma
* Git
* I use it for work "Php.Storm"
* I know how to make adaptive websites
* 

## Code Example

#### HTML example
````
<div class="search-result-page container">
    <div class="search-null">
        <div class="search-null-img d-flex-center">
            <img src="/local/templates/public/img/search-null-img.svg" alt="/" title="/">
        </div>
        <h2 class="search-null-title">Кажется, этого еще нет в нашем ассортименте :(</h2>
        <div class="search-null-text">
            Проверьте, что все написано правильно или попробуйте другие ключевые слова.
            <br/>
            <br/>
            А мы тем временем постараемся сделать так, чтобы это сообщение появлялось как можно реже и вы всегда находили то, что искали :)
        </div>
        <div class="search-null-btn btn">
            <a class="d-flex-center" href="/">Вернуться на главную</a>
        </div>
    </div>
</div>
````

#### CSS example
````
.show-menu-btn{
    width: fit-content;
    width: -moz-fit-content;
    justify-content: flex-start;
    position: relative;
    cursor: pointer;
}

.show-menu-btn:before{
    position: absolute;
    font-size: 14px;
    line-height: 14px;
    top: unset;
    right: -24px;
    -webkit-transition: all 0.3s;
    -moz-transition: all 0.3s;
    -ms-transition: all 0.3s;
    -o-transition: all 0.3s;
    transition: all 0.3s;
    -webkit-transform: rotate(90deg);
    -moz-transform: rotate(90deg);
    -ms-transform: rotate(90deg);
    -o-transform: rotate(90deg);
    transform: rotate(90deg);
}
````

#### JS example
````
$(document).on("click", ".show-more-btn", function () {

        var btnTitleOld = $(this).text();
        var btnTitleNew = $(this).data("title");

        $(this).text(btnTitleNew);
        $(this).data("title", btnTitleOld);

        $(this).toggleClass("open");
        $(this).parent().find(".main-catalog-sections-wrap").toggleClass("open");
        $(this).parent().find(".main-catalog-sections-wrap .main-catalog-section:nth-child(n + 4)").slideToggle(300);
    });
````

## Experience

I have worked with several commercial projects. Below are links to some of them.
* [https://new.funburg.ru/](https://new.funburg.ru/) This project is still in the process of implementation.
* [https://nir-vanna.ru/](https://nir-vanna.ru/)
* [https://stolnik24.ru/](https://stolnik24.ru/)

## Education

* __University__: South Ural State University
* __Courses__: 
  + SoloLearn (HTML, CSS, JS, PHP)
  + NovaSphere (HTML, CSS, JS, PHP, Git, Bitrix Framework, DevOps)

## English
My English level is A1. The conversational part is hard for me. I understand English better than I speak it myself.