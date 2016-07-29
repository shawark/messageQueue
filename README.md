# MessageQueue
This is tool to set job queue and dispatch to worker.
This can be useful to set up distributed hosting master/slaves.

# Use

## Start server
```
./messageQueue -n <number of workers>
```

## Submit work
```
curl <server>:8000/work -d name=$USER -d delay=<delay> -d command=<command>
```
