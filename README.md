# writenNumberAnalyser

## Basic Description
Capable of converting a out-written numeral to an integer value

* Scripting-Language: Java

## Concept
This project build upon the fact, that in every language you will find certain keywords when working with numerals(numbers in different formats). For example in English you can write the number 23 out as *twenty-three*, in German as *dreiundzwanzig*(oneandtwenty) and in French as *vingt-trois*(twenty-three).
As you can see every language is using its own set of grammar to define the format of their numbers. In English you start with a decadic number followed by a single-digit number, separated by a whitespace; In French it's the same, but your separator is a "-"; In German you start with the single-digit followed by the decadic number separated by "und" (isn't German funny ;) ).
While these three presentations of numbers seem very different in the beginning, they are still consisting of basic building blocks like

__separator:" "/"und"/"-"__

and so on, making it possible to create an algorithm around them.
For more information and language specific documentation, come back later, when I actually have written more 😊.

## Implementation
I start writing this project in Java, as the language I have started serious scripting with and as it has currently a large user base, later it might be ported to some languages of the C-family and maybe even on JavaScript and PHP, making it available for web applications. But since my time working on this is limited feel free to use the information given, to port it to what ever scripting-language you want. I would be very happy to see and test your version, so write me when your done.

The Java class will be all static, making it easy for you to implement it into your existing projects.

I rely on an very adaptable algorithm accomlished by many flags and constant Arrays for each language making it easily adaptable for other, new languages. As a result the algorithm is not specialized and by that slower than one, that is uniquely crafted for one language. As well, readability has to suffer since we'll have large if...else and switch structures. I'll try to counteract with many in-script comments.

## Problems to face
Their are some complicated problems to face during this project and I don't want to hide them from you.

* __"Exotic" languages__, not based on Latin, might have a totally different way of representing their numbers. If so you will have to excuse me, but as narrow minded as I am about languages exeding Europe and the US, I have no single clue about Asian, African or South American languages and it's unlikely that I will learn enough of them to integrate them into this project. So once again I rely on you coders around the world to complete this task on your own.
* __Complexity__ is maybe the greatest opponent. Since languages are not constructed like programming-languages and have more or less grown and evolved, leaving some tumors behind (talking about irregular forms here), the algorithm might not be able to cover all of those efficiently. Never the less I will try to make all numbers analysable, but maybe leaving some efficiency behind.
* __Testing__ is always problematic, when you deal with large groups of possible arguments, so I can't possibly test all numbers. I will try to assemble a large group of test-numbers, to cover all the variants. When you encounter an error please emidiatly send me a message, with what number or what group of numbers you had problems. I might not be able to fix to within the next days, so feel free to debug the code yourself and write your solution to me.

## Milestones
1. I started the project privately and already was able to convert the numbers from *zero* to *ninety nine hundred ninety nine* into int
