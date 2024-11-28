export LANG=C.UTF-8

using Pkg
Pkg.add("CSV")
Pkg.add("DataFrames")

using CSV
using DataFrames


alunos_icomp = CSV.read("historico-CC-ES-2024-11-06.csv",encoding="UTF-8", DataFrame)
