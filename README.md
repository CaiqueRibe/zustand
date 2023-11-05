<img src="image.png" alt="Alt text" width="600">

# Zustand React State Management Course (Simple Redux Alternative)

https://www.youtube.com/watch?v=fZPgBnL2x-Q&ab_channel=freeCodeCamp.org

Learn Zustand in this full course for beginners. Zustand is a minimalistic state management library for React, offering a simpler API compared to Redux. It aims to provide ease-of-use without sacrificing flexibility and performance in modern web applications. It provides a simple and intuitive API for managing and updating application state without the need for boilerplate code or complex patterns.

**Project** --> Kanban Board using react and zustand<br>
**Channel** --> freeCodeCamp.org 8,55 mi de inscritos<br>
**Date Created** --> 25 de abr. de 2023

### npm Commands

npm create vite .<br>
npm i zustand <br>
npm i classnames <br>

-  className={classNames("column", { drop: drop })}
-  <div className={classNames('status', task.state)}>{task.state}</div>
   npm i --save-dev vitest @testing-library/jest-dom @testing-library/react jsdom<br>
   npm i immer<br>
-  state manipulation a bit differently
-  tasksInOngoing: 0, addTask: async (title, state) => set(produce((store) => { store.tasks.push({ title, state }) }), false, "addTask")

### Components

-  main
-  App
-  Comlumn
-  Task
-  store(zustand)

### Observations/Notes

-  A small, fast and scalable bearbones state-management solution using simplified flux principles. Has a comfy API based on hooks, isn't boilerplatey or opinionated.<br>
-  Don't disregard it because it's cute. It has quite the claws, lots of time was spent dealing with common pitfalls, like the dreaded [zombie child problem](https://react-redux.js.org/api/hooks#stale-props-and-zombie-children), [react concurrency](https://github.com/bvaughn/rfcs/blob/useMutableSource/text/0000-use-mutable-source.md), and [context loss](https://github.com/facebook/react/issues/13332) between mixed renderers. It may be the one state-manager in the React space that gets all of these right.

### [Why zustand over redux?](https://github.com/pmndrs/zustand#why-zustand-over-redux)

-  Simple and un-opinionated
-  Makes hooks the primary means of consuming state
-  Doesn't wrap your app in context providers

### [Why zustand over context?](https://github.com/pmndrs/zustand#why-zustand-over-context)

-  Less boilerplate
-  Renders components only on changes
-  Centralized, action-based state management

⭐️ **Contents** ⭐️<br>
0:00:00 Why Zustand?<br>
0:07:28 Setting Up Our Project<br>
0:09:45 Creating The Basic Components<br>
0:17:48 Storing Tasks<br>
0:19:50 Disclaimer About Object State<br>
0:23:39 Displaying Tasks<br>
0:25:48 Adding Tasks<br>
0:34:55 Deleting Tasks<br>
0:37:57 Moving Tasks<br>
0:45:34 Using Zustand Middleware<br>
0:52:08 Unit Testing Zustand Stores<br>
1:08:27 Advanced Zustand Features<br>
1:14:17 Outro
