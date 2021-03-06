[[Raku PDF Project]](https://pdf-raku.github.io)
 / [[FDF Module]](https://pdf-raku.github.io/FDF-raku)
 / [FDF](https://pdf-raku.github.io/FDF-raku/FDF)
 :: [Template](https://pdf-raku.github.io/FDF-raku/FDF/Template)

role FDF::Template
==================

Description
-----------

An FDF template dictionary contains information describing a named page that serves as a template.

Methods
-------

class FDF::NamedPageRef $.TRef (page-ref)
-----------------------------------------

(Required) A named page reference dictionary specifying the location of the template.

class FDF::Field @.Fields
-------------------------

(Optional) An array of references to FDF field dictionaries describing the root fields to be imported (those with no ancestors in the field hierarchy).

class Bool $.Rename
-------------------

(Optional) A flag specifying whether fields imported from the template may be renamed in the event of name conflicts with existing fields. Default value: true.

