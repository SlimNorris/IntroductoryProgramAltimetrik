JavaScript can be implemented using JavaScript statements that are placed within the <script>... </script> HTML tags in a web page.

You can place the <script> tags, containing your JavaScript, anywhere within your web page, but it is normally recommended that you should keep it within the <head> tags.

The <script> tag alerts the browser program to start interpreting all the text between these tags as a script. A simple syntax of your JavaScript will appear as follows.

<script ...>
   JavaScript code
</script>


The script tag takes two important attributes:

Language − This attribute specifies what scripting language you are using. Typically, its value will be "javascript". Although recent versions of HTML (and XHTML, its successor) have phased out the use of this attribute.

Type − This attribute is what is now recommended to indicate the scripting language in use and its value should be set to "text/javascript".

So your JavaScript segment will look like:

<script language = "javascript" type = "text/javascript">
   JavaScript code
</script>


Whitespace and Line Breaks

JavaScript ignores spaces, tabs, and newlines that appear in JavaScript programs. You can use spaces, tabs, and newlines freely in your program and you are free to format and indent your programs in a neat and consistent way that makes the code easy to read and understand.
Semicolons are Optional
Simple statements in JavaScript are generally followed by a semicolon character, just as they are in C, C++, and Java. JavaScript, however, allows you to omit this semicolon if each of your statements are placed on a separate line. For example, the following code could be written without semicolons:

<script language = "javascript" type = "text/javascript">
   <!--
      var1 = 10
      var2 = 20
   //-->
</script>


But when formatted in a single line as follows, you must use semicolons: 

<script language = "javascript" type = "text/javascript">
   <!--
      var1 = 10; var2 = 20;
   //-->
</script>


Case Sensitivity
JavaScript is a case-sensitive language. This means that the language keywords, variables, function names, and any other identifiers must always be typed with a consistent capitalization of letters.
So the identifiers Time and TIME will convey different meanings in JavaScript.

Bibliography: https://www.tutorialspoint.com/javascript/javascript_syntax.html