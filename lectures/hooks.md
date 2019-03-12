# learning about hooks

In this lecture, students will learn about the new (as of early 2019) feature called [hooks](https://reactjs.org/docs/hooks-intro.html). This is build on the students already understanding of state in react. During this lecture students will learn about the downfalls of class components and `setState`

## Learning Objectives

- A list of learning goals for this lecture
- I.e., what should the student learn after experiencing this lecture

## Recommended Previous Knowledge

This is what concepts the student should be familiar with in order to benefit from this lecture.

## Slides

https://slides.com/markdewey-1/intro-to-reactwhat-is-react-26#/

## Full Code Samples

- [scoreboard with hooks](https://github.com/suncoast-devs/cohort-xiii/tree/master/week-06/scoreboard-hooks)
- [movie list with hooks](https://github.com/suncoast-devs/cohort-xiii/tree/master/week-06/movies-hook)
- [weather api with effect and hooks](https://github.com/mdewey/weather-hooks)

## Lecture notes

- set context

  - talk about [array destructuring](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment)
  - walk through some examples, of why this is cool
    - syntax sugar
    - work better with return values
    - less mutating, more immutable

  ```javascript
  const arr = [10, 12, 13, 14]
  //we can do this
  const [first, second, ...theRest] = arr
  // instead of this
  const first = arr[0]
  const second = arr[1]
  const theRest = arr.splice(2) // note this will also modify the array arr, destructuring will not alter
  ```

  - talk about [functional components](https://reactjs.org/docs/components-and-props.html)

    - smaller, lighter
    - easier to reason about
    - though read only (no state) (until now)
    - less state-full and less relying on OOP

  - now you can talk about hooks

    - hooks allow us to use state in functioanl component
    - instead of gian state object, each part of state gets its own 'mini state'
    - same concepts as state, rendering on update
    - [https://reactjs.org/docs/hooks-intro.html](https://reactjs.org/docs/hooks-intro.html)
    - be able to `useState` in a functional component
    - no more life cycle events

  - Code Demo: take a past project, refactor to use functional components and then to `useState`

  - Code Demo: `useEffect` to talk to an API

## Possible Assignments

- redo a past assignment with hooks
- color slider with hooks

## Additional Resources

- [https://reactjs.org/docs/hooks-intro.html](https://reactjs.org/docs/hooks-intro.html)
- [functional components](https://reactjs.org/docs/components-and-props.html)

## Possible Next Lectures

- Army Builder (practice)
- Router (next topic)
