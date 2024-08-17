# Hello Test-Driven Development

## Why TDD?

1. You know when you are finished, without having to worry about a long bug trail.
2. When you are writing a test, you are solving several problems at once, even when you've not written any code yet. E.g., the names, signatures, new classes or a factory method, etc.
2. It lets your teammates count on you, and you on them.

## Rules

1. Write new code only if an automated test has failed.
2. Eliminate duplication.

## Steps

The 2 rules imply an order of steps:
1. Red: at first, write a test that does nto work, and even does not compile.
2. Green: write the simplest code that makes the test pass, e.g., by faking.
3. Triangulate and Refactor: eliminate duplication.

Red/Green/Refactor is the TDD mantra.

## References

1. [Test-Driven Development by Example](./docs/ttd-by-example-Kent-Beck.pdf)