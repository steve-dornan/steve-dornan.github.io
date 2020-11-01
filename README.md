<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Year 8 HTML & CSS Units 1-3</title>
        
        <!-- Insert the CSS here within thye <style></style>            tags -->
        
        <style>
        
        /* Selecting by the Element Tag (Element Selector) */ 
         
            h1 { color:rgb(33, 109, 222);}
            
            h2 {color:rgb(25, 105, 21);}
            
            h3 { color:rgb(29, 84, 161);}
            
            p { color:rgb(94, 13, 148);}
            
            li {color:rgb(173, 33, 2);}
            
            body {background-color:rgb(181, 235, 205);}
            
            
        /* Selecting by the ID Tag (ID Selector) */ 
       
         #learning-intent{background-color:rgb(132, 189, 152);
             text-align: center;
         }
         
         #HTML {background-color:rgb(118, 176, 138);}  
         
         #CSS {background-color:rgb(132, 189, 152);} 
         

        /* Selecting by the Class Tag (Class Selector) */ 
        
        .lists {background-color:rgb(161, 209, 178);}
        
        .bold {color:rgb(36, 36, 227);}
        
        .title {text-align: center;}
        
        .para {text-align: center;}
        
        .picture {text-align: center;}
        
        
        .table {text-align: center;}
         
            
        </style>
        
</head>
    <body>
    
    <!-- The Largest of the Heading Tags -->
    
    <h1 class="title" id="return">HTML & CSS @ MLC Term 4 2020</h1> 
    
    <!-- Internal links  -->
    
    <p class="para">This term in <strong><em>Digital Technologies</em ></strong> we are learning how to use <a href="#Topic1"    >HTML</a> and <a href="#Topic2">CSS</a> to create webpages      .</p>
     
    <p class="para">We are using <strong>Khan Academy</strong> as our            online program for learning and the creation of webpages.</p     >
     
    <p id="learning-intent">We are learning about the               following;</p>
      
    <!-- External Links -->
      
    <ul>    
    <li id="HTML"><strong class="bold"><a href="https://en          .wikipedia.org/wiki/HTML#:~:text=Hypertext%20Markup%20Langua     ge%20(HTML)%20is,scripting%20languages%20such%20as%20JavaScr     ipt.">HTML</a></strong> Basics </li>
    <li class="lists">Text Emphasis</li>
    <li class="lists">Lists</li>
    <li class="lists">Images</li><br>
    </ul>

    <!-- External Links -->

    <ul>
    <li id="CSS"><strong class="bold"><a href="https://en.wikipedia.org/wiki/CSS">CSS</a></strong> Basics</li>
    <li class="lists">Adding Colour</li>
    <li class="lists">CSS ID Selectors</li>
    <li class="lists">CSS Classes</li><br>
    </ul>
    

    <!-- Image with Alt text and size adjustment -->

    <img src ="https://miro.medium.com/max/4800/1*cbjT-JtrNb-0FtjxS_we-g@2x.jpeg"alt="Norway"height="200" > <br>

    <p class="picture" id="Topic1"><strong class="bold">HTML</strong> allows a computer programmer to create structured documents by controlling the format of text such as <strong class="bold"><em>headings, paragraphs, lists, links, quotes,</em></strong> and other items.</p>

    <p class="picture"
    id="Topic2"><strong class="bold">CSS</strong> stylises the presentation and content, including <strong class="bold"><em>layout,colour, and font </em></strong>of webpages.</p>
    
            <h2 class="para">Our Digital Technologies Webpage Course</h2>

        <table class="table" >
            <thead >
                <tr>
                    <th>Unit 1</th>
                    <th>Unit 2</th>
                    <th>Unit 3</th>
                    
                </tr>
            </thead>
            <tbody>
            <tr>
                <td>HTML Basics</td>
                <td>CSS Basics</td>
                <td>HTML Links & Tables</td>
                
            </tr>
             <tr>
                <td>Weeks 1-2</td>
                <td>Weeks 3-4</td>
                <td>Week 5-6</td>
            </tr>
            <tr>
                <td>Quiz # 1</td>
                <td>Quiz # 2</td>
                <td>Quiz # 3</td>
            </tr>
                
                
            </tbody>
        </table>
    

    <!-- Internal link -->
    
    <h3 class="para"> <a href="#return" >Back to top</a>></h3>


    </body>
</html>
