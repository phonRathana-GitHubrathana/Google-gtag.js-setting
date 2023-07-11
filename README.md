<html>
<head>
<script type="text/javascript" src="/script/utils.js" charset="UTF-8"> </script>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
<script type="text/javascript">
function getURLParameter(name) {
  return decodeURI(
    (RegExp(name + '=' + '(.+?)(&|$)').exec(location.search)||[,''])[1]
   );
}
function findDestination() {
  var translations, lang;
  var userLang = (getURLParameter("lang") || window.navigator.userLanguage || window.navigator.language).substring(0,2);
  if (userLang == 'km')
    userLang = 'kh-kh';
  var hash = window.location.hash;
  switch (hash) {
    case "#tutorial":
    case "#tutorial_r4":
      translations = ["en","de","fr","it","es"];
      lang = translations.indexOf(userLang) > -1 ? userLang : "en";
      return "http://" + window.location.host + "/" + lang + "/tutorial_r4/introduction.html"
    case "#paypal":
      return "https://www.paypal.com/
    case "#flattr":
      return "https://flattr.com/thing/1028216/My-Expenses-GPL-licenced-Android-Expense-Tracking-App";
    case "#news":
      return "https://plus.google.com/
    case "#changelog":
      hash = "#versionlist";
      break;
    case "#privacy":
      hash = "#imprint";
      break;
    case "#donate":
      hash = "#premium";
    break
  }
  translations = ["en","de","fr","it","es","tr","vi","ar","hu","ca","zh-tw","pt","pl","cs","ru","ro","ja","ms","hr","eu","da","bg","el","iw"];
  lang = translations.indexOf(userLang) > -1 ? userLang : "en";
  return "https://" + window.location.host + "/" + lang + hash;
}
window.location.replace(findDestination());
</script>
</head>
<body>
<noscript>
<ul>

    <li><a href="ar">مصروفاتي</a></li>

    <li><a href="bg">Моите разходи</a></li>

    <li><a href="ca">Les Meves Despeses</a></li>

    <li><a href="cs">Moje výdaje</a></li>

    <li><a href="da">Mine udgifter</a></li>

    <li><a href="de">Meine Ausgaben</a></li>

    <li><a href="el">Έξοδα μου</a></li>

    <li><a href="en">My Expenses</a></li>

    <li><a href="es">Mis gastos</a></li>

    <li><a href="eu">Nire gastuak</a></li>

    <li><a href="fr">Mes dépenses</a></li>

    <li><a href="hr">Moji troškovi</a></li>

    <li><a href="hu">Kiadásaim</a></li>

    <li><a href="it">Le mie spese</a></li>

    <li><a href="iw">ההוצאות שלי</a></li>

    <li><a href="ja">マイ エクスペンス</a></li>

    <li><a href="kn">ಮೈ ಎಕ್ಸಪೆನ್ಸಸ್</a></li>

    <li><a href="ko">내 지출</a></li>

    <li><a href="ms">Perbelanjaan Saya</a></li>

    <li><a href="nl">Mijn Uitgaven</a></li>

    <li><a href="pl">Moje Wydatki</a></li>

    <li><a href="pt">Minhas despesas</a></li>

    <li><a href="ro">Cheltu



























  


 








 

 

 



                     

                   

                  

               

                 

               

              

         

           

           

           

  

  






    

  





 

  

   

       

     

         

       

    

  

        

          

       

      

    

    

        

        

        

    

   

      

        

            

              

             

            

          

        

      

    






