# Crafted Creations
Welcome to the Crafted Creations ReadMe.\
Here we will talk about how we decided to code stuff and also what this website and repository is here for.

# Coding Standards  

## Naming Conventions  

#### Branches should be named in lowercase and hyphen seperated:  

```
my-branch-name
```    

#### Variables should be lowercase and underscore seperated:  

```
let my_var;  
my_var = "Hello World";
```    

#### Function names should be in camel case:  

```
function myFunction()
function thisIsAnExtremeExampleOfCamelCase()
```   

##  Commits  

#### Should be stated in imperative form:  

```
❌ I Added the ability for the user to do thing  
✅ Add ability for user to do thing
```  

#### Should start with a commit type:  

```
𝐟𝐞𝐚𝐭𝐮𝐫𝐞: <commit message> - 𝘈𝘥𝘥𝘴 𝘢 𝘧𝘦𝘢𝘵𝘶𝘳𝘦
𝐛𝐮𝐠𝐟𝐢𝐱: <commit message> - 𝘍𝘪𝘹𝘦𝘴 𝘢 𝘣𝘶𝘨  
𝐫𝐞𝐟𝐚𝐜𝐭𝐨𝐫: <commit message> - 𝘐𝘮𝘱𝘳𝘰𝘷𝘪𝘯𝘨 𝘤𝘰𝘥𝘦 𝘸𝘪𝘵𝘩𝘰𝘶𝘵 𝘢𝘥𝘥𝘪𝘯𝘨 𝘧𝘦𝘢𝘵𝘶𝘳𝘦𝘴  
𝐜𝐨𝐦𝐦𝐞𝐧𝐭𝐢𝐧𝐠: <commit message> - 𝘈𝘥𝘥𝘪𝘯𝘨 𝘪𝘯 𝘤𝘰𝘮𝘮𝘦𝘯𝘵𝘴  
𝐝𝐨𝐜: <commit message> - 𝘈𝘥𝘥𝘪𝘯𝘨 𝘪𝘯 𝘥𝘰𝘤𝘶𝘮𝘦𝘯𝘵𝘢𝘵𝘪𝘰𝘯  
𝐜𝐡𝐨𝐫𝐞: <commit message> - 𝘈𝘯𝘺𝘵𝘩𝘪𝘯𝘨 𝘯𝘰𝘵 𝘤𝘰𝘷𝘦𝘳𝘦𝘥 𝘣𝘺 𝘢𝘯𝘺𝘵𝘩𝘪𝘯𝘨 𝘢𝘣𝘰𝘷𝘦
```    

---

## Code Layout  

#### Braces should start at the end of line and end below the last line:  

```
if(true){  
    return true;  
}
```    

#### Languages should be written in order from top to bottom below:

```
Javascript  
HTML  
CSS
```  

#### example:  

```
<script>
    import Navigation from "$lib/navigation.svelte"  
</script>    

<div>  
    <Navigation />  
</div>    

<style>  
    div{  
        display: flex;  
    }  
</style>
```  

---

## Miscellaneous Conventions

#### For any unused variable represent it as an \_:  

```
{#each myArray as _, i}
    <p>Hello World!<p>  
{/each}
```
