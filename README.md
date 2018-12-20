# auto-gen-code-blog-post-build-without-autogen-build-perf

Used to compare the performance of webpack between two identical projects with the exception that one uses babel-plugin-codegen to generate code and the other does not (this project).

## Fresh dependency install - cold start: webpack-dev-server start up times
- Run 1: 2422ms
- Run 2: 2755ms
- Run 3: 2803ms
- Run 4: 2699ms
- Run 5: 2762ms
- **Average**: **2688.2ms**

## Previously started and stopped webpack-dev-server: webpack-dev-server start up times
- Run 1: 2629ms   
- Run 2: 2465ms
- Run 3: 2518ms
- Run 4: 2565ms
- Run 5: 2485ms
- **Average**: **2532.4ms**

## Running webpack-dev-server, component index.js file change: compile time for change
- Run 1: 167ms
- Run 2: 152ms
- Run 3: 225ms
- Run 4: 155ms
- Run 5: 131ms
- **Average**: **166ms**
