# FAQ

Here are the most frequently asked questions about Flyable. They are organised into different categories. 
You can click on links provided in the answers to be redirected to more detailed documentation on the subject. 
If you don't find the answers you are looking for, don't hesitate to communicate with our team at contact@flyable.dev.

<br />

## Introduction

### What is Flyable?

Flyable is an ahead-of-time compiler for Python code. It takes Python code, analyses, optimizes, and transforms it directly to machine code. Doing so allows Flyable to speed up any Python code without needing to modify it.

### How can Flyable be useful for me / Why should I use Flyable?

If you're looking to significantly increase performance on an existing Python project with no effort, 
Flyable is the platform for you! Compared to other solutions that make Python faster, 
Flyable doesn't require you to make changes to your Python code in order to benefit from performance increases 
which results in development time savings.

### How do I get started?

It's simple! You can begin by downloading the Flyable package for your OS of choice. 
From the [download page](get-started.md#_1-install), you can follow our suggestions for getting started.

### Is Flyable free?

Flyable offers two licences. The free one is for anyone who uses Flyable for educational or non-commercial open-source purposes.
The other licence, the commercial one, is required for any business that wants to compile code with Flyable and push it to production. It also comes with commercial support. For more info you can contact the team directly at contact@flyable.dev.

<br />
<br />

## General Python Compatibility

### How does Flyable work with Python?

Flyable compiles Python code into executable files. 
To do this, it uses a type discovery algorithm and then makes optimisations before generating the desired output.

### Can I use any Python libraries / frameworks / modules?

Yes. Flyable works closely with the Python interpreter (CPython) to ensure that any external code will run exactly the same. This way developers can still enjoy their favorite libraries with the boost given by Flyable. In a near future, Flyable will also be able to compile any external libraries to extend the performance boost to them.

### Can my Python code call a Flyable module?

Not for now. Right now, Flyable only creates static modules to facilitate calls from Flyable to Flyable and calls from Flyable to Python. We do expect to make it work for the 0.9 release.

<br />
<br />

## Syntax

### Do I need to change any of my code?

Ideally no, but realistically Flyable is still a young product and will sometimes need you to change how your code is written. Some syntactic features are still missing right now, but this is a temporary situation, we are working on it.

### Could I compile my pre-existing Python code?

Sure, as long as it stays in the bounds of the Python functionalities that Flyable supports right now.

<br />
<br />

## IDE

### How is the IDE designed?

The IDE has been designed to be simple to use and to understand in order to make the Flyable technology 
accessible.

### Do I have to use Flyable's IDE to use the compiler?

Not really. We packaged the IDE to help people quickly test Flyable. We're aware that most people don't want to work with it since they are probably already using a code editing tool they like.

<br />
<br />

## Performance & General Usage

### What is the expected speedup?

For now, Flyable is expected to speed up your entire software execution time by 10-20%. This number highly varies depending on what the code is doing and how it's written. For specific algorithms Flyable can boost Python to make it up to 70 times faster. 
Also, although Flyable supports Python modules, it doesn't speed them up for now so only the parts of the code that do not depend on Python modules will be accelerated by Flyable.

### How does Flyable make Python faster and more lightweight?

The compiler applies strong optimization to your Python code before generating a native executable on Linux, Windows or Mac.

### How does the Flyable compiler work?

Flyable compiles Python code into executable files. To do this, it uses a type discovery algorithm and then makes optimisations before generating the desired output.

### What architectures can I run Flyable on?

Flyable produces x86 instructions that run both on Windows and Linux 64 bits. Support for MacOS is planned. ARM support is also planned. 32 bits support isn’t planned in the near future.

### What does Flyable produce?

Flyable produces an executable file that can directly be launched. The executable file will find the Python installation on the setup to find any external modules required.
We're also planning to offer the possibility to package all the required modules and files into the executable to remove the need to have an active Python installation to run Flyable made software.

<br />
<br />

## Development

### Can I still be a part of Flyable’s development process?

Yes. To test Flyable before everyone else, request an invite to the Early Access Program by sending us an email at contact@flyable.dev! To contribute to open-source parts of Flyable, visit Flyable’s GitHub repository.

### Is Flyable open-source?

No decision has been made yet, but we would really like to make Flyable an open-source software.

<br />
<br />

## Community

### How does Flyable help with data science?

Flyable helps you develop more performant Python code. Our benchmarks show that Flyable makes Python code up to 70x faster while using 80% less memory. This helps developers be more efficient and build better software and it helps organizations cut operating expenses.

### How can I connect with the Flyable team/community?

You can connect with the Flyable team on Twitter and LinkedIn and you can send us a message at contact@flyable.dev. 
