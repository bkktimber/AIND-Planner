# Domain Independent Planner

This project includes skeletons for the classes and functions needed to solve deterministic logistics planning problems for an Air Cargo transport system using a planning search agent. With progression search algorithms like those in the navigation problem from lecture, optimal plans for each problem will be computed. Unlike the navigation problem, there is no simple distance heuristic to aid the agent. Instead, you will implement domain-independent heuristics.

This project has 2 parts:

## 1. Planning Problem
 Given 3 different problems with their conditions and goals in Air Cargo domain, I implemented methods and functions to satisfy each problem's goal in `my_air_cargo_problem.py` then experimented thoes problem with different types of search, including uniform search, depth-first search, and breadth-first search, then wrote an anlysis of each experiment in `heuristics_analysis.pdf`.

## 2. Domain-independent heuristics
 Problems in part 1 are modified to be more leaxed with method `AirCargoProblem.h_ignore_preconditions` in `my_air_cargo_problem.py` and are solved with Planning Graph with automatic heuristic in `my_planning_graph.py`. In contrast of part 1, part 2 use A* search for planning graph, the results are report in `heuristics_analysis.pdf`.

# Repository Structure
- `my_air_cargo_problem.py`: include problem statements in Air Cargo Domain and methods and functions for part 1 of the project.
- `my_planning_graph.py`: Planning Graph heuristic for part 2 of Air Cargo Domain.
- `heuristic_analysis.pdf`: Report results and provide analysis of part 1 and part 2 of this project.
- `researh_review.pdf`: Review of planning and search methods including _STRIPS_, _UCPOP_, and _Planning Graph_.
