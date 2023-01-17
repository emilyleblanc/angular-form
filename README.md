# Forms

## Steps to create a form:
### Import Module
- 1. app.module.ts: import the FormsModule
- 2. app.module.ts: call the FormsModule in the imports array (under BrowserModule)

### Create Form
- 3. form.component.html: create a standard html form
- 4. form.component.html: add the ngModel directive to the inputs fields. This will give you access to properties such as onChange and onTouched
- 5. form.component.html: add the ngSubmit directive to the form element. Call a submit(). 
- 6. form.component.ts: write a submit method

### Validate Form
- 7. declare a variable on the input (eg. #name = "ngModel"). Now you can access properties of that variable. 
- 7b. form.component.html: create a div to display the error message
- 8. form.component.html: add the *ngIf structural directive and display div if an error is present
- 9. form.component.html: the errors are stored in the ngModel
