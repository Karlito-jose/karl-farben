# karl-farben
Javascript Farbenspiel
<html>
<head>
<title>JavaScript-Test</title>
<script type="text/javascript">
<!--
  function Farbe(R, G, B) {
    this.R = R;
    this.G = G;
    this.B = B;
    this.hex="#"+R+G+B;
  }

 //  wir wechseln auf hellgruen

  function HintergrundWechseln() {
    var Hintergrund = new Farbe("E0","FF","E0");
    var Textfarbe = new Farbe ("00","FF","07");
    document.bgColor = Hintergrund.hex;
    document.fgColor = Textfarbe.hex;
  }
  //-->
</script>


</head>
<body>

<A HREF="javascript:HintergrundWechseln();">Farbwechsel</a><BR>
hier ist einfacher Text<br>

<script type="text/javascript">
<!--

  // wir wollen eine Datumsausgabe
  //  -- für lastModified als Function in den Head
  var jetzt = new Date();
  var monat = jetzt.getMonth() + 1;
  var datumsausgabe = jetzt.getDate() + "." + monat + "." +jetzt.getFullYear() ;
 document.write(datumsausgabe +    " Hallo hier bin ich");


//-->
</script>
</body>
</html>
