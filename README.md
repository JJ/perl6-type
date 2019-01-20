# Perl6::Type

Walk through a type class hierarchy

This class stores the different elements of the class hierarchy of a
Perl6 Type. It's got a single method, `mro` or [Method Resolution
Order](https://docs.perl6.org/type/Metamodel::C3MRO), which returns the hierarchy in the order the methods would be
resolved, that is, the look up order for methods in the type.

## Installation

It's installed in the usual way

    zef install .

