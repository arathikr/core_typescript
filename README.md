# The TS Type System

=> Helps us catch errors during development.
=> Uses 'type annotations' to analyze our code.
=> Only active during development.
=> Doesn't provide any performance optimization.

# Understanding basic types in Typescript

Type: Easy way to the different proerties + functions that a value has.

Ex: string: properties + Methods a 'string' has in Javascript.
=> charAt(),charCodeAt(), concat(), includes(), endsWIth(), indexOf(), lastIndexOf(), localeCompare(), match()

=> Types: 1) Primitive Types, 2) Object Types
1.Primitive: number,string,boolean,symbol,void,null,undefined.
2.Object Types: functions,arrays,objects and classes.

Q) WHy do we care about types?
A) Types are used by the Typescript Compiler to analyze our code for errors. and Types allow other engineers to understand what values are flowing arount our code base.

Type Annotations + Type Inference:

1)Type Annotations: Code we add to tell Typescript what type of value a variable will refer to.[we developers tell typescript the type]

2)Typescript tries to figure out what type of value a variable refers to.[Typescript guesses the type]
