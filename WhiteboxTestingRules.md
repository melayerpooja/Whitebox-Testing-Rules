# White box Testing Rules



* Class name should follow the camel case rule. 

Example: 
```typescript
DemoClass
```

* Variable name and function name must be in the camel case format. Any other parameters should also be in proper format.

Example: 

```typescript
demoVar, demoFunction(){}
```

* Variables which are accessed in the template, are only marked as ‘Public’. All other variables must use the access specifier as ‘Private’.

* Data to be sent to server has to be marked as ‘Private’.

* Each component selector has to be prefixed with the word ‘Helix’.


Example: 

```typescript
Helix-ComponentName
```

* Every component name, class name, var name must describe about its functionality.

* Modal names must follow camel case format. Example: HelixModalLoginComponent

* All the file names in project should be in lowercase.

* Service name must also proceeded with ‘Helix’.

Example: 

```typescript
Helix-name-service
```


* Do not use console.log() anywhere in the code.

* Remove all comments and extra white spaces.

* Code must be properly intended.

* Commit message on bit bucket should also be in given format.

Example: 

```
Module name: Short description about task
```

* CSS classes should also follow camel case.


