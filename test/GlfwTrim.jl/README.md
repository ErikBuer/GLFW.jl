Run from package root

```bash
julia --project=. -e "using JuliaC; JuliaC.main(ARGS)" -- --output-exe testapp --bundle build --trim=safe --experimental test/GlfwTrim.jl/GlfwTrim.jl
```