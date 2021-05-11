Very big topic. Very **important** as well.

## Here is some related code

This doesn't work, because the path is relative:

```c
--8<-- "more_important_code.c"
```

This works, but it only works in this project, not in other projects, because the path has to be hardcoded in a shared file:

```c
--8<-- "big_topic/more_important_code.c"
```

Global include:
```c
--8<-- "../global_world.c"
```
