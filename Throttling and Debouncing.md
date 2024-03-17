#Throttling and Debouncing

### Throttling and debouncing are techniques used in web development to improve performance by controlling how often certain functions are executed, particularly in response to events like scrolling, resizing, or typing.

## Throttling:

Throttling limits the number of times a function can be called over a certain period. 

#### Example: Let's say you have a search bar, and you want to fetch search results from the server as the user types. Instead of sending a request for every keystroke (which could overload the server), you throttle the function handling the search so that it only runs every 300 milliseconds, for example. This way, if the user types quickly, the function won't execute on every keystroke, but rather at a controlled pace.

## Debouncing:

Debouncing is similar to throttling, but it delays the execution of a function until after a certain period of inactivity

#### Example: Let's say you have a form with a "submit" button, and you want to perform some validation or processing when the user finishes typing in an input field. You don't want to execute the function for every keystroke, so you debounce it to wait until the user stops typing for, let's say, 500 milliseconds. This prevents the function from running unnecessarily while the user is still typing and only triggers it once they've finished typing or paused for a moment.

### Usage:

1. Throttling is handy for tasks that need to be executed regularly but not too frequently, like updating the position of a scrollable element or handling mouse movement events.

2. Debouncing is useful for tasks that you want to perform only after the user has finished a series of actions, like resizing a window or typing in an input field.
####
In both cases, throttling and debouncing help optimize performance and prevent unnecessary resource consumption by controlling the rate at which functions are executed.
