# CSS-REGEX
Test that I did for the selection process in a company. In this test the following tests should be performed:

1. First comes CSS3 selectors. You will need sample.html and styles.css files for that. Your aim is to add simple styles into styles.css (PLEASE DO NOT CHANGE THE .HTML FILE), so that targeted tags are visually selected in sample.html:

- Add color background for tags, described below, write styles into styles.css:
- Tag, that contain text "Target value 1" - green color.
- Tag, that contain text "Target value 2" - gray color.
- Tag, that contain text "Target value 3" - blue color.
- Tag, that contain text "Target value 4" - yellow color.
- Links. Only 4 links should be selected - red color.
- All even li elements inside UL on line 44 of sample.html - purple color.

2. For the following tasks (2.1, 2.2)  use strictly regular expressions (regex):
2.1 Now you will have to write regular expressions using pcre standard. Save results in regular.txt file. For the first set use sample.html file:
- Extract urls like. Do not use url itself in regular expression. It should select only 4 links.
- Extract latitude value from html.
- Extract longitude value from html.

2.2. For the next 2 subtasks use sample.json file. This file contains JSON that has a list of objects inside. Please check it's structure first, each object is under unique ID:

{
	"SV350": {
		...
		// data, describing the object
		...
	},
	"fKDFI3": {
		...
		// data, describing the object
		...
	},

	...

	"38shF": {
		...
		// data, describing the object
		...
	}
}
Write 2 regular expressions, save results into regular.txt file:
- Extract all unique IDs from json, example of unique ID: "SV350". 
- Extract all unique IDs from json, that has "land":"ESP" inside, example of UID: SV350. 
