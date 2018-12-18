# auto-gen-code-blog-post-build-without-autogen-build-perf

Used to compare the performance of webpack between two identical projects with the exception that one uses babel-plugin-codegen to generate code and the other does not (this project).

## After a fresh dependency install
1. Running webpack-dev-server for the first time took **2906ms**
2. Subsequent webpack-dev-server (no changes) took **2820ms** (quicker maybe because of webpack / babel-loader caching)
3. Made change (added extra line) to index.js file component <Test50/> - reload took **194ms**

## Delete dependencies and then perform another fresh install
1. Running webpack-dev-server for the first time took **2897ms**
2. Subsequent webpack-dev-server (no changes) took **2723ms**
3. Made change (added extra line) to index.js file component <Test50/> - reload took **151ms**

## Delete dependencies and then perform another fresh install
1. Running webpack-dev-server for the first time took **3011ms**
2. Subsequent webpack-dev-server (no changes) took **2862ms**
3. Made change (added extra line) to index.js file component <Test50/> - reload took **159ms**


## Delete dependencies and then perform another fresh install
1. Running webpack-dev-server for the first time took **2848ms**
2. Made change (added extra line) to index.js file component <Test50/> - reload took **301ms**
3. Made change (added extra line) to index.js file component <Test50/> - reload took **433ms**
4. Made change (added extra line) to index.js file component <Test50/> - reload took **251ms**
5. Made change (added extra line) to index.js file component <Test50/> - reload took **215ms**

## Delete dependencies and then perform another fresh install
1. Running webpack-dev-server for the first time took **2792ms**
2. Made change (added extra line) to index.js file component <Test50/> - reload took **202ms**
3. Made change (added extra line) to index.js file component <Test50/> - reload took **166ms**
4. Made change (added extra line) to index.js file component <Test50/> - reload took **170ms**
5. Made change (added extra line) to index.js file component <Test50/> - reload took **135ms**
