# Notes

## Emails

## Useful Shortcuts

### Bash
`npm run dev` (admissions)

`npm run start` (em?)

### Node
`npm install cmder`


### Windows

#### Xd
`Shift + Scroll` Scroll horizontally

#### Zoom
`Ctrl + Alt + Shift + H` &rarr; Hide

`Alt + A` &rarr; Microphone Toggle

`Alt + S` &rarr; Share Screen Prompt

#### VSCode
From Command Prompt, `code .` opens current folder in code

#### Git

## Terminology

### EM
Yield: Period in which students get accepted and decide where they will go to Uni

### ITSM
#### ITSM Workflow Process
```mermaid
flowchart LR
    A[Detect] --> B[Record];
    B --> C{Classify};
    C -.-> D[Incident];
    D -.-> E[Investigate];
    E -.-> I[Resolve];
    C -.-> F[Request];
    F -.-> G[Fulfill];
    G -.-> I[Resolve];
    I --> J[Close];
```

#### Incident Triage

|   | High Impact | Medium Impact | Low Impact |
| :---: |  :---: | :---: | :---: |
| High Urgency | 1 | 2 | 3 |
| Medium Urgency | 2 | 3 | 4 |
| Low Urgency | 3 | 4 | 5 |

*Impact: Number of users/items affected/influenced*
*Urgency: Based on time until significant impact*

### T4\*
[T4 Training Resources](https://webservices.it.ufl.edu/t4/t4-training/)

**\* Side project**

## In Progress

### Workflow

<!-- HIDDEN UF WORKFLOW TEMPLATE
#### mermaid

```mermaid
gantt
title Deadlines
dateFormat MM/DD/YY
section Am I In
section Yield
section MLK
Add Alert     :done,      a1, 01/14/22, 1d
Monitor Alert :active,    a2, 01/14/22,01/18/22
MLK Day       :milestone, a3, 01/18/22, 24h
Remove Alert  :after a2     , 0d
```
-->

[Mermaid Documentation](https://mermaid-js.github.io/mermaid/#/)
##### Flowchart
```
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```  

##### Sequence Diagram
```
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
```

##### Gantt Diagram
```mermaid
gantt MD;
dateFormat  YYYY-MM-DD
title Adding GANTT diagram to mermaid
excludes weekdays 2014-01-10

section A section
Completed task            :done,    des1, 2014-01-06,2014-01-08
Active task               :active,  des2, 2014-01-09, 3d
Future task               :         des3, after des2, 5d
Future task2               :         des4, after des3, 5d
```

### Run 

#### Naming Conventions
- camelCase for vars
- underscores for images
- dashes for filenames
