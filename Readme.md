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

Ex => div , span

sementic tag => those tag provide meaning what this tag do

Ex=> header , footer , main , article , aside , section , nav , form  and so on

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
th -- th thead me jo heading hai us heading ko bold main hea/ding dikhane ke liye ise use krte hai

# Forms -- what is Forms

forms -- structure --> To collect user Input

<form> --> to create HTML forms for user input

<input> -- Many Forms 
     type - radio , submit , checkbox , date 
            text , email , password 
    id = map with for of label
    name = us value ko puchne ke liye tere under user ne kya data dala wo dekhne ke liye
    placeholder = to inform user yha kya insert krna hai
    value = us input filed ki value kya hai

<input type"text" id="email" name="mail" placeholder="Enter Your Mail" value=""/>

<Label> --> Ka for="" attrribute input ke id=""
attribute se one to one map krna hai


# Form Element Ke Under Aur Kya kya insert Kr Sakta hu
   
    - Input
    - Label
    - select  --> Drop Down Box create krne ke liye --> Us box me value dalne ke liye
        -- select ke under hm option likhte hai
    - button
    - textArea - ek description content user se lina hai to textArea Use krte hai
    - fieldset -- fieldset ka use kisi contain ka wrapping krne ke liye use kiya jata hai
    - legend --> use wrapping container ko caption ke liye

# suppose muzhe dropdown ke under multiple dropdown select krne ho -->> it is possible in select option , if this possible so how can do

Yes , we can select multiple option in select dropdown , using boolean attribute "multiple"

# input type
  - text
  - button
  - radio
  - checkbox
  - password
  - email
  - date
  - img

# Media in HTML
  <!-- Add Image To html page -->
    <img src="" alt="" width="" height=""/>

    <!-- Add Video To HTML -->
    <video src=""controls autoplay muted></video>

    <video controls autoplay muted loop>
        <source src="" type="video/mp4"/>
    </video>

    <!-- Add Audio To HTML  -->
    <audio src="" controls autoplay muted loop></audio>

    <audio controls autoplay muted loop>
        <source src="" type="audio/mp3"/>
    </audio>

    <iframe src="https://www.youtube.com/embed/te7iK3-f0IY" width="450 height="250"><iframe>