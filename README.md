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
way 2 : rgb0(0,0 ,0 ) -> (1,1,1)    or use rgba(0,1,1,0.5) {a-> alpha tranparency a see throuhj effect}