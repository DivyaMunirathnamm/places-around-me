# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

### Design Steps:

### Step 1:
Create a Django admin interface.

### Step 2:
Download your city map from google.

### Step 3:
Using ```<map>``` tag name the map.

### Step 4:
Create clickable regions in the image using ```<area``` tag.

### Step 5:
Write HTML programs for all the regions identified.

### Step 6:
Execute the programs and publish them.


## Code:
```
map.html
 <!DOCTYPE html>
<html>
    <head>
        <title>
            imagemaps demo
        </title>
    </head>
    <body>
        <h1>imagemaps demo</h1>
        <img src="Divya-hometown.jpg" usemap="#image_map">
<map name="image_map">
  <area alt="csischool" title="csischool" href="csischool.html" coords="597,288,714,324" shape="rect">
  <area alt="jjnagar" title="jjnagar" href="jjnagar.html" coords="508,287,70" shape="circle">
  <area alt="mgrnagar" title="mgrnagar" href="mgrnagar.html" coords="589,418,687,474" shape="rect">
  <area alt="velumess" title="velumess" href="velumess.html" coords="384,346,107" shape="circle">
  <area alt="govthospital" title="govthospital" href="govthospital.html" coords="603,6,97" shape="circle">
  
</map>

    </body>
</html>

csischool.html
<!DOCTYPE html>
<html>
    <head>
        <title>csischool</title>
    </head>
    <body>
        <h1>csischool</h1>
    </body>
</html>

govthospital.html

<!DOCTYPE html>
<html>
    <head>
        <title>govthospital</title>
    </head>
    <body>
        <h1>govthospital</h1>
    </body>
</html>

jjnagar.html

<!DOCTYPE html>
<html>
    <head>
        <title>jjnagar</title>
    </head>
    <body>
        <h1>jjnagar</h1>
    </body>
</html>

mgrnagar.html

<!DOCTYPE html>
<html>
    <head>
        <title>mgrnagar</title>
    </head>
    <body>
        <h1>mgrnagar</h1>
    </body>
</html>

velumess.html

<!DOCTYPE html>
<html>
    <head>
        <title>velumess</title>
    </head>
    <body>
        <h1>velumess</h1>
    </body>
</html>

```


## Output:
![Uploading govthostrt.png…]()
![Uploading jjnagartrt.png…]()
![Uploading velumesstrt.png…]()
![Uploading velumesstrt.png…]()


## Result:

The program for implementing image map using HTML is executed successfully
