# Zero or Z Framework [pre ALPHA]

a no module php framework that implements [LightnCandy](https://github.com/zordius/lightncandy) and powered by [aracphp](https://github.com/flavi1/aracphp)

# Goals

* Avoid sub-sub-sub-folder complex trees in your vendor folder.
* No module approach : PHP namespace are enought powerfull (aracphp)
* Avoid repetitive code in the control couch (0 or Z Concept)

# Avoid sub-sub-sub-folder complex

TODO

# No module approach

TODO

# O or Z Concept

TODO

*  parler du preprocess dans les templates (rappel historique sur PHP) -> implicit preprocessed HMVC
* routines vs classic front controllers.
* Control is delegate to a routine (0) or a template page (Z)
* One unic front controller, 0.routine.php for explicit HMVC, z.page.tpl for implicit preprocessed HMVC.

# Conventions

* url point directly to a project folder. ex : myproject/myrequest
* First, the controller will try to find a routine in this format : 0.routine.php (here, ex : myproject/0.myrequest.php)
* If routine not found, the controller will try to find a page template "z.page.tpl" (here : myproject/z.myrequest.php)
