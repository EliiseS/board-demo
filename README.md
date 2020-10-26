# Github boards with Scrum

This repository is to demonstrate an example of how to use Github project boards with Scrum

## Issue types

- **Epics** are milestones that contain all tasks and user stories related to that epic
- **User stories** are issues with:
  - the `user story` label
  - a check list referring to the tasks in the user story
  - a link to a milestone
- **Tasks** are issues with:
  - the `task` label
  - a link to a milestone

These issue types could be supported and enforced using Github issue templates, for example see the [bug report template](.github/ISSUE_TEMPLATE/Bug_Report.md)
  
> **Additonal consideration**: Create a label per user story that would be added to the user story and each of it's tasks. This would allow for more tight coupling of user stories to their tasks and better filtering. However, this would increase the maintence overhead per story and the label itself wouldn't have a direct link to the story
  
## Estimations

Estimations is done using size labels on user stories and task, for example `size/L`, `size/S`

## Prioritization

Prioritization is done using priority labels on user stories and tasks, for example `priority/Low`, `priority/High`

## Sprints

Sprints are managed using projects, with a single project representing a single sprint, for example: [`Sprint 0` project](https://github.com/EliiseS/board-demo/projects/1). Once a sprint is finished the project can be closed

## Backlog

For managing the backlog there is a [`Backlog` project](https://github.com/EliiseS/board-demo/projects/2). The project allows for an overview of all the available user stories and managing the prioritizations for each upcoming sprint

## Parking lot

In addition, for managing the daily stand up parking lot there's a [`Parking lot` project](https://github.com/EliiseS/board-demo/projects/3) avaliable to add issues up for discussion


