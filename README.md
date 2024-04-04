Planning

```
* {
    box-sizing: border-box;
}

header.header (flex, align-items: center, border-top: green, padding: 1rem)
    img.header__image
    h1.header__title (font)

nav.nav (padding: 1rem)
    ul.nav__list (flex, justify-content: space-between, list-style: none, background-color: orangered)
        
        li.nav__item (5x, color: white)
            a.nav__link (5x - text-decoration: none)


    
    section.hero (background: url, height: 20rem, width: 100%, flex, justify-content: center, align-items: center)
        h2.hero__slogan (border: 2px solid green, background-color: white, padding: 1rem)


    main.main (flex TODO: better BEM name next time)
        
        section.ingredients (flex, flex-wrap: wrap; width: 75%, possibly article)
            
            article.ingredient (width: 15rem, padding: 1rem; margin-right: 1rem)
                img.ingredient__image
                h3.ingredient__name
                p.ingredient__description
            
            article.ingredient--featured (background-color: green; color: white)
                img.ingredient__image
                h3.ingredient__name
                p.ingredient__description


        aside.reviews (width: 25%, flex, column)
            blockquote.review (background-color: #eee, width: 80%)

            blockquote.review--last (align-self: flex-end)



.ingredient:hover, .ingredient:active {
    background-color: green;
}

box-sizing: content-box; (default for all elements)
= height of an element is the height property value + the padding top/bottom + the border top/bottom
= width of an element is the width property value + the padding top/bottom + the border top/bottom

box-sizing: border-box;
= height of the element is the height property value!
= width of the element is the width property value


✅ Create initial folder structure
    - index.html
    - css/main.css
    - assets/images/background.jpeg


Initialize Git repo
- ✅ git init
- ✅ git add
- ✅ git commit
- ✅ create github repo
- ✅ git remote add origin
- ✅ git push

```