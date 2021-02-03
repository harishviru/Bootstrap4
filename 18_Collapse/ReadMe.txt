Bootstrap 4 Collapse
--------------------
.Collapsibles are useful when you want to hide and show large amount of content:

data-toggle="collapse"
data-target="#id" or href="#"
data-parent="#accordion"
.collapse
.collapse show
.collapsing

.collapse(options)  via Javascript
where options :toggle,hide,show,dispose.

show.bs.collapse 	Occurs when the collapsible element is about to be shown 	
shown.bs.collapse 	Occurs when the collapsible element is fully shown
hide.bs.collapse 	Occurs when the collapsible element is about to be hidden 	
hidden.bs.collapse 	Occurs when the collapsible element is fully hidden

Note: For <a> elements, you can use the href attribute instead of the data-target attribute:

