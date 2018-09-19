# [fit] Class **Intro**
# [fit] HIIM 501

---
# [fit] **Infrastructure**
# [fit] of Informatics

---
> _Infrastructure_ is much more important than _Architecture_
-- Rem Koolhaas

---
## What **is** infrastructure?
##### Discuss

---
> Infrastructure is _pre-solved_ problems.

^ e.g. infrastructure in the economical sense.

---
## The Infrastructure of Informatics
> Information Technology is the Infrastructure of Health Informatics

```
┌──────────────────────────────────────────────────┐
│             _  _          _ _   _                │
│            | || |___ __ _| | |_| |_              │
│            | __ / -_) _` | |  _| ' \             │
│            |_||_\___\__,_|_|\__|_||_|            │
│                                                  │
│    ___       __                    _   _         │
│   |_ _|_ _  / _|___ _ _ _ __  __ _| |_(_)__ ___  │
│    | || ' \|  _/ _ \ '_| '  \/ _` |  _| / _(_-<  │
│   |___|_||_|_| \___/_| |_|_|_\__,_|\__|_\__/__/  │
│                                                  │
├────────────────┬────────────────┬────────────────┤
│                │                │                │
│   Computers    │   Algorithms   │    The Web     │
│                │                │                │
├────────────────┼────────────────┼────────────────┤
│                │                │                │
│    Software    │   Networking   │   Blockchain   │
│                │                │                │
└────────────────┴────────────────┴────────────────┘
```

---
# [fit] **Information** Technology

---
## Information technology includes any _device_, _protocol_, _application_ or other _artifact_ we use in the capture, storage, retrieval, and use of information.

^ We're being as inclusive as possible.

---
```
                                   ____      ____                           __  _
                                  /  _/___  / __/___  _________ ___  ____ _/ /_(_)___  ____
                                  / // __ \/ /_/ __ \/ ___/ __ `__ \/ __ `/ __/ / __ \/ __ \
                                _/ // / / / __/ /_/ / /  / / / / / / /_/ / /_/ / /_/ / / / /
                               /___/_/ /_/_/  \____/_/  /_/ /_/ /_/\__,_/\__/_/\____/_/ /_/

                                    ______          __                __
                                   /_  __/__  _____/ /_  ____  ____  / /___  ____ ___  __
                                    / / / _ \/ ___/ __ \/ __ \/ __ \/ / __ \/ __ `/ / / /
                                   / / /  __/ /__/ / / / / / / /_/ / / /_/ / /_/ / /_/ /
                                  /_/  \___/\___/_/ /_/_/ /_/\____/_/\____/\__, /\__, /
                                                                          /____//____/


                              ┌──────────────────────────┐     ┌──────────────────────────┐
                              │                          │░    │                          │░
                              │         Process          │░    │          System          │░
                              │                          │░    │                          │░
                              └──────────────────────────┘░    └──────────────────────────┘░
                               ░░░░░░░░░░░░░░░░░░░░░░░░░░░░     ░░░░░░░░░░░░░░░░░░░░░░░░░░░░


                              ┌──────────────────────────┐     ┌──────────────────────────┐
                              │                          │░    │                          │░
                              │          Design          │░    │  Metrics & Measurement   │░
                              │                          │░    │                          │░
                              └──────────────────────────┘░    └──────────────────────────┘░
                               ░░░░░░░░░░░░░░░░░░░░░░░░░░░░     ░░░░░░░░░░░░░░░░░░░░░░░░░░░░
```

------
# [fit] Processes

---
## Model of a **Process**
```
                ┌──────────────────────┐
                │                      │
                │                      │
  Input  ──────▶│    Transformation    │───────▶ Output
                │                      │
                │                      │
                └──────────────────────┘
```

^ What is left unspecified? Timing? Other constraints?

------
# [fit] Systems

---
## A **System** is a _composition_ of **Processes**

---
```



                     ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
                     │                                    ____         __                                           │
                     │                                   / __/_ _____ / /____ __ _                                  │
                     │                                  _\ \/ // (_-</ __/ -_)  ' \                                 │
                     │                                 /___/\_, /___/\__/\__/_/_/_/                                 │
                     │                                     /___/                                                    │
                     │                                                                                              │
                     │                                                 ┌──────────────────────┐                     │
                     │                                                 │                      │                     │
                     │                                                 │                      │                     │
                     │                                     ┌──────────▶│    Transformation    │────────────┐        │
                     │                                     │           │                      │            │        │
                     │                                     │   Input   │                      │            │        │
                     │  ┌──────────────────────┐           │           └──────────────────────┘            │        │
                     │  │                      │           │                                               │        │
                     │  │                      │   Output  │                                               │        │
          Input  ────┼─▶│    Transformation    │───────────┤                                               ├────────┼──▶ Output
                     │  │                      │           │                                               │        │
                     │  │                      │           │                                               │        │
                     │  └──────────────────────┘           │           ┌──────────────────────┐            │        │
                     │                                     │   Input   │                      │            │        │
                     │                                     │           │                      │            │        │
                     │                                     └──────────▶│    Transformation    │────────────┘        │
                     │                                                 │                      │                     │
                     │                                                 │                      │                     │
                     │                                                 └──────────────────────┘                     │
                     │                                                                                              │
                     └──────────────────────────────────────────────────────────────────────────────────────────────┘




```
------
# [fit] Design

---
> Everyone **designs** who devises courses of action aimed at changing existing situations into preferred ones.
-- Herbert Simon [^2]

[^2]: See pp. 111 of Simon, H. A. (2001) The Sciences of the Artificial (3rd ed.). Cambridge, MA: MIT Press.

^ Designing is identifying the processes, and arranging them into systems, that perform the change from existing (in) to desired (out) "situation"
Underline "processes" = action, "system" = courses of action, "in" existing, and "out" preferred

------
# [fit] Metrics & Measurement

---
# Metrics
> Everyone designs who devises courses of action aimed at changing _existing situations_ into _preferred ones_.
-- Herbert Simon [^2]

How are these situations specified?
How do we know we've moved from one to the other?

---
## _Measurement_ is the **process** of identifying the values of _Metrics_

---
## **Metrics** enable _Feedback_
```

                 ┌──────────────────────┐
                 │                      │
                 │    Transformation    │
   Input  ──────▶│      or System       │───────▶ Output
                 │                      │
     ▲           └──────────────────────┘            │
     │                                               │
     └───────────────────────────────────────────────┘
                          Feedback

```

---
# [fit] Systems **Thinking**

---
```



                     ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
                     │                                    ____         __                                           │
                     │                                   / __/_ _____ / /____ __ _                                  │
                     │                                  _\ \/ // (_-</ __/ -_)  ' \                                 │
                     │                                 /___/\_, /___/\__/\__/_/_/_/                                 │
                     │                                     /___/                                                    │
                     │                                                                                              │
                     │                                                 ┌──────────────────────┐                     │
                     │                                                 │                      │                     │
                     │                                                 │                      │                     │
                     │                                     ┌──────────▶│         ??           │────────────┐        │
                     │                                     │           │                      │            │        │
                     │                                     │   ??      │                      │            │        │
                     │  ┌──────────────────────┐           │           └──────────────────────┘            │        │
                     │  │                      │           │                                               │        │
                     │  │                      │   ??      │                                               │        │
             ??  ────┼─▶│          ??          │───────────┤                                               ├────────┼──▶ ??
                     │  │                      │           │                                               │        │
                     │  │                      │           │                                               │        │
                     │  └──────────────────────┘           │           ┌──────────────────────┐            │        │
                     │                                     │   ??      │                      │            │        │
                     │                                     │           │                      │            │        │
                     │                                     └──────────▶│         ??           │────────────┘        │
                     │                                                 │                      │                     │
                     │                                                 │                      │                     │
                     │                                                 └──────────────────────┘                     │
                     │                                                                                              │
                     └──────────────────────────────────────────────────────────────────────────────────────────────┘




```

---
## Systems Thinking

> Systems thinking is viewing technology as a System

1. Identify the inputs.
2. Identify the outputs.
3. Identify the transformation(s).
4. Iterate down or up.

