# Sass malloc error sample repo

Sass crashes under certain situations. Repo to show the cases.

Related issue: https://github.com/dlmanning/gulp-sass/issues/104#issuecomment-161632080


## Instructions

1. Fork and clone repo
2. `npm install -g gulp` in case you don't have it
3. `gulp styles`

Rendered error on my machine:

```
gulp(771,0x7fff79c4c180) malloc: *** error for object 0x1025437dc: pointer being freed was not allocated
*** set a breakpoint in malloc_error_break to debug
Abort trap: 6
```

More instructions at `./app/styles/main.scss`

node_modules folder was commited to lock versions of the dependencies so you can debug in the same circumstances.


Cheers!
