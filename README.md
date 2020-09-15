# Zero or Z Framework [pre ALPHA]

a no module php framework that implements [LightnCandy](https://github.com/zordius/lightncandy) and powered by [aracphp](https://github.com/flavi1/aracphp)

# Concept

* url point directly to a project folder. ex : myproject/myrequest
* First, the controller will try to find a routine in this format : 0.routine.php (here, ex : myproject/0.myrequest.php)
* If routine not found, the controller will try to find a page template "z.page.tpl" (here : myproject/z.myrequest.php)
