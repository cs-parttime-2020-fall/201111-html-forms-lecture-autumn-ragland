# 20-11-11 CSS HTML Forms Lecture

### Set Up
1. copy the assignment git url in github after accepting the assignment
1. clone the assignment in the `html-css-basics` directory using `git clone COPIED URL`
1. open the assignment in VSCode

### Linking files
1. create an html file called `index.html` and use the `html:5` shortcut to generate the html, head, and body elements
2. create a css file called `style.css`
3. link the css file to the html file using the `link` tag in the `head` - set the `rel` attribute to `stylesheet` and the `href` attribute to the css file path
```html
 <link rel="stylesheet" href="style.css">
```
4. check that the file is linked by setting the `background-color` property of the body to any color other than white/gray and open the HTML file using `ctrl o` in the browser

### Code Together
#### Content
1. Add a heading with the text `20 11 11 HTML Forms`
1. add HTML `form` tag below heading
1. wrap all form field in a `fieldset` element with a `legend` with the text `Lecture`
1. create a `studentName` field with a text input, `Name` label, and a placeholder that reads `First and Last Name`
1. create a `submitForm` button 
1. create a `resetForm` button
1. create a `studentAge` field with a required number input and `Age` label
1. create a `studentEmail` field with a required email input and `Email` label
1. create a birthday field with a date input and a `Date of Birth` label
1.  create a `cohortSelection` field with a selection nesting 6 options (values 0 - 5) and a `Cohort` label
1. create `studentLocation` radio buttons for local and not local
1. create student experience fields with three check boxes for `programing interest`, `programming experience`, and `programming education`
1. set the action and method attributes of the form element and view formatted form values using `https://postman-echo.com/get`

#### Styling
1. round the border of the fieldset and add space between the content inside the fieldset and the border
1. add space between each of the label-input form element groups 

### Push File Changes in the Terminal
1. `git status` : check if file changes have been made
1. `git add -A` : stage changes for commit
1. `git commit -m "meaningful message"` : commit changes with appropriate message
1. `git push` : reflect local changes remotely 

### Resources
[Concept Documentation on HTML + CSS](https://github.com/cs-parttime-2020-fall/part-time-program-syllabus/blob/master/htmlCSS.md)
