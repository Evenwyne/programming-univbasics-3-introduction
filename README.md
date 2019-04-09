# Programming as Conversation Part 3: Introduction

## Learning Goals

* Define abstraction

## Introduction

A **paragraph** is a collection of sentences, aligned by a topic sentence and
bundled up or closed by a closing sentence. A **paragraph** can persuade or
offend, direct, or explain. A paragraph has a _function_.

"Code paragraphs" are called, depending on language, "functions," "procedures,"
"methods," or "subroutines." They bundle up expressions and statements to
accomplish a task. Just as "Make a Sandwich" encompasses specific, "atomic"
actions like like "get slice of bread," "get jelly," etc.,
`retreive_avatar_image_for_user` encompasses logic like `if user_name == nil`
or `if image_url == nil`

To have code that is easy to read, debug, and maintain, we need to bundle
collections of atomic activities into paragraphs that do work &mdash; methods.

## Abstraction

This process of bundling up small atoms into a collective, non-specific name is
called "abstraction." "Abstraction" comes from the Latin word for "to pull
away." When we "abstract" we "zoom out" or "pull away" from the tiny details
and refer to a larger collection, made up from those small details, by a
"larger name."

"Matt," "Lore," and "Kellye" are atomic individuals, but we can refer to them
all collectively by the abstraction "New Yorkers." Books about a killer dog, a
scary alter ego, and a scary clown can be _abstracted_ into the name "horror
novels (by Stephen King)."

Abstraction is a perfectly natural part of learning to converse. When you're
first learning to communicate, you don't know enough to start talking about
abstractions. But as you learn about opposites, how things are similar (and
how, perhaps one thing is dissimilar) you grow  in your ability to _abstract_

In fact the thing that makes most higher learning "higher" learning is that the
discussion, work, and discovery is focused on working primarily with
abstractions over specifics (e.g. mathematics, physics, chemistry).

## Next Steps

Ruby calls bundles of statements that, together, accomplish a unit of work or
process, ***methods***. In Programming as Conversation 3 we'll learn to take
our _expressions_ and _statements_ and bundle them up into abstractions called
_methods_.

## A New Way of Running Code: Tests and Labs

In Programming as Conversation 1, we learned to run code in IRB. In 
Programming as Conversation 2, we learned to run code by using
`ruby filename`. When programmers need to run (and rerun, and rerun)
code over and over, they like to use _tests_ to run their code.

That's right, a test is Ruby code that runs Ruby code to verify the
output. In this module, we're going to start giving you "Labs" to complete.
We'll write the _tests_ but you must write the _code_ to satisfy the
tests. When your tests pass you'll be able to move on through the module.

We believe that labs give you a chance to practice your skills. In 
Programming as Conversation Parts 1 and 2, we just wanted you to feel
the magic and awesomeness of programming. We didn't want to crimp that joy
with labs. But now you know enough to do some pretty powerful stuff. Tests will
confirm for both you and us that you're ***really*** getting the hang of
this stuff. That's such an awesome feeling, we can't wait to share it with you!

We have a specific lab that teaches how to solve a lab just a few
lessons from now, so don't stress about it! We'll walk you through the first
few and you're going to love getting the "green lights" just like the 
thousands of students who have come before you!