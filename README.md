# Weaver Solver

Weaver Solver is a web application that helps users find a solution to the popular game Word Ladder, popularly known as Weaver (https://wordwormdormdork.com/).

## Features

- Takes the 4 or 5 letter starting word and the 4 or 5 letter ending word as input
- Finds the sequence of words connecting the start and end words using a breadth-first-search algorithm
- Displays the word sequence in an easy-to-read format
- Built using HTML, CSS, JavaScript, Bootstrap, and PyScript

## Demo

https://weaversolver.tech/

## How the Algorithm Works
The algorithm uses a breadth-first search (BFS) approach, which ensures that it explores all possible paths from set_start before moving on to paths that require more transformations. This guarantees that the first path found is the shortest path.

- It begins by considering the set_start word as the initial state.
- It explores all possible neighboring words from this state and enqueues them.
- By repeatedly dequeuing paths and exploring their neighbors, the algorithm gradually progresses toward set_end.
- If it finds a path where the last word is set_end, it means it has successfully transformed set_start into set_end, and the path is returned as the result.
- This algorithm efficiently searches for a solution while avoiding unnecessary exploration by using a queue to maintain a systematic approach.
