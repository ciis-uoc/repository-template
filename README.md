# Repository Template

Dieses Repository dient als beispielhafte Vorlage für das Capstone Project Information Systems der Universität zu Köln.

Das Repository bilded einen Scrum-Workflow innerhalb von GitHub ab. Dieser beinhaltet ein Kanban-Board für das Backlog, spezifizierte Labels für Prioritäten, Storypoints, etc., und beispielhafte Backlog-Items.

## Verwendung des Templates

- Specify the .gitignore file depending on your technology stack

### Labels

Das Repository beinhaltet bereits vordefinierte Labels für Prioritäten, Storypoints (1-40), sowie die Typen Features, Bugs, und Tests.

Jedes Backlog-Item sollte entsprechend mindestens mit einem Storypoints-, Prioritäts-, und Typen-Label markiert werden.

Je nach Bedarf, können auch weitere Labels erstellt werden.

### Backlog

- Bei Bedarf auch weitere Boards möglich

## Repository Struktur

`docs`: Hier können Abgaben oder andere Dokumente, die im Verlauf des Capstone Projects erstellt werden, abgelegt werden.

## Velocity

| Sprints | Planned | Achieved |
|:-------:|:-------:|:--------:|
|    1    |         |          |
|    2    |         |          |
|    3    |         |          |
|    4    |         |          |
|    5    |         |          |

## Project Planning

```mermaid
gantt
        dateFormat  YYYY-MM-DD
        title Adding GANTT diagram functionality to mermaid
        section A section
        Completed task            :done,    des1, 2014-01-06,2014-01-08
        Active task               :active,  des2, 2014-01-09, 3d
        Future task               :         des3, after des2, 5d
        Future task2               :         des4, after des3, 5d
        section Critical tasks
        Completed task in the critical line :crit, done, 2014-01-06,24h
        Implement parser and jison          :crit, done, after des1, 2d
        Create tests for parser             :crit, active, 3d
        Future task in critical line        :crit, 5d
        Create tests for renderer           :2d
        Add to mermaid                      :1d
```

<!-- Insert image -->

## Issue Template

## Description

As a user, I want to be able to log-in to the system to access my personal information.

## Acceptance Criteria

- The user is logged in if the entered e-mail matches the entered password
- The system informs the user if the login succeeds / fails

## Tasks

- [ ] Build log-in form
- [ ] Implement back-end function to check input
- [ ] Test with correct and incorrect inputs
