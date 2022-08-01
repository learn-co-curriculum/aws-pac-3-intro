# Programming as Conversation 3: Introduction

## Learning Goals

* Revisit abstraction

## Introduction

Before we jump into more code, let's think for a moment about something you
encounter pretty much every day when you read a news article or email: the way
we organize words to express and clarify meaning. For example, a **paragraph**
is a collection of sentences, introduced by a topic sentence and bundled up or
closed by a closing sentence. A **paragraph** can persuade or offend, direct or
explain. A paragraph has a _function_.

"Code paragraphs" are called, depending on language, "functions," "procedures,"
"methods," or "subroutines." They bundle up expressions and statements to
accomplish a task. Just as "Make a Sandwich" encompasses specific, "atomic"
actions like "get slice of bread," "get jelly," etc., `executeTransfer`
encompasses logic like `if (accountStatus === "open")` or `if (accountBalance >=
transactionAmount)`.

To have code that is easy to read, debug, and maintain, we need to bundle
collections of atomic activities into "code paragraphs" that do work. JavaScript
calls these "functions." 

Functions are the single most important unit of code in JavaScript. Much like a `<div>` or a `<section>` in HTML, functions serve as ways to group together related bits of JavaScript code. Grouped code is easier to read, debug, and improve.

## Abstraction

This process of bundling up small atoms into a _function_ is called
"abstraction." "Abstraction" comes from the Latin word for "to pull away." When
we're further away, many details are hard to see. Only the most relevant shapes
are recognizable. For example, when you're on an airplane overlooking a city,
the details of the cars below — the mileage, what's in the cup holder, the
make or model — are invisible; they're not _essential_. But what we may be
able to see is the vehicle type (car vs. truck) or the color of the car. By
abstracting we see what's true at a higher level, or more _generally_.

 You might not think about it often, but your brain is full of abstractions.

| Single Units                                                      | Abstraction                             |
| ----------------------------------------------------------------- | --------------------------------------- |
| John, Paul, George, Ringo                                         | The Beatles                             |
| Books about a killer dog, a scary clown, a scary alter ego...     | Horror novels (by Stephen King)         |
| Individuals with strange powers and use them for the greater good | Superheroes                             |
| Get two pieces of bread, put jam on ...                           | Make a peanut butter and jelly sandwich |


Abstraction is a natural part of learning to converse. We create abstractions to make it easier to shorten our sentences. We'd never get anything done if we couldn't abstract! We also use abstractions to decide what doesn't fit or what should fit. "Mozart" doesn't belong with The Beatles, but he does fit with "Classical Composers."

Abstractions help us think about complex activities. Humans brought the pattern of "abstracting work" to JavaScript. Abstractions that hold work are called functions.

## Next Steps

In Programming as Conversation 3, we'll learn to take our JavaScript
_expressions_ and _statements_ and bundle them up into abstractions called
_functions_.