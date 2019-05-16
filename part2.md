## Part 2

Use lifiting functions to make a real heirarchy in your todo app.

![https://github.com/wdi-sg/todo-react/blob/master/todo-part-2.png?raw=true](https://github.com/wdi-sg/todo-react/blob/master/todo-part-2.png?raw=true)

Given this component hierarchy:

  - `ItemList` should be stored as state at the top level.
  - `Form` can be it's own component, or be integrated into the top level component.
  - `TodoItem` will get passed the method that gets called for item delete.

#### further

When editing a todo item, put the validation in the edit as well. (this could be a modular form component that is used at the top level and for item edit)

#### further
Add the deleted items list

#### further
Make it so that items expire after a certain amount of time (5 mins, 1 day)

#### further
Make another level of hierarchy, where items can go into named lists (a la trello)

