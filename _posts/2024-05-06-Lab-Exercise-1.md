---
title: Lab Exercise 1
author: Xiao Cheng
date: 2024-05-06
category: Lab
layout: post
---

## Lab-Exercise-1 folder layout
```
$tree Lab-Exercise-1
├── GraphTraversal.cpp
├── GraphTraversal.h
├── test.cpp
├── CMakeLists.txt
```

## * You need to update the docker image with the steps in this [page](https://github.com/SVF-tools/Software-Security-Analysis/wiki/Update%E2%80%90to%E2%80%90the%E2%80%90latest%E2%80%90Docker%E2%80%90Image).
## 1. Lab-Exercise-1 coding task

- Implement methods `printPath` and `DFS` of class `GraphTraversal` in [`GraphTraversal.cpp`](https://github.com/SVF-tools/Software-Security-Analysis/blob/main/Lab-Exercise-1/GraphTraversal.cpp). 
- Pass the test without any assertion by [`test.cpp`](https://github.com/SVF-tools/Software-Security-Analysis/blob/main/Lab-Exercise-1/test.cpp)
- Submit `GraphTraversal.cpp` to canvas. Your implementation will be evaluated against our 10 internal tests. You will get the full marks if your code can pass them all. Unfortunately, our internal tests are private. Here, we only provided one test case in `test.cpp`. You are encouraged to add more test cases by yourself to validate the correctness of your implementation.


#### *You will be working on `GraphTraversal.cpp` only and there is **NO** need to modify other files under the Assignment-1 folder

## 2. Configuration && debugging 
### 1. [launch.json](https://github.com/SVF-tools/Software-Security-Analysis/blob/main/.vscode/launch.json)
You need to set the `"program" to be the executable file of Lab 1, i.e., "${workspaceFolder}/bin/gTrav"` in
launch.json in order to run and debug

<img src="https://github.com/SVF-tools/Software-Security-Analysis/blob/slides/images/launch1.png" alt="Alt text" title="Optional title" width="800" />


### 2. Debug your code

#### *If there is an assertion or unexpected output, you will need to debug and find bugs.

#### Step 1: Set the breakpoint where you want to stop your program and press the 'debug' button

<img src="https://github.com/SVF-tools/Software-Security-Analysis/blob/slides/images/ass-1debug1.png" alt="Alt text" title="Optional title" width="800" />


#### Step 2: 'Step over' /'Step in' / 'Step out' 
- 'Step over' to the next step of your program
- 'Step in' to the current line of your program
- 'Step out' to mainstream of your program where you stepped in before

<img src="https://github.com/SVF-tools/Software-Security-Analysis/blob/slides/images/ass-1debug2.png" alt="Alt text" title="Optional title" width="800" />


#### Step 3: During your debugging, you can also watch the value of a variable you are interested in. 




-------

#### More information about C++

- https://www.learn-cpp.org
- https://www.w3schools.com/cpp/ 
- https://www.learncpp.com
- https://www.programiz.com/cpp-programming 
- https://www.tutorialspoint.com/cplusplus/

