This is a subtopic that was included as a `git submodule`, because we need this as documentation for multiple projects.

## Here is some related code

This doesn't work, because the path is relative:

```c
--8<-- "hello_world.c"
```

This works, but it only works in this project, not in other projects, because the path has to be hardcoded in a shared file:

```c
--8<-- "smaller_topic/hello_world.c"
```