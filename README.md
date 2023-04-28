
1BEM(human-body)
<body>
    <main>
        <div class="human-body">
            <div class="human-body__head">
                <div class="human-body__head_eyes">
                    <div class="human-body__head_eyes--color">
                </div>
                <div class="human-body__head_nose"></div>
                <div class="human-body__head_mouth">
                    <div class="human-body__head_mouth--weight-lips">
                </div>
            </div>
            <div class="human-body__torso">
                <div class="human-body__torso_stomach"></div>
                <div class="human-body__torso_left-arm">
                    <div class="human-body__torso_left-arm--scar">
                </div>
                <div class="human-body__torso_right-arm"></div>
            </div>
            <div class="human-body__legs">
                <div class="human-body__legs_left-leg"></div>
                <div class="human-body__legs_right-leg"></div>
                <div class="human-body__legs_feet">
                    <div class="human-body__legs_feet--length">
                </div>
            </div>
        </div>
    </main>
</body>
2BEM

2BEM(header,form, card)
<header class="header">
    <div class="header-container">
        <div class="header__logo"><a href=""></a></div>
        <nav class="header__menu">
            <ul class="header__menu_nav-list">
                <li class="header__menu_nav-list--pink"></li>
                <li class="header__menu_nav-list--pink"></li>
                <li class="header__menu_nav-list--pink"></li>
                <li class="header__menu_nav-list--pink"></li>
                <li class="header__menu_nav-list--pink"></li>
                <li class="header__menu_nav-list--pink"></li>
                <li class="header__menu_nav-list--pink"></li>
            </ul>
        </nav>
    </div>
</header>
<form class="form" action="https://httpbin.org/post" method="post">
        <div class="form-content">
            <div class="form-content__subheader"></div>
            <div class="form-content__field">
                <input name="name" class="form-content__field_input" placeholder="name" required />
                <label class="form-content__field_input"></label>
            </div>
            <div class="form-content__field">
                <input name="date" class="form-content__field_input" type="date" required />
                <label class="form-content__field_input"></label>
            </div>
        </div>
</form>


3-4BEM(Emmet)
 (header)
![Image alt](https://github.com/mananena/2semBEM/blob/BEM/screne1.png)
header.header>.header-container>.header__logo>nav.header__menu>ul.header__menu_nav-list>li*7.header__menu_nav-list--pink

 (form)
![Image alt](https://github.com/mananena/2semBEM/blob/BEM/screne2.png)
form.form>.form-content>.form-content__subheader>.form-content__field+input.form-content__field-input+lable.form-content__field-input^.form-content__field>input.form-content__field-input+lable.form-content__field-input

  (card)
![Image alt](https://github.com/mananena/2semBEM/blob/BEM/screne3.png)
.card>img.card__foto+.card__block>h2.card__block_text-inner+a.card__block_text-inner

1