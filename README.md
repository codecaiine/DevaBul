# DevaBul
Deva-Bul is a Android mobile application that patients to exchange information in disease-dedicated forums. The application also will provide map benefits. Users can find their location and addresses of health institutions (Hospitals, Pharmacies etc.) .    
Used Technologies: 

<html>
<body>
<h1>Used Technologies</h1> 
Java, Gradle, MySQL, PHP, Volley Library, Google APIs(Maps, Places)

<h1>Changes to do for the right work of the project</h1>

1. In Php files and other necessary MySQL connections codes you have to write your webhost properties instead of x. 
[$conn = mysqli_connect("x", "x", "x", "x")]
For example: $conn = mysqli_connect("HOSTNAME", "USERNAME", "PASSWORD", "DATABASE_NAME" <br/>

2. In AndroidManifest file;
...
android:name="com.google.android.maps.v2.API_KEY"
android:value="x"/>  You have to write api code that take from https://developers.google.com instead of x 
... <br/>

3. In Activities;
You have to write path of your php file instead of x. [String url ="x/LoginStatusChange.php"]
For example: String url ="www.webhost.com/LoginStatusChange.php"

</body>
</html>

