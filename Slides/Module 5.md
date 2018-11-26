# [fit] The **Web**

---
> The **Web** is a global information network made up of a family of _protocols_ and _standards_ for _hypermedia_.

^
Hypermedia is media with links - hypertext.

---
## Minimum Viable Web - **Web 1.0**

- Protocol for _addressing_ documents.
- Standard format for _storing_ documents.
- Protocol for _communicating_ about documents.
    - **C**reating
    - **R**eading
    - **U**pdating
    - **D**eleting

^
Notice the links to our basic computer: storage, processing, IO. Which is missing?

---
##

![fit](Figures/m5 p1 of WWW Paper 1992.pdf)

---
## Modern Web - **Web 2.0**

Web 1.0 + **Interactivity**

- Two More Standards:
    - A Programming Language
    - Style Sheets
- Web Apps

---
## Web Protocols

```
                                                 ┌────────────────────────────────┐
                                                 │                                │░
                                                 │       __  __________________   │░
                                                 │      / / / /_  __/_  __/ __ \  │░
                                                 │     / /_/ / / /   / / / /_/ /  │░
                                                 │    / __  / / /   / / / ____/   │░
                                                 │   /_/ /_/ /_/   /_/ /_/        │░
                                                 │                                │░
                                                 └────────────────────────────────┘░
                                                  ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░


                                                            __________  _  __
                                                        __ / / __/ __ \/ |/ /    ┌────────────────────────────────┐
                                  _____________        / // /\ \/ /_/ /    /     │                                │░
                                 / ___/ __/ __/        \___/___/\____/_/|_/      │       __  ______  __           │░
                                / /___\ \_\ \                                    │      / / / / __ \/ /   _____   │░
                                \___/___/___/                                    │     / / / / /_/ / /   / ___/   │░
                                                                                 │    / /_/ / _, _/ /___(__  )    │░
                                   ┌────────────────────────────────┐            │    \____/_/ |_/_____/____/     │░
                                   │                                │░           │                                │░
                                   │       __  __________  _____    │░           └────────────────────────────────┘░
                                   │      / / / /_  __/  |/  / /    │░            ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
                                   │     / /_/ / / / / /|_/ / /     │░
                                   │    / __  / / / / /  / / /___   │░
                                   │   /_/ /_/ /_/ /_/  /_/_____/   │░                ______
                                   │                                │░            __ / / __/
                                   └────────────────────────────────┘░           / // /\ \
                                    ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░           \___/___/
```

------
# [fit] URLs


---
```

       ┌────────┐ ┌─┐                                                         ┌──────┐
 >>────│ scheme │─│:│─┬─────────────────────────────────────────────────────┬─│ path │─┬───────────────┬──┬──────────────────┬───────><
       └────────┘ └─┘ │                                                     │ └──────┘ │               │  │                  │
                      │ ┌────┐                      ┌──────┐                │          │ ┌─┐ ┌───────┐ │  │ ┌─┐ ┌──────────┐ │
                      └─│ // │─┬──────────────────┬─│ host │─┬──────────────┤          └─│?│─│ query │─┘  └─│#│─│ fragment │─┘
                        └────┘ │                  │ └──────┘ │              │            └─┘ └───────┘      └─┘ └──────────┘
                               │ ┌──────────┐ ┌─┐ │          │ ┌─┐ ┌──────┐ │
                               └─│ userinfo │─│@│─┘          └─│:│─│ port │─┘
                                 └──────────┘ └─┘              └─┘ └──────┘
```

```


http://myname:mypass@example.com:8888/patients/123/labs/456?result=2&units=g#page5



https://en.wikipedia.org/wiki/Uniform_Resource_Identifier#/media/File:URI_syntax_diagram.png
```

------
# [fit] HTTP

------
# [fit] HTTP**S**

------
# [fit] HTML

------
# [fit] JS

------
# [fit] CSS

------
# [fit] XML &
# [fit] JSON

------
# [fit] **Semantic**
# [fit] Web
---
