# Description

## Run instructions

Run the following commands

    docker run -it --name=test1 alpine:latest date
    docker run -it --name=test1 alpine:latest date

Why does this not work?
answer: It says /test1 container is already running.

What can you do to make them both run (there are at least a couple of ways)?

answer: Either we can rename the old container or we can remove it and use again

