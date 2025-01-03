# CodeTheWeb

# Refer here for shortcuts
https://docs.emmet.io/cheat-sheet/

https://react.dev/reference/react

# HTML
a: (hit tab) href -> used to add a hyperlink reference
br -> used to break lines
hr -> used to draw a horizontal line
pre -> used to write the text as it is with spaces or line changers
strong/bold -> used to make that particular word bold
i/em -> slanting word
sub/sup -> For writing H2O(2 will be written below if we write <sub></sub>). For writing anything as an exponent we use sup
del -> cuts that thing just as a price tag
mark -> highlight
style="text-align: center;"
#in the head tag above the title write link:css
q -> add quotation ""
abbr -> when you hover over the abbreviation the full form appears
address -> defines contact information. Usually renders in italic
cite -> defines title of a creative work like name of a book. Renders in italic
<bdo dir="rtl" -> the text is printed from left to right or right to left
<img src="link here" width="" alt="no image">
table>tr>th*3(hit tab)
in style you can write tr:nth-child(even) {
                                            background-color:    ;
                                            }//the nth(even indexed) child will appear to be of that color

ul/ol/dl(datalist)
span is inline-> does not take full space block element does
class is selected using (.)
ids using (#)----> used only once
iframe -> used to load one web browser into another
nav defines set of navigation links

label -> uss box ke upr aata h . Here for with the same id as that of input and whenever you click at that label that input box is highlighted
input:text(hit tab) -> placeholder gives that thing in the input box
select(hit tab) -> id="multiple"
within select block
option(hit tab) value=" " vscode
select -> we can create dropdown menu
option -> we can create options of dropdown
textarea-> used for multiline comments
fieldset -> used for grouping
legend -> used for giving captions
type is very important in input tag
id of input tag and label ka for is same

# CSS

padding -> used to generate spaces around an elements content
html {
    background: url(paste some address of image to make the whole image cover the whole background)

 id > class -> in terms of specificity

 h1,h2,h3 -> means select all three
 ul li-> inside ul go to the elements having li tag
 header > a -> only select a inside  of header
 img + p -> selects only the first sibling 
 h1:hover { bg-color} -> when you hover over that particular element it will change the color


 The box-sizing property can be used to adjust this behavior:

content-box gives you the default CSS box-sizing behavior. If you set an element's width to 100 pixels, then the element's content box will be 100 pixels wide, and the width of any border or padding will be added to the final rendered width, making the element wider than 100px.

border-box tells the browser to account for any border and padding in the values you specify for an element's width and height. If you set an element's width to 100 pixels, that 100 pixels will include any border or padding you added, and the content box will shrink to absorb that extra width. This typically makes it much easier to size elements.

 # Read about positions(mdn) and flex(https://css-tricks.com/snippets/css/a-guide-to-flexbox/)




