# HTMLTasks

## Task : Fix the bugs in the below snippet:

<html lang="en">
    <head>
        <title>Document
            <body>
                guvi
        </title>
    </head>
    <div>
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
        <div>
            <div>
                Guvi Geek Network
            </div>
        </body>
    </html>
      
      
## Errors in the code
      
    <html lang="en">
    <head>
        // <title>Document -Title tag should be closed.
         //    <body>  - body tag should be given after the head tag.
                guvi
        </title>
    </head>
    <div>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. // can be given in a para
        <div>
            <div>
                Guvi Geek Network
            </div>
        </body>  // body start tag is missing
    </html>
      
  ## The corrected code :
      <html lang="en">
    <head>
        <title>Document
            
                guvi
        </title>
    </head>
    <body>
        <div>
          <h1>Guvi Geek Network </h1>
        <div>
            <div>
           Lorem ipsum dolor sit amet consectetur adipisicing elit.    
            </div>
     </body>
    </html>
