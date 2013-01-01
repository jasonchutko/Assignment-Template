#LaTeX (Lyx) Assignment Template
* * *
###Features:

* Cover page
* Headers on each page
* Proper margins

###How to Use:
Save the file AssignmentTemplate.lyx to an easily accessible location.
A setup step is required only one time to reduce editing on subsequent files.

####Setup:
```
File -> Open -> AssignmentTemplate.lyx
Document -> Settings... -> LaTeX Preamble
```
From this screen, change the constants under the header

```
% Constants to set once
```

Save this file.

####Regular Usage:
```
File -> New from Template... -> AssignmentTemplate.lyx
```
And then similarly to the setup,
```
Document -> Settings... -> LaTeX Preamble
```
And change the variables under the header
```
% Variables to change every new document
```
Save the changes, and then you can begin your document underneath the LaTeX code
`\start`

###Sample Assignment:
I have included a sample assignment in the Sample folder of this Github repository, featuring my solution to problem #1 from my AMATH 251 class' assignment #6. Click [here](https://github.com/jasonchutko/Assignment-Template/blob/master/Sample/sample.pdf) to view it.
###Credits:
This Lyx template is based on its LaTeX equivalent found at
<http://www.latextemplates.com/template/structured-general-purpose-assignment>