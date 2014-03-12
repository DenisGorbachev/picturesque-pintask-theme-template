Picturesque theme template for Pintask
=========================

Using pictures for board backgrounds is easy. Just specify `https://denisgorbachev.github.io/picturesque-pintask-theme-template/picturesque.css` as the first file and your CSS for board background as the second file when adding your extension on http://pintask.me/.

This versatile template is only a few lines of code:

```css
html
  .top-content
    box-shadow 0 5px 15px 0 #97989c
    z-index 2000
  
  .starring-as-board-list, .board-edit form, .board-calendar .board-calendar-message, .list-switcher-wrapper
    background-color rgba(236, 239, 244, 0.95)
  
  .board-store
    .starring-as-board-list
      border-color rgba(236, 239, 244, 0.95)
  
  .starring-as-board-lists > .starring-as-board-list
    margin-left 15px
    margin-top 15px
    .board-list-header
      margin-top 10px

```

_This theme template is written in [Stylus](http://learnboost.github.io/stylus/). Plain old [CSS version](https://github.com/DenisGorbachev/picturesque-pintask-theme-template/blob/master/picturesque.css) is available, too._
