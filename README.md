# jQuerry

1. Basic jQuerry and Boostrap Integration
2. jQuerry ready and click
3. html,css, child, hide and length : innerHTML and Number of element selected
    All Selectors:
        * $('p') : One element
        * $('p div a') : more elements
        * $('#id') : by id
        * $('.class') : by class
        * $('.parent>child')
        * $('#main h1+h2') : h2 Sibling between of h1
        * $('p[class]') : paragraph has class
        * $('a[href="#"]') : all the a with href='#'
        * $('a[href!="#"]') : all the a without href='#'
        * $('a[href^=http]') : all the  href= start with http (Externam Links) in a
        * $('a[href$=org]') : all the  href= end with org in a
        * $('ul li:first') : First Element in Every list(ul) : first, last, even, odd, eq(n) //nth element,     lt(n) //till nth elem, gt(n) //greater than nth elem, 
        * $(':input') : select all input types include input, button, select, option ...

    All methods:
        * $(document).ready(function(){....}) : ready elemnt
        * $('p').html("....") : inner HTML
        * $('p').css('...', '...') : add style
        * $('p').length : Number of element selected
        * $('p').hide() : hide element also hide(2000) : 2000ms
        * $('p[class]').addClass("W3-RED") : Add Class to Element to which elements has class
        * $('p').show() also show(2000) : 2000ms
        * $('p').hide(2000).show(2000) : can add more than 1 methods