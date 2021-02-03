Bootstrap 4 Alerts
-------------------------
.alert                                                --->alert can created
.alert-{contextual classes}
.alert-link                                           --->Add the alert-link class to any links inside the alert box 
.alert-heading 	                                      ---->Adds color:inherit to the specified element

#Closing Alerts
.alert-dismissible                                    -> class to the alert container.
.close
.data-dismiss="alert" to link or button element.

#Animated Alerts
.fade
.show

close.bs.alert 	                 -->This event fires immediately when the close instance method is called.
closed.bs.alert 	             -->This event is fired when the alert has been closed 

$('#myAlert').on('closed.bs.alert', function () {
  // do something…
})
