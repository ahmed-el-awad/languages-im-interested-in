# What's this?

A general summary of the languages that I am interested in, alongside a roadmap on which I'd learn before starting another (in theory).

# Isn't this too simple?

That's the point. I haven't mentioned details (such as concurrency for Go and Elixir) for the sake of brevity.

There are a lot more things to say to those languages that I glanced over.

<br>

```mermaid
graph
	PLs[Programming Languages]

	PLs --> Mu{{Multiple Uses}}
	Mu --> JS(JavaScript)
	JS -->|JavaScript with Types| TS(TypeScript)

	PLs --> Simple{{Simple}}

	Simple --> |Functional| Elixir(Elixir)
	Simple --> |Low Level| C(C)
	Simple --> |High Level| Go(Go)
	Elixir -->|Functional, OOP| OCaml(OCaml)
	OCaml --> Hard
	Hard -->|Functional but Hard| Haskell(Haskell)
	Hard{{Hard}} -->|Low Level but Hard| Rust(Rust)
	C -->|Low Level but Hard| Rust
	C -->|High Level| Go
```
