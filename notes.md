expression should be put in div element of the app in index.html

# directives
> Change the behaviour of the element it's applied to.

## Basic directies
| Directives| Notes|Apply|
| ---|---|---|
| v-cloak| hides the render before the vue app is loaded|
| v-model| to bind values to data function in vue to html | v-model= "firstName"|
| v-bind| update property of html element dynamicaly, so what this do is use the data fuction in js and get data from url variable and put it in place of it in html| v-bind:href="url", :href="url"[short hand way to use it]|
|v-html| if you want to put raw html from data fuction|it's not good idea to use it for cross site scripting problem|
|v-on| it listen to event and do something, when there is a click on the element the fuction from the js file in methods object we will have the fuction what will run| v-on:click="function_name", @click="function_name"|


---

> to excess data property we use **this.variable_name**, to use the value in programming

[Event Modifiers](https://v3.vuejs.org/guide/events.html#event-modifiers)
We can you to change events property we need to use **event.code** on this website.


[Key Info](https://keycode.info/) To find the number of key pressed by user

## HTML ELEMENTS
|Name|Describtion|Uses|Look|
|---|---|---|---|
|input| to get input from user| ``` <input type="text"> ```, ``` <input type="number" ```>|<input type="number">|
|button| to add button|``` <button type="button"> ```|<button type="button"> Click </button>

|Modifiers|Description|Uses|
|---|---|---|
|v-model.lazy| let user type before doing the next thing|
|v-model.lazy.trim| it preforms white space removal after typing finishes|
|v-model.number|Converstion to number|

## CSS styling
|element|what they do|
| --- | ---|
| [v-cloak]| attributes can be selected in css sheet with box bracket [atr-name] and change there property|

## Computed Properties
> It compute some value of a property only when the values are change, so it increases the speed and help us avoid render without need
