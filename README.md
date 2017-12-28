# Whitebox-Testing-Rules

* Class name should follow the camel case rule. 

```typescript
Example: 

DemoClass
```

* Variable name and function name must be in the camel case format. Any other parameters should also be in proper format.

```typescript
Example: 

demoVar, demoFunction(){}
```

* Variables which are accessed in the template, are only marked as ‘Public’. All other variables must use the access specifier as ‘Private’.

* Data to be sent to server has to be marked as ‘Private’.

* Each component selector has to be prefixed with the word ‘Helix’.

```typescript
Example: 

Helix-ComponentName
```

* Every component name, class name, var name must describe about its functionality.

* Modal names must follow camel case format. Example: HelixModalLoginComponent

* All the file names in project should be in lowercase.

* Service name must also proceeded with ‘Helix’.

```typescript
Example: 

Helix-name-service
```


* Do not use console.log() anywhere in the code.

* Remove all comments and extra white spaces.

* Code must be properly intended.

* Commit message on bit bucket should also be in given format.

```
Example: 

Module name: Short description about task
```

* CSS custom classes should be seperated by hyphen.

* If the perticular CSS class is not used in html, don't keep its defination in CSS file.

* According to HTML 5 specification, ID must be unique in its home subtree. So avoid duplication of ID in HTML page.
