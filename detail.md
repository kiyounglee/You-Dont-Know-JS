## Up & Going
*[Foreword](up%20%26%20going/forword.md) - Mar 31,2015(88p)*
* [Chapter 1: Into Programming](up%20%26%20going/ch1.md)
	* Code -- Try It Yourself -- Operators -- Values & Types -- Code Comments -- Variables
	* Blocks -- Conditionals -- Loops -- Functions -- Practice
* [Chapter 2: Into JavaScript](up%20%26%20going/ch2.md)
	* Values & Types -- Variables -- Conditionals -- Strict Mode -- Functions As Values
	* `this` Keyword -- Prototypes -- Old & New -- Non-JavaScript
* [Chapter 3: Into YDKJS](up%20%26%20going/ch3.md)
	* Scope & Closures 
	* this & Object Prototypes
	* Types & Grammar
	* Async & Performance
	* ES6 & Beyond
* [Appendix A: Acknowledgments](up%20%26%20going/apA.md)
## Scope & Closures
*[Foreword](up%20%26%20going/forword.md) - Mar 24,2014(98p)*
* [Chapter 1: What is Scope?](up%20%26%20going/ch1.md) ---- [Review](up%20%26%20going/ch1.md#review-tldr)
	* Compiler Theory
	* Understanding Scope
	* Nested Scope
	* Errors
* [Chapter 2: Lexical Scope](up%20%26%20going/ch2.md) ---- [Review](up%20%26%20going/ch2.md#review-tldr)
	* Lex-time
	* Cheating Lexical
* [Chapter 3: Function vs. Block Scope](up%20%26%20going/ch3.md) ---- [Review](up%20%26%20going/ch3.md#review-tldr)
	* Scope From Functions
	* Hiding In Plain Scope
	* Functions As Scopes
		* Anonymous vs. Named
		* IIEF(Invoking Function Expressions Immediately)
	* Blocks As Scopes
* [Chapter 4: Hoisting](up%20%26%20going/ch4.md) ---- [Review](up%20%26%20going/ch4.md#review-tldr)
	* Chicken Or The Egg?
	* The Compiler Strikes Again
	* Functions First
* [Chapter 5: Scope Closures](up%20%26%20going/ch5.md) ---- [Review](up%20%26%20going/ch5.md#review-tldr)
	* Enlightenment
	* Nitty Gritty
	* Now I Can See
	* Loops + Closure
	* Modules
* [Appendix A: Dynamic Scope](up%20%26%20going/apA.md)
* [Appendix B: Polyfilling Block Scope](up%20%26%20going/apB.md)
* [Appendix C: Lexical-this](up%20%26%20going/apC.md)
* [Appendix D: Acknowledgments](up%20%26%20going/apD.md)
## *this* & Object Prototypes
*[Foreword](this%20%26%20object%20prototypes/forword.md) - Jul 27,2014(174p)*
* [Chapter 1: `this` Or That?](this%20%26%20object%20prototypes/ch1.md) ---- [Review](this%20%26%20object%20prototypes/ch1.md#review-tldr)
	* Why `this`?
	* Confusions
	* What's `this`?
* [Chapter 2: `this` All Makes Sense Now!](this%20%26%20object%20prototypes/ch2.md) ---- [Review](this%20%26%20object%20prototypes/ch2.md#review-tldr)
	* Call-site
	* Nothing But Rules(`this` binding)
	* Everything In Order
	* Binding Exceptions
	* Lexical `this`
* [Chapter 3: Objects](this%20%26%20object%20prototypes/ch3.md) ---- [Review](this%20%26%20object%20prototypes/ch3.md#review-tldr)
	* Syntax
	* Type
	* Contents
		* Computed Property Names / Property vs. Method / Arrays
		* Duplicating Objects / Property Descriptors / Immutability
		* `[[Get]]` / `[[Put]]` / Getters & Setters / Existence
	* Iteration
* [Chapter 4: Mixing (Up) "Class" Objects](this%20%26%20object%20prototypes/ch4.md) ---- [Review](this%20%26%20object%20prototypes/ch4.md#review-tldr)
	* Class Theory
	* Class Mechanics
	* Class Inheritance
	* Mixins
* [Chapter 5: Prototypes](this%20%26%20object%20prototypes/ch5.md) ---- [Review](this%20%26%20object%20prototypes/ch5.md#review-tldr)
	* `[[Prototype]]`
		* `Object.prototype`
		* Setting & Shadowing Properties
	* "Class"
	* "(Prototypal) Inheritance"
	* Object Links
* [Chapter 6: Behavior Delegation](this%20%26%20object%20prototypes/ch6.md) ---- [Review](this%20%26%20object%20prototypes/ch6.md#review-tldr)
	* Towards Delegation-Oriented Design
		* Class Theory
		* Delegation Theory
		* Mental Models Compared
	* Classes vs. Objects
	* Simpler Design
	* Nicer Syntax
	* Introspection
* [Appendix A: ES6 `class`](this%20%26%20object%20prototypes/apA.md) ---- [Review](this%20%26%20object%20prototypes/apA.md#review-tldr)
* [Appendix B: Acknowledgments](this%20%26%20object%20prototypes/apB.md)
## Types & Grammar
*[Foreword](types%20%26%20grammar/forword.md) - Feb 4,2015(198p)*
* [Chapter 1: Types](types%20%26%20grammar/ch1.md) ---- [Review](types%20%26%20grammar/ch1.md#review)
	* A Type By Any Other Name...
	* Built-in Types
	* Values as Types
* [Chapter 2: Values](types%20%26%20grammar/ch2.md) ---- [Review](types%20%26%20grammar/ch2.md#review)
	* Arrays
	* Strings
	* Numbers
	* Special Values
	* Value vs Reference
* [Chapter 3: Natives](types%20%26%20grammar/ch3.md) ---- [Review](types%20%26%20grammar/ch3.md#review)
	* Internal `[[Class]]`
	* Boxing Wrappers
	* Unboxing
	* Natives as Constructors
		* `Array(..)`
		* `Object(..)`, `Function(..)`, and `RegExp(..)`
		* `Date(..)` and `Error(..)`
		* `Symbol(..)`
* [Chapter 4: Coercion](types%20%26%20grammar/ch4.md) ---- [Review](types%20%26%20grammar/ch4.md#review)
	* Converting Values
	* Abstract Value Operations
	* Explicit Coercion
	* Implicit Coercion
	* Loose Equals vs Strict Equals
	* Abstract Relational Comparison
* [Chapter 5: Grammar](types%20%26%20grammar/ch5.md) ---- [Review](types%20%26%20grammar/ch5.md#review)
	* Statements & Expressions
	* Operator Precedence
	* Automatic Semicolons
	* Errors
	* Function Arguments
	* `try..finally`
	* `switch`
* [Appendix A: Mixed Environment JavaScript](types%20%26%20grammar/apA.md)
* [Appendix B: Acknowledgments](types%20%26%20grammar/apB.md)


