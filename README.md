# VALUES-AND-STYLES
My personal developer value and style guide.

---

## Values

* Be curious
    * Have a seeker mindset
    * Developers need to be students, forever students
* Question things
    * Especially "why" and "what"
    * Most questions aren't dumb: Being afraid to ask a question is dumb
* Share by default
* Keep it simple
    * Be biased towards self-regulating processes\
* Keep it up-to-date
    * Don't be precious--sometimes you have to break it to improve it   
    * Follow evergreen paradigm
    * Stagnant software is a liability. If it isn't worth updating, unship it
    * Especially keep dependencies up-to-date
* Experiment
    * Figure out what you like doing, and then lean into it
    * Plant some seed, see what grows, then prune the graden
* Don't take yourself too seriously
    * Hold your own conclusions, ideas, and plans loosely
    * Be willing to throw it away
    * Let others critique your stuff

---

   ## Styles and Best Practices

### Operating Principles
* Keep It Simple
* Someone is going to have to read this, maybe even a future you
* Be as idiomatic as you can
* Make it as immutable as you can
---

### Cross-language

* Generally, be as idiomatic as possible
* Use trailing comma on last argument in multi-line method calls

### Kotlin

* Check out the official [Coding Conventions](https://kotlinlang.org/docs/coding-conventions.html)
* Use Kotlin like a Kotlin programmer (especially important for those of us who came from java)

---

### Typescript

* Take the time to get the typing right from the get-go

---

### React

#### Organization
* One exported Component per file (private sub components are fine)
* Create a folder structure that groups things, avoid a rigid "one-folder-per-component" scheme

#### Naming and Formatting 
* Component file names should be PascalCase
* Avoid using dom prop names (ie. style, className, etc.)
* Ordinarily split Component instantiations across lines if they have 3 or more props
* When calling a component, keep it on one line if it fits well. Otherwise utilize and a new line and an indenty for each prop:

```agsl
   <MyCompoent
        prop1="value1"
        prop2="value2"
        prop3="value3"
   />
```

#### Other
* Use Typescript and TailwindCSS
* Imports should always be on a single line
* De-structure obsessively (but don't go overboard)
* Ordinarily de-structure your props in the component signature 
    * For instance: `MyComponent( {a,b,c}: MyProps )`
* Keep your state as low as you can.

---

### Ruby

* Don't forget that if and case are expressions
* Remove parenthesis on zero parameter method calls
