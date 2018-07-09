
## Notes

### BEM Notes
* The block name should describe its purpose, not state
* Blocks can be nested inside each other
* The element should be part of a block, and can't be used seperately from it
* The element name describe its purpose
* The element name is separated from block name with a double underscore __
* Elements can be nested inside each other
* The block can have nested structure in the DOM, but in the CSS the block structure is a flat list of elements
* Elements are optional within blocks. Not all blocks have elements.
* Modifier defines the appearance, state, or behaviour of a block or element



### Things to think about
* Parent/Child naming conventions
* Rough formula for naming classes
* No reason to mimic your HTML structure in Sass
* Be aware of third party code
* Classes that are controlled by javascript should be labelled that way. ie) j-class



### Things to implement

* Never use ids for styling
* Try to avoid attaching classes to elements in your css 

	```
	ie) h1.title
	```

* Use classes for styling
* Space after : but not before 
	
	```
	ie) background-color: pink;
	```

* There should be a space after the selector, before the opening bracket

	```
	.style {
		// code
	}
	```

* Each selector should be on its own line
	
	```
	.style,
	.these,
	.classes {
		// code
	}
	```

* The closing bracket should be on its own line




