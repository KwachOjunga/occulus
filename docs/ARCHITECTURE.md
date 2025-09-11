# Overview

In order for occulus' implementation to be feasible, it will have to defer most
of its decisions to external libraries.
This means provided a library offers some targeted functionality with minimal 
overhead and is sufficiently modular, it is OK to use it.
Having to make all decisions about implementation for it will be a difficult exercise;
it's better to have a working tool that can be later be altered than to have to decide 
about everything from scratch.

Implications of this:
- The frontend is to be built with Vanilla Javascript, Html and Css.
- Only go about rewriting a piece of code if whatever you want cannot be addressed by 
    select libraries.
- 