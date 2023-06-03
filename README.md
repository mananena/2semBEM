
## 1 BEM(human-body)
```
<body>
    <main>
        <div class="human-body">
            <div class="human-body__head head">
                <div class="head__eyes"></div>
                <div class="head__nose"></div>
                <div class="head__mouth">
                    <div class="head__mouth_red"></div>
                </div>
            </div>
            <div class="human-body__torso torso">
                <div class="torso__stomach"></div>
                <div class="torso__left-arm">
                    <div class="torso__left-arm_scar"></div>
                </div>
                <div class="torso__right-arm"></div>
            </div>
            <div class="human-body__legs legs">
                <div class="legs__left-leg"></div>
                <div class="legs__right-leg"></div>
                <div class="legs__feet">
                    <div class="legs__feet_tatoo"></div>
                </div>
            </div>
        </div>
    </main>
</body>
```
## 2BEM

### 2BEM(header,form, card)
```
<header class="header">
    <div class="header__wrapper">
        <a href="" class="header__logo logo"><img src="" alt="" class="logo__image"></a>
        <nav class="header__navigation navigation">
            <ul class="navigation__list">
                <li class="navigation__item"><a href="" class="navigation__link"></a></li>
                <li class="navigation__item"><a href="" class="navigation__link"></a></li>
                <li class="navigation__item"><a href="" class="navigation__link"></a></li>
                <li class="navigation__item"><a href="" class="navigation__link"></a></li>
                <li class="navigation__item"><a href="" class="navigation__link"></a></li>
                <li class="navigation__item"><a href="" class="navigation__link"></a></li>
                <li class="navigation__item"><a href="" class="navigation__link navigation__link--cart"></a></li>
            </ul>
        </nav>
    </div>
</header>

<section class="callback">
    <div class="callback__contacts-wrapper">
    </div>
    <div class="callback__form-wrapper">
        <h3 class="callback__title"></h3>
        <p class="callback__text"></p>
        <form action="" class="callback__form form">
            <input type="text" class="form__input">
            <input type="text" class="form__input"><input type="text" class="form__input">
            <input type="text" class="form__input">
            <textarea name="" id="" cols="30" rows="10" class="form__input form__input--textarea"></textarea>
            <button type="submit" class="form__button form__button--submit"></button>
        </form>
    </div>
</section>

<section class="about-me">
    <h2 class="about-me__title"></h2>
    <p class="about-me__text"></p>
    <a class="about-me__link about-me__link-" href=""></a>
    <ul class="about-me__cards cards">
        <li class="cards__about-card about-card">
            <img src="" class="about-card__photo" alt="">
            <h3 class="about-card__title"></h3>
            <a href="" class="about-card__link"></a>
        </li>
        <li class="cards__about-card about-card">
            <img src="" class="about-card__photo" alt="">
            <h3 class="about-card__title"></h3>
            <a href="" class="about-card__link"></a>
        </li>
        <li class="cards__about-card about-card">
            <img src="" class="about-card__photo" alt="">
            <h3 class="about-card__title"></h3>
            <a href="" class="about-card__link"></a>
        </li>
    </ul>
</section>

<section class="cushion">
    <ul class="cushion__price-list price-list">
        <li class="price-list__item item-cushion">
            <img src="" class="item-cushion__photo" alt="">
            <h2 class="item-cushion__title"></h2>
            <p class="item-cushion__numbers"></p>
        </li>
        <li class="price-list__item item-cushion">
            <img src="" class="item-cushion__photo" alt="">
            <h2 class="item-cushion__title"></h2>
            <p class="item-cushion__numbers"></p>
        </li>
        <li class="price-list__item item-cushion">
            <img src="" class="item-cushion__photo" alt="">
            <h2 class="item-cushion__title"></h2>
            <p class="item-cushion__numbers"></p>
        </li>
        <li class="price-list__item item-cushion">
            <img src="" class="item-cushion__photo" alt="">
            <h2 class="item-cushion__title"></h2>
            <p class="item-cushion__numbers"></p>
        </li>
        <li class="price-list__item item-cushion">
            <img src="" class="item-cushion__photo" alt="">
            <h2 class="item-cushion__title"></h2>
            <p class="item-cushion__numbers"></p>
        </li>
        <li class="price-list__item item-cushion">
            <img src="" class="item-cushion__photo" alt="">
            <h2 class="item-cushion__title"></h2>
            <p class="item-cushion__numbers"></p>
        </li>
    </ul>
</section>
```

### 3-4BEM(Emmet)

 (header)

![Image alt](screne1.png)

`header.header>.header__wrapper>a.header__logo.logo>img.logo__image^nav.header__navigation.navigation>ul.navigation__list>li.navigation__item*6>a.navigation__link^li.navigation__item>a.navigation__link.navigation__link--cart`

 (form)

![Image alt](callback.png)

`section.callback>.callback__contacts-wrapper+.callback__form-wrapper>h3.callback__title+p.callback__text+form.callback__form.form>input.form__input*4+textarea.form__input.form__input--textarea+button:submit.form__button.form__button--submit`

  (card)

![Image alt](card.png) 

`section.about-me>h2.about-me__title+p.about-me__text+a.about-me__link+ul.about-me__cards.cards>li.cards__about-card.about-card*3>img.about-card__photo+h3.about-card__title+a.about-card__link`

![Image alt](cushion.jpg)

`section.cushion>ul.cushion__list.price-list>li.price-list__cushion-card.cushion-card*6>img.cushion-card__photo+h2.cushion-card__title+p.cushion-card__numbers`