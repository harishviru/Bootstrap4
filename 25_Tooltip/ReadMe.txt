.Bootstrap 4 Tooltip
--------------------   

data-toggle="tooltip"
data-placement="top"

$('[data-toggle="tooltip"]').tooltip();  

#Tooltip Options:
 animation="true/false" 
container
delay: {show: 500, hide: 100} 
html ="true/false" ->whether to accept HTML tags in the tooltip
placement -"top/left/right/bottom
selector -Adds the tooltip to a specified selector
title
trigger-"click,hover,focus"

#Tooltip Methods
tooltip('show/hide/toggle');

#Tooltip Events

show.bs.tooltip	Occurs when the tooltip is about to be shown	
shown.bs.tooltip	Occurs when the tooltip is fully shown 
hide.bs.tooltip	Occurs when the tooltip is about to be hidden	
hidden.bs.tooltip	Occurs when the tooltip is fully hidden

Note: Tooltips must be initialized with jQuery: select the specified element and call the tooltip() method.

Bootstrap 4 Popover
-------------------
The Popover component is similar to tooltips; it is a pop-up box that appears when the user clicks on an element. The difference is that the popover can contain much more content.

data-toggle="popover"
title                              --->header text of the popover,
data-content                ----> popover's body:
data-placement 
data-trigger="focus/hover/click"

  $('[data-toggle="popover"]').popover(); 


#Popover Options
 animation="true/false" 
 container
 content
 delay: {show: 500, hide: 100} 
 html ="true/false" ->whether to accept HTML tags in the tooltip
 placement -"top/left/right/bottom
 selector -Adds the tooltip to a specified selector
 title
 trigger-"click,hover,focus


#Popover Methods
.popover(options)	
 options :show,hide,toggle,dispose

 #Popover Events
  show.bs.popover	 Occurs when the popover is about to be shown	
  shown.bs.popover	 Occurs when the popover is fully shown 
  hide.bs.popover	        Occurs when the popover is about to be hidden	
  hidden.bs.popover	 Occurs when the popover is fully hidden 	Note: Popovers must be initialized with jQuery: select the specified element and call the popover() method.

Bootstrap 4 Toast
-----------------
The toast component is like an alert box that is only shown for a couple of seconds when something happens 

.toast,
.toast-header 
.toast-body 
 data-autohide="false" 
 data-dismiss="toast"

  $('.toast').toast('show');

#Toast Options
For data attributes, append the option name to data-, as in data-placement="".

animation
autohide
delay

#Toast Methods
.toast(options)	
 options :show,hide

 #Toast Events
show.bs.toast	Occurs when the toast is about to be shown	
shown.bs.toast	Occurs when the toast is fully shown 
hide.bs.toast	Occurs when the toast is about to be hidden
hidden.bs.toast	Occurs when the toast is fully hidden

Note: Toasts must be initialized with jQuery: select the specified element and call the toast() method.