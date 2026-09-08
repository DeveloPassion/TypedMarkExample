# TypedMark Example

A minimal publishable TypedMark `0.1.0` system used to exercise the reference
tooling in [DeveloPassion/TypedMark](https://github.com/DeveloPassion/TypedMark).

The system defines one `note` type and one scaffolded welcome note. Instantiating
it must produce a self-contained working collection that:

- retains the system's schemas and templates;
- records `@developassion/typedmark-example` version `0.1.0` as composition
  provenance;
- uses a caller-supplied collection identity;
- omits the source system's `version` and `scaffold`; and
- validates without access to this source directory.

The system intentionally has no `.typedmark/history.md`. An attempted automatic
upgrade from an earlier version therefore requires manual classification instead
of guessing migration operations.
