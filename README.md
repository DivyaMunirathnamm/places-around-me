## Places Around Me
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
![Divya-hometown](https://github.com/DivyaMunirathnamm/places-around-me/assets/147474097/7578af54-c8c0-4bdc-b4ca-7dfd24d4692e)

![jjnagartrt](https://github.com/DivyaMunirathnamm/places-around-me/assets/147474097/9443b55d-5914-4618-a106-b9955ffacd1e)

![govthostrt](https://github.com/DivyaMunirathnamm/places-around-me/assets/147474097/ac0c3530-4a83-4fe7-9a7e-bb936d77a46f)

![mgrnagartrt](https://github.com/DivyaMunirathnamm/places-around-me/assets/147474097/fa70e0cf-3f46-4bca-96a9-2cf4e95652c5)

![velumesstrt](https://github.com/DivyaMunirathnamm/places-around-me/assets/147474097/a2eb92ab-09ba-4224-917b-5bded1f85d50)

![csischooltrt](https://github.com/DivyaMunirathnamm/places-around-me/assets/147474097/c809de72-1c2f-4c18-bdf1-266bbe025c94)


## Result:

The program for implementing image map using HTML is executed successfully
