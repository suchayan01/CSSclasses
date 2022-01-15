# CSSclasses
Css


same styling migh appear different in different browsers
this is purely rendering logic and default styling


cascading rule in order of increasing preserence
1. browser default
2. external style sheet
        in case multiple stylesheets have adressed same tag rule says pick the last name file inside head tag of that file
        if same file has diff rule for same tag again lst one to show up with the same property gets overriden while those not maintioned will be taken not rest above tags


        ****** in case user want to make a style attr immutable add !important
3. infile style tag in header
4. inline styling
------------------------------------------
http://www.csszengarden.com/214/page1/
--------------------------------------------
color Convention
Avoid color name for project because diff browser has different shades
way 1 : hexadecimal starte with pound sign then 6 digits [most commonway of using color]
way 2 : rgb0(0,0 ,0 ) -> (1,1,1)    or use rgba(0,1,1,0.5) {a-> alpha tranparency a see through effect}
try using proper color contrast for accesbility 

site to verfity - https://wave.webaim.org/

Font family
common used fonts - Helvetica, Courier, "Courier New", "Comic Sans MS", cursive or Verdana

If we choose to use custom font from an external url see below syntax

@font-face{
    font-family: mySpesialFont
    src: url('local path/ link')
}

now reference it in the tag
h1{
    font-family: mySpecialFont;
}

font-style
1. Normal - default
2. Italic
3. Oblique - type of Italic

font-variant
1. normal
2. small-caps  / no matter what case you write browser will show it as upper case

font-size:  less frequently used
xx-small, x-small, small, smaller
medium
larger, x-large, xx-large, larger

most used to size is pixels (20px, 35px)
also use percentage

color
foreground or test color
background - bg color

bg color for h1 is entire page width while for span just the background of the content within the span tag

test Align 
1. Left
2. Right
3. center
4. justify


Line height
impacts space  around the text
