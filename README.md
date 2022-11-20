   
    img{
    width: 300px;
}
    1. Here img will be called a SELECTOR , which means on which html element we are applying the rule;
    2. {    } this whole snippet is called Declaration Block
    3. width : 300 px this whole line is called Declaration , 
       declaration are the style rule and are written using a property value pair separated with a colon
       and ending with a semicolon to endicate that the rule is complete
    4.  width -> it is called property which refers to the style characteristic to be applied to the element
    5. 300px  -> is refer as value , this is specific to property


##  COLOR

### rgb() and rgba()

    1. rgb(): the hexadecimal value of a color is combination of rgb which means if a color value is #ff0000 
        the first two digit represents
        red, after that two digit represents green , and last two blue,
    2. if the value is not equal to six then last remaining all digit value will be added back  by 0
       example #ff will be #ff0000
    3. The value of rgb range from 0 to 255 and 0 to 100%;
    4. to add opacity we use the extra a in rgb and fourth value in percentage ex rgba(0, 0, 0, 1) the last 
        one represents 1 opacity means 100%

### hsl() and hsla()


    1. hsl(): it defines a color by its hue, saturation, and lightness 
    2. hsla(): hsl also inclueds optional alpha component
    3. the hue is specified as an angel( zero  or 360 degree means red ,  green equal 120 degree , and blues equal 240 and so on ... )
    4. the value can be declared with or without the degree unit ex hsl(270deg, 60%, 70%)
    5. saturation : it is the second value , it is represented with percentage
                     ( 100% is full saturation , 0% is shade of gray and 50 is normal)
    6. lightness : it is the third value and also represented by percentage 
                    (100% is white , 0% is black , 50% is black )
    7. the alpha a can be represented in decimal or percentage 

## Selector
 to select a element on which style will be applied
 1. *  :- it selects all the element it is universal  ex: *{ color: red;}
 2. element selector : ex h1 , h2, body , p and so  ex:   h1{color: red;}
 3. class : use the class name from the html element which is written inside the element tag i.e class="heading"
            dot is used in css to select class . ex:-   .heading{color: red;}
            multiple class can be combined ex .className1.className2 (without space) the css will only applicable when bot 
            the class is present in a element tag
4.  id : # is used in css to select 
         only one for one page
5. nested : just use the either element name or class name or combination . but they should be seperated by a space .
         exampl :- .className p{
            colo: red;
         }

         tips: think like it is a dom tree
6. grouped : grouped by comma 
7 . combined : ex h1.p
