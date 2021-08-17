# Form 
A form is used for collecting input from end user for immediate or postponed processing on the server.
Form is one of the essential tools used  in  data gathering. It provides the end user with freedom in providing user-related data that could be used for identification and other purposes.

It is an essential resource or tool used in businesses , banks , educational institutions , government agencies , etc.
The banks issue forms to customers during account opening , for customer service , etc.
Businesses use forms to accept customer order , receive complaints , etc.
Institution for learning use in varying ways such as when registering a new student , during examination, etc

Forms in HTML are created using the form element which comprises of the <form> tag wrapping  different child tags.
The <form> tag is a parent tag that encloses set of fields and labels.
## What is a field
A field in a form is a data entry point while a label identifies the field.
Related fields can be grouped together using <legend>.

A form field can take any type of data,  thereby making  fields to be segmented into various types.
A field uses the type attribute to identify the nature of data that should be entered.

A field can fall into any of the category below :
### Input
The input element is use for single line data entry

### Select
Use this category if you want your end uses to choose from a set of numerous options.
An example of this category is the state of residence selection.
Listing the 36 states and asking users to select 

### Textarea
A textarea is used for collecting multiline data entry

#### Types of data for input field 
An input field can have any of the following type : 
*	text : A text input field is for gathering short text e.g first name 
*	password : for collecting sensitive data that should not be reveal 
*	email : for email addresses
*	tel :  for telephone number
*	submit :  displays a submit button
*	submit :  displays a clickable button
*	date : for time related information 
*	range : select a range of values 
*	number :  for numeric data of integer type
*	checkbox : used to enable the selection of option(s) from a list of options
*	radio : used when you want the end user to select only one option from a list of options


The {name} attribute of a form element is important in identifying the form field for processing on the server especially if the data was sent using the default form behavior rather than javascript
By default , your forms will not appear pleasant as they would be scattered and zigzag due to absence of styling.
The fields in a form are wrapped within the form tag.


A <label> is used for indicating what data a user should enter into a field. Labels can be styled , and a compulsory attribute “for” must be used to which form element the label points to .

A checkbox allows the user to check more than one option  , while a radio button accepts only one option.
 
A fieldset is used for wrapping fields that belong to the same legend ( grouping)

When the user clicks on submit , the data enter by the user is sent to the server for processing via the {method} 
attribute on the form field.
The path to the server is provided by the {action} attribute
