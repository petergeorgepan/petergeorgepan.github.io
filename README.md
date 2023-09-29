<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <style>
    div
    {
        border:3px solid black;
        width: 300px;
        height: 200px;
        margin:  20px;
        font-size: 30px;
        
    }
    .vis{
        overflow-x: visible;
        
    }
   .ver{ 
     writing-mode:vertical-rl
   }
   .scro{
        overflow:scroll;
        overflow-x: hidden;
   }
    .point{
        overflow: hidden;
       text-overflow: ellipsis;
       white-space: nowrap;
    }
    
  </style>
</head>
  <body>
    <div class="vis"><nobr>
     This is soome long text that will not fit the box

    </div></nobr>
    <div class="point">
      this is some long text that 

    </div>
       <div class="scro">
        some text with a span element
       <p>with a   <p class="ver">vertical-rl </p> writing-mode.</p>
    </div> 
  </body>
</html>
