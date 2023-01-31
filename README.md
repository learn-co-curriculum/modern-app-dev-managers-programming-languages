# Programming Languages

## Learning Goals

- Explain why different programming languages are used.

## Introduction

Programming languages are used to tell the computer what to do and how to do it.
[The list of programming languages on Wikipedia](https://en.wikipedia.org/wiki/List_of_programming_languages)
has lots of languages on it. Why are there so many languages if all of them are
being used to send instructions to the computer?

A computer processor can only understand 1s and 0s. Programming languages
provide abstractions that make it easier for humans to write instructions. Once
a program is written, it needs to be converted to 1s and 0s for a program. The
higher the level of abstraction provided by a language, the longer it takes to
run on a computer.

## Low-level and High-Level Languages

A low-level language is one that is closer to machine code, i.e., it has low
levels of abstractions for working with the computer. For example, a very low
level language might need you to describe exactly how to add to numbers whereas
a high-level language will provide you with a `sum` function that allows you to
perform addition without knowing how a processor works.

Low-level languages are also machine-dependent. Since they provide more direct
access to the hardware, multiple versions of a program may have to be written to
run on different systems. For example, computers can have different types of
processors. A low-level language would require you to write code specific to
each type of processor.

A high-level language is one that provides high level of abstractions which
makes code easier to read for humans. They are also machine-independent, i.e.,
you can write the code and run it on different types of systems and
environments. For example, Java code can be run on different operating systems
without changing anything. The main trade-off for using a high-level language is
usually speed. But if your application doesn’t need to be extremely fast, you
can use a high-level language to improve maintainability, readability, and
provide updates or features faster.

Languages exist in a spectrum from low-level to high-level. A language like
Assembly is very low-level whereas Python is very high level. When choosing a
language, it’s helpful to know how it compares to other languages to get a
general sense of what trade-offs it makes.

## Common Languages

Some programming languages provide unique features, are more performant, or were
designed for specific use cases. Let’s look at a few common languages and their
uses:

- C (low-level): A low-level language. It’s used mainly for systems programming,
  i.e., software that requires access to hardware. It is highly performant.
- JavaScript (high-level): It was developed to be used on web browsers. It’s the
  only language that a web browser can run natively.
- Python (high-level): One of the most popular general programming languages.
  It’s used for scripting, automation, data analysis, machine learning, and even
  for building web applications.

You can check out the
[StackOverflow Survey](https://survey.stackoverflow.co/2022/#section-most-popular-technologies-programming-scripting-and-markup-languages)
to see which languages are popular now. But note that even languages that are
not very popular may work great for your specific use case.

## Which Language Should I Use?

The language or languages you should use for your application depends on a
variety of factors such as speed, features, readability, purpose, tooling
support, community support.

Some languages were developed to be used for very specific use cases. SQL
facilitates interactions with databases, JavaScript was developed for web
browsers, HTML is used to describe text structure and meaning, and CSS is used
for styling applications.

The best way to decide which language or languages to use is to identify the
priorities for the application you’re building. For example, if you’re making a
software for systems with limited resources, it’s probably better to use a
low-level language since they have a low overhead and are very fast. But if
you’re developing applications for modern computers or smart devices, you can
likely use a high-level language to build it. The companies who make the devices
or the operating systems usually provide high-level languages and tools for
making applications for their operating systems or provides recommendations. We
can use Swift for iOS applications, Java or Kotlin for Android, and C# for
Windows.

## Conclusion

We have learned about different types of programming languages and how to decide
which ones to use for applications we’re developing. Programming languages
evolve and change all the time so it’s important to be aware of new advances or
limitations if you want to make the most of the language you’re using.
