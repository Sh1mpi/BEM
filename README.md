# BEM
# 1 задание 
<!-- блоки -->
head
body
hands
<!--элементы  -->
head__brain
head__eyes
body__hair
body__belly-button
hands__hand
hands__nails
hands__fingers
<!-- модификаторы -->
head__eyes--color-blue
body__hair--length-short
hands__hand--tattoo
# 2-4 задание
![Alt text](header.png?raw=true "Header")
```
<!-- header -->
header.header>a.header__logo+nav.header__nav>ul.header__ul>li.header__li*6>a.header__nav-link 
```
![Alt text](form.png?raw=true "Form")
```
<!-- форма -->
form.form-sab>label.form-sab__item>input.form-sab__input+span.form-sab__span-hidden^button.form-sab__button
```
![Alt text](card.png?raw=true "Card")
```
<!-- карточка -->
li.cards__card>img.cards__img+p.cards__type+p.cards__info+p.cards__date
```
![Alt text](footer.png?raw=true "Footer")
```
<!-- footer -->
footer.footer>a.footer__logo+.footer__site-map>ul.footer__links*3>li.footer__links-item*7>a.footer__link^^^.footer__legal>p.footer__copyright+a.footer__terms
```