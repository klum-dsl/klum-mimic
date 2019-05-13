KlumMimic
=======
We are Legion!

# What is KlumMimic?

KlumMimic is a part of the KlumDSL suite. It provides an easy way to create repeating fields or methods from a template.

While this is easily done using runtime metaprogramming using `methodMissing` or MetaClasses in Groovy, KlumMimic 
creates actual fields and methods during compile time. This has some major advantages:

- These methods/fields are visible from java as well (so the differences between Groovy Traits and MixIns)
- Out of the box IDE support. Since the methods are part of the compiled class, they can be read by any IDE to provide
  code completion and in IDE checks without the need to include IDE specific helpers (gdsl, dsld)
- The same holds true for `TypeChecked` Groovy classes. 
 

## Example

