# froods-dropdown
Package for dropdowns.

dropdownDiv should be a div containing:
	- A button element.
	- A Div element.

The button element should be the button for displaying the dropdown.

The div element should be the actual content in the dropdown.

You should create a 'visible' class in css:

.visible {
	display: flex !important;
}
(Display doesn't have to be flex)

You should also add the following properties to the original class of your dropdown content:
.dropdown-content {
	display: none;
	position: absolute;
}