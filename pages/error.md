<!DOCTYPE html>
  <html lang='en'>
  <head>
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="chrome=1">
    <meta name="HandheldFriendly" content="True">
    <meta name="MobileOptimized" content="320">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="referrer" content="no-referrer">
    <title>Open When</title>
    <link rel='stylesheet' href='https://chamki.netlify.com/tufte.css' type='text/css'>
    <link rel='stylesheet' href='https://chamki.netlify.com/latex.css' type='text/css'>
<!-- Chrome, Firefox OS and Opera --> 
<meta name="theme-color" content="#ff4500"> 
<!-- Windows Phone --> 
<meta name="msapplication-navbutton-color" content="#ff4500">
 <!-- iOS Safari --> 
<meta name="apple-mobile-web-app-status-bar-style" content="#ff4500">
<link rel="icon" sizes="16x16 32x32 48x48 96x96 192x192" href="//cdn1.netlify.com/img/icon.png">
  <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
    <script src="https://unpkg.com/sweetalert/dist/sweetalert.min.js"></script>   
    <style>
      .swal-text {
  background-color: #FEFAE3;
  padding: 17px;
  border: 1px solid #F0E1A1;
  display: block;
  margin: 22px;
  text-align: center;
  color: #61534e;
}
      </style>
    
</head>
<body>
  <script>
  $(document).ready(function(){
    if (!sessionStorage.returning) {
    // run only if returning not stored in sessionStorage
    swal("Notice!", "This site is no longer maintained and has been shut down. Thanks for visit.         -Netlify Team", "warning");
      sessionStorage.returning = true;
} });
      </script>
<article>
<section>
<center>
<p> Good Bye! </p>
  </center>
</section>
</article>
</body>
</html>
