# py-reqcue
Dependency resolution to install Python projects

## Idea

1. Take the requirements.txt file of the project
1. Run a custom dependency resolver applying various strategies
1. Create a freeze file with all (transitive) dependencies pinned
1. Install that using pip without dependency resolution
1. Run static analysis to verifiy dependencies in code. (Should be possible? All symbols resolve, only reachable from own source code?)
