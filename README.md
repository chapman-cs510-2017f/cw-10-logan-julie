# CS510 CW 10

Name: Julie Gardner-Hoag, Logan Gantner <br>
Student ID: 2299636, 2307470 <br>
Email: gardnerh@chapman.edu, gantner@chapman.edu <br>
Course: CS510 Fall 2017 <br>


[![Build Status](https://travis-ci.org/chapman-cs510-2017f/cw-10-logan-julie.svg?branch=master)](https://travis-ci.org/chapman-cs510-2017f/cw-10-logan-julie)

## Specification

**Note: Remember this is a C project.**

Complete the following exercises, saving your solutions in the indicated files. 

1. Recall the following references, which will still be useful throughout the rest of the course.
    * [Learn C in Y Minutes](https://learnxinyminutes.com/docs/c/)
    * [C Cheat Sheet](https://www.cheatography.com/ashlyn-black/cheat-sheets/c-reference/)
    * [C Programming Wikibook](https://en.wikibooks.org/wiki/C_Programming)
    * [Learn Make in Y Minutes](https://learnxinyminutes.com/docs/make/)
1. Note that a ```bin``` directory will be created by ```make```. Pay attention to how it is used in what follows, since you will often see this convention used in practice. Also pay attention to the added compiler flags in the ```Makefile```, and what they do.
1. Examine the source code in ```src/bit_print``` carefully. Compile and run it.
    1. In a Jupyter notebook ```BitPrint.ipynb```, describe what ```print_types``` does in detail. By running the compiled program in a terminal, answer the following questions. (Even better, show the output of the program in a cell in your Jupyter notebook using the `%bash` magic command.)
    1. What are the integer values for the letters 'A', 'Z', 'a', and 'z'?
    1. What are the integer values for the numbers '0', '1', and '9' represented as characters?
    1. If you needed to store a 2D array of 10000x10000 complex numbers, how much memory would it require (in megabytes) if: a) the real and imaginary parts were each shorts? b) the real and imaginary parts were each long doubles? (Recall the prefixes: kilo = 10^3, mega = 10^6, giga = 10^9, tera = 10^12, peta = 10^15, exa = 10^18, zetta = 10^21, yotta = 10^24)
    1. Work out the algorithm for how the bit string for an unsigned int is interpreted as an integer. Describe this algorithm in your notebook.
    1. Work out the algorithm for how the bit string for a (signed) int is interpreted as an integer. How does this differ from an unsigned int? What are the maximum and minimum bounds of each? Describe this algorithm in your notebook.
1. Examine the source code in ```src/arrays``` carefully. Compile and run it.
    1. In a Jupyter notebook ```Arrays.ipynb```, describe what ```arrays``` does in detail. Do the following.
    1. Change the type of "array" to an array of floats. Make sure the code compiles and runs.
    1. Change the type of "memblock" to a pointer to long double. Make sure the code compiles and runs.
    1. Refactor ```arrays.c``` to add two new functions: ```print_arrays``` and ```set_arrays```. Move the existing code from ```main``` into these new functions as appropriate, and call them from ```main```. You will have to think carefully about what types these new functions should be, and what arguments (if any) they should have, of what type(s). Make sure the code compiles and runs.
    1. In your notebook, explain what ```malloc``` and ```free``` do in detail.
1. Examine the source code in ```src/structs``` carefully. Compile and run it.
    1. In a Jupyter notebook ```Structs.ipynb```, describe what ```print_structs``` does in detail. Answer the following questions.
    1. Explain the difference between "pass by value" and "pass by reference" in your own words. Support your explanation with concrete examples from the program output.
    1. Explain the difference between ```v.x``` and ```v->x``` for a struct ```v``` with field ```x```.
1. Examine the existing test in ```test/``` carefully. Compile and run it.
    1. Add another test that reimplements the "pass by reference" test in ```src/structs```. Ensure that it passes.

## Assessment

This was an interesting assignment. We had a bit of trouble figuring out what was supposed to go in our set_arrays function.

## Honor Pledge

I pledge that all the work in this repository is my own with only the following exceptions:

* Content of starter files supplied by the instructor;
* Code borrowed from another source, documented with correct attribution in the code and summarized here.

Signed,

Julie Gardner-Hoag, Logan Gantner
