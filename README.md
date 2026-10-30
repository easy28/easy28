# Hi, I'm Liang Fu

I build **[RegexTester.dev](https://regextester.dev)** — a free online regex tester that runs **real regex engines in your browser via WebAssembly**: PCRE2, RE2, ECMAScript, Python, Go, Java, .NET, and Rust. No sign-up, no cookies, no server round-trips for matching.

## Why it's different

- Every flavor is the actual engine compiled to WASM — not a JavaScript approximation — so behavior matches the real library, edge cases included
- A step-by-step pattern explainer and a backtracking debugger (with a flame graph of every backtrack step)
- An [AI regex generator](https://regextester.dev/ai-regex-generator) that turns plain English into patterns
- A [community gallery](https://regextester.dev/gallery) of 14,000+ real-world patterns with permalinks
- A [compatibility checker](https://regextester.dev/compat) that flags where your pattern behaves differently across flavors

## Cheat sheet

- [Regex Flavor Matrix](https://easy28.github.io/regex-flavor-matrix/) — which flavor supports lookbehind, atomic groups, recursion, `\K`, and more
