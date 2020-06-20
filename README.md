# QRCodeSignDemo
Simple Demo Showing the Use of QR Codes and Google Analytics Campaigns


For this scenario we want to setup a red sign and a green sign with QR codes on them.  We will use Google analytics campaigns to see which sign gets the most people scanning the QR code.

We'll use my a test page that is instrumented with Google Analytics as the destination for this demo
Here is the code for this webpage:
```html
<!doctype html>
<html>
<head>
   <meta charset="utf-8">
     <title>Thanks for visiting!</title>
   <meta name="KeyWords" content="John Funk QR Code Campaign Tutorial">
</head>

<!------ Google Analytics begin ----->
<script type="text/javascript">
var gaJsHost = (("https:" == document.location.protocol) ? "https://ssl." : "http://www.");
document.write(unescape("%3Cscript src='" + gaJsHost + "google-analytics.com/ga.js' type='text/javascript'%3E%3C/script%3E"));
</script>
<script type="text/javascript">
var pageTracker = _gat._getTracker("UA-3346206-1");
pageTracker._initData();
pageTracker._trackPageview();
</script>
<!------ Google Analytics end ----->    
    
<body>
    Thanks for visiting!
</body>
</html>

```

## Step 1:  Generate a URL for the red campaign

