# SNOW-Angular-Data-Binding

In Angular, Data Binding provides the communication between a component and the DOM. 
It is a technique used to bind the data from an HTML template to a Component class or from a Component class to an HTML template. 
Angular allows both one-way data binding and two-way data binding.

## One-way data binding
One-way data binding allows us to manipulate the views through the models. 
If we make any changes in the class, it gets reflected in the template. 
In Angular, One-way data binding achieved through:
Interpolation or String Interpolation
Property binding
Event binding

## String Interpolation
In String Interpolation, we bind the data from a typescript class to the template by using the expression in double curly braces. 
It is one-way from component class to the template. 
For example:{{ data }}.
![image](https://user-images.githubusercontent.com/12488769/148706298-ca144d97-2757-4470-819d-24318eefc42a.png)
![image](https://user-images.githubusercontent.com/12488769/148706301-9ac94231-ff9b-4fbb-b2a2-0174818892b2.png)

## Property Binding
Property binding allows us to bind values to the attributes of HTML elements. 
Whenever the value of the component changes, the Angular updates the element attribute in the template. 
It's also a one-way binding from component class to template.

![image](https://user-images.githubusercontent.com/12488769/148706320-8c9e3c2a-e144-4969-8eeb-693b41e9f403.png)

![image](https://user-images.githubusercontent.com/12488769/148706323-c77f45e9-c3c9-4db4-9a10-6118c94da63a.png)


String interpolation and property binding are somewhat interchangeable. 
If we need to set element properties to non-string data values, we must use Property binding, not String Interpolation.

## Event Binding
Event binding allows us to bind DOM events such as keystrokes, button clicks, mouse overs, touches, etc to a function in the component. 
It is one way from template to the component class.
Event binding allows us to bind DOM events such as keystrokes, button clicks, mouse overs, touches, etc to a function in the component. 
It is one way from template to the component class.
![image](https://user-images.githubusercontent.com/12488769/148706339-be23f55a-3cf1-4b8c-a53d-115e506cee46.png)
![image](https://user-images.githubusercontent.com/12488769/148706343-c2ffda5b-9726-4d5a-b5d6-5365ef8c710b.png)

## Two-way data binding
In one-way data binding, any changes in the template are not reflected in the component class. 
To solve this, Angular provides two-way data binding.
Two-way data binding is achieved by combining property binding and event binding together.
![image](https://user-images.githubusercontent.com/12488769/148706364-af3c44de-fd9e-4cbb-b2cd-ca1601f42784.png)

Two-way data binding is useful in data entry forms. 
The Angular uses the ngModel directive to achieve two-way binding on HTML <form> elements.
To use the ngModel directive, we need to import the FormsModule package into our Angular module.
  
The ngModel directive is placed inside the square & parentheses and assigned to the property in the component class.
  



