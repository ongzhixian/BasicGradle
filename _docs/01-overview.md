# Overview

Write your build scripts in `build.gradle`

# Task types

1.  Simple tasks
    Defines the task with an action closure. 
    Action closure determines the behaviour of the task. 
    Good for implementing one-off tasks in your build script.

2.  Enhanced tasks

    where the behaviour is built into the task, and the task provides some properties which you can use to configure the behaviour. 
    We have seen these in Authoring Tasks. 
    Most Gradle plugins use enhanced tasks. 
    With enhanced tasks, you don’t need to implement the task behaviour as you do with simple tasks. 
    You simply declare the task and configure the task using its properties. 
    In this way, enhanced tasks let you reuse a piece of behaviour in many different places, possibly across different builds.

    