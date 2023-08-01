# Single Level of Abstraction (SAL)

Every statement of a method should be on one abstraction level.

## Helps with
- Detail hiding
- Writing smaller methods
- Avoiding mental grouping

## Code smells
- **Body of Loops:** Often contains implementation details that can be extracted into an (private) method.
- **Comment followed by a block of code**: Most likely a candidate for a new method.
