# Typing

The typing system handling should implement a formal parser for mathematical statements. Maybe take the actual conventions or create extended systems. Probably will have to implement all ops. Define structural element to typing spaces guiding the relations. 

 - Multiple contexts ??


Notes on contexts:

We are having an issue where the type checking is disconected from the parsing reality, making it hard to write "correct" and generic context handling. We might have to specify context handling rules in the spec. This might require spefic context bindings, or generic uses for switches. 

Something like 

$$
\Gamma \vdash \text{expr} \implies \Theta
$$
```

// var decl with initializer
Γ ⊢ init : type 
------------------------ (vardecl)
Γ → Γ[var:type] ⊢ type

------------------------ (stmt)
Γ → Γ' ⊢ void
```