---
# [fit] **Learning** Goals

---
## Learning Goals [^1]

- **Foundational Knowledge** - Systems, infrastructure, and lots of details.
- **Application** - Using many types of IT.
- **Integration** - Systems-thinking about the details and use of IT.

---
## Learning Goals [^1]

- **Human Dimension** - Comfortable, confident, resourceful, capable posture towards IT.
- **Caring** - Get excited about new IT _and_ maintain a hype-free perspective about IT.
- **Learning how to Learn** - Understand your internal scaffolding for IT, and know how to fill in the details when needed.

[^1]: See pp. 83-84 of Fink, L. D. (2013) Creating Significant Learning Experiences: An Integrated Approach to Designing College Courses. San Francisco, CA: Jossey-Bass

---
# [fit] Course **Structure**

---
## Modular Rhythm

```
                     Learning
                      Journal
   ┌──────────────────────────┐                                      ┌──────────────────────────┐     ┌──────────────────────────┐
   │                          │░                                     │                          │░    │                          │░
   │   Write Learning Goals   │───────────────────┐                  │    Lectures & Reading    │────▶│   Write Quiz Questions   │░
   │                          │░                  │                  │                          │░    │                          │░
   └──────────────────────────┘░                  │                  └──────────────────────────┘░    └──────────────────────────┘░
    ░░░░░░░░░░░░░│░░░░░░░░░░░░░░                  │                   ░░░░░░░░░░░░░│░░░░░░░░░░░░░░     ░░░░░░░░░░░░░│░░░░░░░░░░░░░░
                 │                                │                                │                                │
                 │                                ▼                                ▼                                ▼
                 │                  ┌──────────────────────────┐     ┌──────────────────────────┐     ┌──────────────────────────┐
                 │                  │                          │░    │                          │░    │                          │░
                 │                  │                          │░    │   In the Wild Analysis   │░    │                          │░
                 │                  │                          │░    │                          │░    │                          │░
                 │                  │                          │░    └──────────────────────────┘░    │                          │░
                 │                  │  Complete & Reflect on   │░     ░░░░░░░░░░░░░│░░░░░░░░░░░░░░    │     Complete Recall      │░
                 │    Learning      │  Real World Assignments  │░                  │                  │     Practice Quizzes     │░
                 ▼     Journal      │                          │░                  ▼                  │                          │░
   ┌──────────────────────────┐     │                          │░    ┌──────────────────────────┐     │                          │░
   │                          │░    │                          │░    │                          │░    │                          │░
   │   Reflect on Learning    │░    │                          │░    │  In the Wild Discussion  │░    │                          │░
   │                          │░    │                          │░    │                          │░    │                          │░
   └──────────────────────────┘░    └──────────────────────────┘░    └──────────────────────────┘░    └──────────────────────────┘░
    ░░░░░░░░░░░░░▲░░░░░░░░░░░░░░     ░░░░░░░░░░░░░│░░░░░░░░░░░░░░     ░░░░░░░░░░░░░│░░░░░░░░░░░░░░     ░░░░░░░░░░░░░│░░░░░░░░░░░░░░
                 │                                │                                │                                │
                 └────────────────────────────────┴────────────────────────────────┴────────────────────────────────┘

```

^ Learning journals are an opportunity to design :)

---
## Real World Assignments

We want to envision ourselves practicing real-world informatics skills, specifically those related to IT.

* Set up a server
* Make changes to a website
* Write a small program
* Navigate any OS
* *Find relevant documentation*


---
# [fit] Course **Schedule**

---
## Course Schedule

| Week(s) | End Date | Topics                                            |
|:--------|----------|---------------------------------------------------|
| 1       | Sept. 2  | Class Intro, Systems Thinking, & Infrastructure   |
| 2-4     | Sept. 23 | Electronic Computers                              |
| 5-7     | Oct. 14  | Software Systems                                  |
| 8-10    | Nov. 4   | Computer Networking                               |
| 11-13   | Nov. 25  | The Web                                           |
| 14-15   | Dec. 9   | Integrated IT Systems & Hot Topics                |
|         | Dec 13   | **Final Date to Submit Work**                     |
