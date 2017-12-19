---
layout: page
title: Tectonic Coding Principles
subtitle: Rules from the iron core
---

#### #1 Don't change interfaces. Ever.

When you change an interface, you potentially create a hidden bomb in the system. Don't do it. Add another interface and mark the old one deprecated instead. Or better yet, make a system that dynamically supports multiple versions.

#### #2 Layers are evil.

Don't add layers on top of layers. Some engineers love layers, because they have complicated minds, but each additional layer is an overhead, it makes architecture more complicated and that's the start of evil. 

Simple solutions are elegant, efficient and easy to maintain.

#### #3 Seek for simplicity. 

Engineers want to get bragging rights. They want to create complicated things because someone taught them to. But in reality, complicacy is just expensive waste.

#### #4 Each round-trip costs.

Minimize the communication round-trips and your users will joice the fast response time.

#### #5 Use the right tools for the job.

Some programming languages are more prone e.g. to memory leaks than others. Typical business application should not be written in a language like C++, because it is a dangerous tool in most hands. 

Use tools that are common, because it'll be easier to find developers.  

What will be the life-cycle of your product? You need someone to maintain it, so don't use dying technologies.

### #6 Code must be beautiful.

Beautiful and readable. That's the signature of a professional.
