# GeoStats.jl @ JuliaEO2023

Instructor: [Júlio Hoffimann](https://github.com/juliohm)

## Agenda

- [10min]: Introduction slides
- [45min]: Advanced geodata science
- [15min]: Coffee break & questions
- [45min]: Geostatistical learning

## Instructions

### During the event

1. Download/clone the repository folder.
2. If you have Docker installed, change to the folder and run:
```bash
$ docker run -v ${PWD}:/home/javyon/geostats -p 8888:8888 gaelforget/notebooks:latest
```
3. Launch Pluto and open the notebook [geodatascience-docker.jl](geodatascience-docker.jl).

For more information, please follow the [event instructions](https://github.com/AIRCentre/JuliaEO/blob/main/docs/README-Docker-Intro.md).

### After the event

If you would like to run all notebooks after the live hands-on session, folow the steps below instead:

1. Install `Julia v1.8.3` from the [official website](https://julialang.org/downloads).
2. Install `Pluto v0.19.19` from the Julia REPL:
```julia
] add Pluto@0.19.19
```
3. Launch Pluto and open the notebooks [geodatascience.jl](geodatascience.jl) and [geostatslearn.jl](geostatslearn.jl)
