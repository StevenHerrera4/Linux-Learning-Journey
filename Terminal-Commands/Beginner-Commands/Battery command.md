# Observing the battery health and consumption on Pop!_OS

**Objective:**
display battery information directly in the linux terminal.

**Operating System:**
Pop!_OS

## Step 1 — Access the terminal


```bash
# Open terminal with  SUPER + T (or open it in the applications area)
```

## Step 2 — Insert command
Command

```bash
# upower -i $(upower -e | grep BAT)
```

## Result
This command displays general information about the battery like percentage, energy-rate, energy-full, capacity, time to empty, cycle count and others.

## Issues Encountered
- No problem encountered

## What I Learned
- How to see my device battery life.
- The capacity it can give me and the time I can expect for the battery to be empty.
  
