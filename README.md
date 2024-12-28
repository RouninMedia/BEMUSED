# Bemuse
***BEM**, **u**sing **s**everal **e**xtensions* (**Bemuse**) is a slightly-tweaked version of **BEM**, incorporating:

 - one or two ideas from Daniel Tonon's **ABEM**
 - one more original idea

_____

## An Example of CSS written using Bemuse

_____

## Ideas borrowed from ABEM and utilised in Bemuse

https://css-tricks.com/abem-useful-adaptation-bem/

____

## One more original idea utilised in Bemuse

Note: https://frontstuff.io/in-defense-of-utility-first-css
 
See:

 1. `/* Oops, looks like duplicate rules down there! */` )
 2. If you duplicate the `.card--ribbon` class, your code isn’t DRY anymore. 

**N.B.** The slightly different _modifier_ syntax in **Bemuse** originally arose from a misunderstanding of how **BEM** modifiers were supposed to work and the mistaken interpretation that they required _extensive duplication_ in the CSS - whereas, in fact, they require _minimal duplication_ in the HTML. That misunderstanding has long since been cleared up, but, to some front-end developers at least, **Bemuse** modifiers will continue to feel preferable.
