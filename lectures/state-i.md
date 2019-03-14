# using state i

In this lecture, the students will be introduced to the concept of state and how to use it to make dynamic web apps. This will use the traditional `setState` to teach one-way databinding and other react ideas.

## Learning Objectives

- learn what state is
- be able to to use state to dynamic data
- pass data from state of parent to the child of a children
- state is immutable
- how to listen for events in React
- create-react-app

## Recommended Previous Knowledge

a student should be able to:

- define a react component
- use props that been passed to the component

## Slides

https://slides.com/markdewey-1/deck#/0/6

## Full Code Samples

Scoreboard:
https://github.com/suncoast-devs/cohort-xiii/tree/master/week-04/scoreboard/src

## Lecture notes

- start with the review of what is props
  - read only, static values passed from parent component
- intro the problem that state solves and what state is
  - our web apps need to be dynamic
- for code sample, create something with buttons and events
- start off listening to events and how to tie into those
  - explain onClick
  - events are good side tangent
  - console.log events + event.target.value
- then add some buttons that change things on the screen
  - counters are fun
- add an onChange to an input field

## Possible Assignments

- scoreboard
- color slider

## Actual Assignment

- [ScoreBoard](https://github.com/suncoast-devs/react-part-time-course/blob/master/homework/scoreboard.md)

## Additional Resources

- [react events](https://reactjs.org/docs/handling-events.html)
- [react state and life cycle](https://reactjs.org/docs/state-and-lifecycle.html)

## Next Lectures

- state ii - more practice
