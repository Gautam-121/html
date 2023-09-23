make html file - done
make boilaplate code - done
understand tag - done
understand h1-h6 - done
understand p - done
understand br - done
understand img - done
understand a - done
understand div - done
understand id and class - done

<jobhi></jobhi>  =  jobhi tag

div = div ek rectangular box hota hai jiske pass width full hoti hai pr height zero hoti hai

div = div ki height apne children ke height ke barabr hoti hai

suppose div ke under 2 children hai jinki height 10px and 20px hai to div ki height sum of all children hoti hai yani 30px 

div height = child1 height + child2 height + so on..

id = id is unique to full html file

class = class is not unique it group the tag of html using class 


# Love Babbar Series

Doctyle html -> Batata hai ke ye file index.html wo html:5 me likhi hu hai
<html></html> --> html ek root element hai jo btata hai pura ka pura contaent mere ander likha jayega
<head></head> ---> head tag btata hai ki jitna bhi meta data hai wo mere under likh jayeng
<body></body> ---> body tag btata hai ki jo bhi contaent browser me display hoga wo mere ander likha jayega

element --> <body> containt </body> , only <body></body> --> ise tag khte hai

<img src="" alt = "" />
<h1 class="head" id="heading"></h1>

Attributes (src , alt)--> Attributes contain extra information about the element that won't appear in the content


tags => what? => markup entity ==> provide structure , meaning , formating

meaning => tags into two parts => sementic tag and non-sementic tag

non-semantic tag => those tag don't provide any meaning what the tag do

Ex => div , spane

sementic tag => those tag provide meaning what this tag do

Ex=> header , footer , main , article , aside , section , nav , fotm  and so on

h1-h6 , p , a , ul , ol , table , tr , td , img , form , input , option , select

formating tag => br , hr , strong , em , sub , sup , title , u , s , b , i , pre 

# can We use multiple h1 tag in page?
Yes, you can use multiple <h1> tags in HTML, but it is generally considered a best practice to have only one <h1> tag per page. The <h1> tag is used to define the main heading of a page and should describe the content of the entire page. Using multiple <h1> tags can make it harder for search engines and screen readers to understand the structure of your page . However, with the introduction of HTML5, using multiple <h1> tags within different sections of a page is now accepted as semantically correct.


emmet --> shorcut to generate full code

emmet abbr
 element -> nested ==> "> --> p>img 

 ul>li*3

 table>tr>td*2

 table>(tr>td*3)*3

 article+section 
    <article></article>
    <section></section>

p{this is text} <p>This is Text</p>

p#para1 <p id=para1></p>

p.love <p class="love"></p>

article.cars.range.rover <article class = "cars range rover"></article>

a{click here} <a href = "">Click Here</a>

{} > + *

div tag ==> ka use aap kr skte ho
division create krne ke liye , ye ek
generic container hai , jo wrapping ke liye use hota hai

 <div>
        <p></p>
        <header></header>
        <main></main>
        <footer></footer>
</div>

Block and Inline Element 

Block elment --> always start with nect line
aur wo pure screen ki width contain krta hai

Inline Element --> start with same line and wo 
jitna cobtain hai utna hi width occupied krta hai

# how can i change block elment into inline and inline into block
So css display property we use for interchanging block to inline and inline to block
display : inline (converting Block elment into inline element)
display : Block (converting Inline Element into Block element)


# What is Table
Table is Arrengement of Row and Column

table
thead -- Header of arrengement use thead me insert krni hai
tbody -- tbody jisme actual contain present rhenga
tfoot -- tfoot unka sum koi operation 

tr -- tr tag jisse row create kr sakte hai
td -- table data add kr sakte hai , as column
th -- th thead me jo heading hai us heading ko bold main heading dikhane ke liye ise use krte hai