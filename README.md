<html>

<title>{Title}</title>
<link rel="shortcut icon" href="{favicon}">

<meta name="image:side" content=""/>

<meta name="color:text" content="#d3d3d3"/>
<meta name="color:link" content="#ADD8E6"/>
<meta name="color:link hover" content="#72bcd4"/>
<meta name="color:border" content="#d3d3d3"/>
<meta name="color:highlighted text" content="#cc3434"/>
<meta name="color:highlighted background" content="#000000"/>

<meta name="select:post size" content="250px"/>
<meta name="select:post size" content="300px"/>
<meta name="select:post size" content="350px"/>
<meta name="select:post size" content="400px"/>

<meta name="select:border" content="solid"/>
<meta name="select:border" content="dotted"/>
<meta name="select:border" content="dashed"/>
<meta name="select:border" content="outset"/>


<meta name="text:link divider" content=","/>
<meta name="text:link 1" content=""/>
<meta name="text:link 1 url" content="/"/>
<meta name="text:link 2" content=""/>
<meta name="text:link 2 url" content="/"/>
<meta name="text:link 3" content=""/>
<meta name="text:link 3 url" content="/"/>
<meta name="text:link 4" content=""/>
<meta name="text:link 4 url" content="/"/>



<script type="text/javascript"
src="http://codysherman.com/tools/infinite-scrolling/code" ></script>

    <style>




    
    /*--- Controls & Lightbox ---*/
    
    
    iframe#tumblr_controls {
        
        right:3px
        position: fixed
        opacity: 0.2;
        filter:alpha(opacity=20);
        -moz-opacity: 0.2;
        -khtml-opacity: 0.2;
        -webkit-transition: all 0.9s ease;
        -moz-transition: all 0.9s ease;
        -o-transition: all 0.9s ease;}
 
    iframe#tumblr_controls:hover {
    
        opacity: 1;
        filter:alpha(opacity=100);
        -moz-opacity: 1;
        -khtml-opacity: 1;}
  
  
  
   /*--- Scrollbar ---*/
   
   
    ::-webkit-scrollbar {
    
        width: 9px;
        height: 3px; }
        
    ::-webkit-scrollbar-thumb { 
        
        background: url("{image:side}");
        border: 1px solid #fff;
        border-radius:3px;
       -moz-border-radius:3px;
       -webkit-border-radius:3px; }
        
   
 
 
   /*--- Tooltips ---*/ 
    
    
    .ui-tooltip {  
        
    position:Absolute;
    z-index:9999;
    padding-top:10px; }
 
 
    .ui-tooltip-content {
        
    background:url("{image:side}");
    padding:2px 5px;
    font-size:7px;
    text-transform:uppercase;
    letter-spacing:1px;
    border:1px solid {color:borders};
    font-family:trebuchet ms;
    border-radius:3px;
    -moz-border-radius:3px;
    -webkit-border-radius:3px; }
    
    
    
    /*--- Text Selection ---*/
    
    ::selection {color: {color:highlighted text};
    background:{color:highlighted background} ;}
    
    ::-moz-selection {color: {color:highlighted text};
    background:{color:highlighted background} ;}
    
    ::-webkit-selection {color: {color:highlighted text};
    background:{color:highlighted background} ;}
    
    
    
    /*--- General ---*/
        
    
    body {
        
        background: #000;
        font-size: 7px;
        font-family:trebuchet ms;
        text-transform:uppercase;
        letter-spacing:1px;
        color: {color:text};
         
    }
    
    ul {
    list-style-type: hiragana;

    }
    
    a, a:visited {
     
        text-decoration: none;
        color:{color:link};
        -webkit-transition-duration: .7s;
        -moz-transition-duration: .7s;
        -o-transition-duration: .7s;
        
    }
    
    a:hover {
        
        color:{color:link hover};
        background:#000;
        transition-duration: .7s;
        -webkit-transition-duration: .7s;
        -moz-transition-duration: .7s;
        -o-transition-duration: .7s;
    }
    

    
    
    #entries {
        
        width: {select:post size};
        margin: 130px 5px 20px 650px;
        position: relative;
        padding: 15px;
        border: 1px {select:border} {color:border};
        border-radius:3px;
        -moz-border-radius:3px;
        -webkit-border-radius:3px;  
        background: url("{image:side}")
        
        
    }
    
    #entries blockquote {
        
        color: {color:text};
        padding: 0px 0px 0px 5px;
        border-left: 1px {select:border}{color:border};
        border-radius:3px;
     -moz-border-radius:3px;
    -webkit-border-radius:3px;  
 
        
    }
    
    #sidebar {
        
        position:fixed;
        margin-left: 300px;
        margin-top: 0px;
        width: 200px;
        height:auto;
        background: url("{image:side}") repeat;
        border: 1px {select:border} {color:border};
        border-radius:3px;
     -moz-border-radius:3px;
    -webkit-border-radius:3px;  
        
        
    }
    
   
    #sidebar .title {
        
        font-size: 13px;
        margin-bottom: 5px;
        color:{color:title};
        border-bottom: 1px {select:border} {color:border} ;
            transition-duration: .7s;
        -webkit-transition-duration: .7s;
        -moz-transition-duration: .7s;
        -o-transition-duration: .7s;
        
    }
    
    
    
    .title:hover {
       
        color: transparent;
       text-shadow: #cc3434 0 0 5px;
       text-decoration:none;
       letter-spacing:3px;
       transition-duration: .7s;
        -webkit-transition-duration: .7s;
        -moz-transition-duration: .7s;
        -o-transition-duration: .7s;
        
    }
    
    #sidebar .clicky {
        
        margin-top: 10px;
    }
    
    #sidebar .desc {
        
        color:{color:text};
        margin-top: 10px;
        border-bottom: 1px {select:border} {color:border} ;
        
        
    }
    
    #top{
    background: url("{image:side}");
    top:0px;
    left:0px;
    height:30px;
    width:100%;
    position:fixed;
    z-index:999;
    border-bottom: 1px {select:border} {color:border};
}


    #left{
    background: url("{image:side}");
    top:0px;
    left:0px;
    height:100%;
    width:30px;
    position:fixed;
    z-index:999;
    border-right: 1px {select:border} {color:border};
}
    
    
    .permalink { 
        
       border-top: 1px {select:border} {color:border};
    }
        
        
    
    .ask {
        
        border: 1px {select:border}{color:border};
        padding: 5px;
    }
    
    #credit {
        
        background: url("{image:side}");
        position: fixed;
        padding: 7px;
        border: 1px {select:border}{color:border};
        width: 15px;
        height: 7;
        bottom: 12px;
        left: 1225px;
    }
        
        
    </style>
    
    <head>
        
    </head>
    
    <body>
   <div id="top"></div>
   <div id="left"></div>
    
    <div id="sidebar">
    <center>
    
  
        <div class="title">
           <br><i>{ {Title} }</i><br>
           ⠀⠀⠀⠀ <div id="top"></div>
        </div>

        <div class="desc">
            {Description} <br><br>
        </div>
    
        <div class="clicky">
   <i>  {      {block:iflink1}
            <a href="{text:link 1 url}">{text:link 1}</a> {text:link divider}
            {/block:iflink1}
            {block:iflink2}
            <a href="{text:link 2 url}">{text:link 2}</a> 
            {/block:iflink2}
            {block:iflink3}
       <br> <br>    <a href="{text:link 3 url}">{text:link 3}</a> {text:link divider}
            {/block:iflink3}
            {block:iflink4}
            <a href="{text:link 4 url}">{text:link 4}</a>
            {/block:iflink4}
    } </i>   <br><br>
        
    </div>

    </div>
    
    <div id="credit">
       <a href="http://local-murderer.tumblr.com"> L-M </a>
    </div>
    
    
    <!-- POSTS -->
    
        <div id="content">
            
            {block:Posts}
            <div id="entries">
            
            

            {block:NoRebloggedFrom}
            {block:RebloggedFrom}
            {ReblogParentName}
            {/block:RebloggedFrom}
            {/block:NoRebloggedFrom}
                 

            {block:ContentSource}
            <!-- {SourceURL}
            {block:SourceLogo}
            <img src="{BlackLogoURL}"width="{LogoWidth}" height="{LogoHeight}" alt="{SourceTitle}" />
            {/block:SourceLogo}
            {block:NoSourceLogo}{SourceLink}{/block:NoSourceLogo} -->
            {/block:ContentSource}
            
            
            {block:Text}
            {block:Title}
            <b>{Title}</b>
            {block:Title} <br>
          <br>  {Body} <br><br>
            {/block:Text}
            
            {block:Photo}
            {LinkOpenTag}
            <img src="{PhotoURL-400}" alt="{PhotoAlt}" style="width: {select:post size};">
            {LinkCloseTag}
            {block:Caption}
            {Caption}
            {/block:Caption}
            {/block:Photo}
            
            {block:Photoset}
            {LinkOpenTag}
            {Photoset}
            {LinkCloseTag}
            {block:Caption}
            {Caption}
            {/block:Caption}
            {/block:Photoset}
            
            {block:Quote}
            {Quote}
            {block:Source}
            {Source}
            {/block:Source}
            {/block:Quote}
            
            {block:Link}
            <a href="{URL}" target="_blank">{Name}</a>
            {block:Caption}
            {Caption}
            {/block:Caption}
            {/block:Link}
            
            {block:Chat}
            {block:Title}
            <b>{Title}</b>
            {/block:Title}
            {block:Lines}
            <div class="line {Alt}">
            {block:Label}
            <b>{Label}</b>
            {/block:Label} 
            {Line}
            </div>
            {/block:Lines}
            {/block:Chat}
            
            {block:Audio}
            {block:AudioPlayer}
            {AudioPlayer}
            {block:AudioPlayer}
            {block:TrackName}
            {TrackName}
            {/block:TrackName}
            {block:Artist}
            {Artist}
            {/block:Artist}
            {block:Caption}
            {Caption}
            {/block:Caption}
            {/block:Audio}
            
            {block:Video}
            <div style="overflow:hidden;">
            {Video-400}
            </div>
            {block:Caption}
            {Caption}
            {block:Caption}
            {/block:Video}
            
            {block:Answer}
            <div class="ask">
            {Asker} said:
            {Question}
            </div>
            {Answer}
            {block:Answerer}
            {Answerer}
            {/block:Answerer}
            {/block:Answer}
            
	    {block:PostNotes}
	    {PostNotes}
	    {/block:PostNotes}
	    
            <!-- PERMALINK -->
            
 {block:Date}
<div class="permalink" style="margin-top:16px;"> <br>
             <a href="{Permalink}"> 
            {TimeAgo}
            +{NoteCount}
            <div align="right">
           {block:HasTags}<div class="tags {block:Caption}crash{/block:Caption}{block:Text}crash{/block:Text}{block:Link}crash{/block:Link}{block:answer}crash{/block:answer}"><i class="fa fa-tag"></i>{block:Tags}<a href="{TagUrl}" class="c"># {Tag}  </a>{/block:Tags}</div>{/block:HasTags}{/block:ifnothidetags}{/block:indexpage}  
            </div>
            {/block:Date}
            
            
          
            
           </div> 
        </div>
    </body>
</html>
