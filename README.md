# Maegistrate, Inc.

Cert-grade systems engineering. Verifiable where it matters; functional
where it helps. 

Mostly heads-down; occasional contributions to projects
we depend on or admire.

## Philosophy

<table width="100%">
<colgroup>
<col width="20%">
<col width="42%">
<col width="38%">
</colgroup>
<thead>
<tr><th></th><th>Modern</th><th>Foundational</th></tr>
</thead>
<tbody>
<tr><td><b>Systems</b></td><td>Rust, Zig, Odin, Hare</td><td>C, C++, Ada, Forth, Assembly</td></tr>
<tr><td><b>Functional</b></td><td>Haskell, OCaml, Scala, F#, Erlang/Elixir, Lean 4</td><td>Lisp, Scheme, ML, Miranda, Lambda calculus</td></tr>
</tbody>
</table>

Strong opinions on systems: ownership, type-level invariants, allocator
discipline, compile-time composition. *The closer to the metal the work
runs, the more interesting it gets.*

Strong opinions on functional: effect tracking, algebraic data types,
supervision discipline, the bias toward total functions over partial
ones. *The right type makes the wrong state hard to spell.*

## Discipline

<table width="100%">
<colgroup>
<col width="35%">
<col width="65%">
</colgroup>
<tr><td><b>No swallowed failures</b></td><td>Errors propagate or get explicit rationale</td></tr>
<tr><td><b>Illegal states unrepresentable</b></td><td>Encode invariants at the type level</td></tr>
<tr><td><b>Pure cores, effectful edges</b></td><td>Effects tracked; total where the type permits</td></tr>
<tr><td><b>Exhaustive pattern matching</b></td><td>No catch-alls that swallow new cases</td></tr>
<tr><td><b>No accidental quadratics</b></td><td>Complexity claimed up front; WCET when deployed</td></tr>
<tr><td><b>Strict-by-default static analysis</b></td><td>Explicit allowance ledger for every exception</td></tr>
<tr><td><b>Qualified toolchains, MISRA-grade source</b></td><td>Where the deployment context calls for it</td></tr>
<tr><td><b>Mutation-tested coverage</b></td><td>Tests that don't kill mutations get rewritten</td></tr>
<tr><td><b>Supply-chain discipline</b></td><td><code>cargo-deny</code> for Rust; equivalents elsewhere</td></tr>
<tr><td><b>Independent peer review</b></td><td>Before any change ships</td></tr>
</table>
