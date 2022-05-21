# Set Laravel (any version) custom 404(any error page) page
## Step 1 
Goto /vendor/laravel/framework/src/Illuminate/Foundation/Exceptions/views/ this location 
## Step 2 
Here you will find all error pages 
Now edit which page you want to edit 
Here I'm changning 404 page so I just edit 404.blade.php 
Now We have to enter just one line of code like 
## Step 3 
<code>
echo "<script>location.href='/404'</script>";
</code> 

## Step 4 
Remove old codes of this file or you can comment out old codes of this file. 
## Step 5
Save and reload your website on 404 page. 
### (Here I have created 404 route to handle 404 page )
My codes like 

![image](https://user-images.githubusercontent.com/70555095/169640236-41f35477-e6b6-4aeb-b360-388775598a53.png)

## Get more on https://devsecit.com 
### Kanai Shil - DEV SEC IT Pvt. Ltd.
