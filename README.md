# javascript
Demo Programs
# Tags

## noscript

The noscript tag defines an alternate content for users that have disabled scripts in their browser or have a browser that doesn't support script.

The noscript element can be used in both head and body.

When used inside the head element: noscript must contain only link, style, and meta elements.

The content inside the <noscript> element will be displayed if scripts are not supported, or are disabled in the user's browser.

## What is Console.log()
Console.log() is used to log information to the console. This is normally done automatically with the last result of a command that is returned, but can be done manually. Say for instance that you have a complex calculation that is being done in two parts, and you aren't getting the result that you're looking for, but don't know which part is the problem, you could log each part to see what is explicitly happening.

As a really simple example, I'm going to set two variables. The last variable that I set will be the result that shows after it finishes running:

```
a = 2*6;
b = a + 2;
```

Will show me "14".
But what if I really needed to know what a was being set to as it was being set? That's where I would log it to the console.

```
console.log(a = 2*6)
b = a+2
```
Will give me "12" and then "14" returned to my console.


## What is NoScript and Script
```
<noscript>
	<b>Your browser does not support</b>
</noscript>

<script>
	//about config
	alert("Hello")
	</script>
```
The <noscript> tag defines an alternate content for users that have disabled scripts in their browser or have a browser that doesn't support script.

The <noscript> element can be used in both <head> and <body>.

When used inside the <head> element: <noscript> must contain only <link>, <style>, and <meta> elements.

The content inside the <noscript> element will be displayed if scripts are not supported, or are disabled in the user's browser.


# Git Command
1. git add . (It adds all file of project to commit)
2. git commit -m "Message" (commit code locally)
3. git pull (It pull code from server)
4. git push (It push code tp server)
5. git merge branchname (to merge code from server and client)
6. git branch branchaname (It creates branch)
7. git checkout branchname (It goes to another branch)
