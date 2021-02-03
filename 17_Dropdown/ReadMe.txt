.Bootstrap 4 Dropdowns
----------------------
.dropdown
.dropdown-menu
.dropdown-item
.dropdown-toggle
data-toggle="dropdown"
.dropdown-divider            -used to seperate links
.dropdown-header           - used to add headers inside the dropdown menu
.active
.disabled

.dropright or .dropleft       -alignment/position of dropdown
.dropdown-menu-right          -To right-align the dropdown menu
.dropup                             -If you want the dropdown menu to expand upwards instead of downwards
.dropdown-item-text        -is used to add plain text to a dropdown item

Grouped Buttons with a Dropdown.
.btn-group
.btn-group-vertical

Split Button Dropdowns
.dropdown-toggle-split

Via JavaScript ::
 $('.dropdown-toggle').dropdown(); 

Dropdown Events ::
.show.bs.dropdown 	Occurs when the dropdown is about to be shown.
shown.bs.dropdown 	Occurs when the dropdown is fully shown
hide.bs.dropdown 	Occurs when the dropdown is about to be hidden
hidden.bs.dropdown 	Occurs when the dropdown is fully hidden

$(".dropdown").on("show.bs.dropdown", function(event){
  var x = $(event.relatedTarget).text(); // Get the text of the element
  alert(x);
});