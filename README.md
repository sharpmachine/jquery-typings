# jquery-typings
A type definition for jQuery that doesn't conflict with Angular Protractor.

When using angular-projector and jquery in the same project, the typings may cause Typscript errors for duplicate declares errors in some editors due to jQuery and Protractor both using `$`. This d.ts prevents that.
