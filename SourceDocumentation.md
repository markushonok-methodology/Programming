# Source Documentation

Source declarations and their XML documentation together form the consumer-facing contract of source code.

An exposed declaration must communicate enough of its contract to be understood and used correctly without reading its implementation.

Prefer expressing contract information through names, types, modifiers, and other declaration syntax. Add XML documentation for contract information required for correct use that the declaration itself does not communicate.

Judge redundancy against the declaration, not the implementation. Treat information that requires reading the implementation as absent from the declaration.

Document externally meaningful behavior and constraints, not implementation mechanics.

Place contract documentation on the declaration that owns the contract rather than repeating it on implementations or more specific declarations.

When a clearer declaration can communicate the contract, improve the declaration instead of explaining it in XML.