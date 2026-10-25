# Airport Priority and Round Robin Scheduling

## Aim
To implement Priority Scheduling and Round Robin Scheduling in C using airport runway traffic control and taxiway management as real-world use cases.

## Real-World Use Case
This project models airport operations where flights share limited runway and taxiway resources.

### Part A: Priority Scheduling
Flights are assigned priority values. A lower number represents a more urgent flight, such as one with low fuel. Flights are arranged by priority and allocated runway time.

### Part B: Round Robin Scheduling
Flights share the taxiway in fixed time slices. A flight that has remaining taxi time waits for its next turn until it reaches its gate.

## Algorithms Implemented
- Priority Scheduling
- Round Robin Scheduling with a time quantum of 2 units

## Technologies Used
- Programming Language: C
- Concepts: Operating Systems, CPU Scheduling, Priority Scheduling, Round Robin Scheduling, Time Quantum and Preemption

## Files
- `PS.c` — Priority Scheduling for airport runway traffic.
- `RRS.c` — Round Robin Scheduling for airport taxiway traffic.
- `priority_output.png` — Priority scheduling output from the lab manual.
- `round_robin_output.png` — Round Robin output from the lab manual.

## How to Compile and Run

### Priority Scheduling
```bash
gcc PS.c -o PS
./PS
```

### Round Robin Scheduling
```bash
gcc RRS.c -o RRS
./RRS
```

## Expected Outcome
Priority Scheduling displays the flight landing order and time slots. Round Robin Scheduling displays how flights take turns using the taxiway until their remaining taxi time reaches zero.

## Conclusion
Priority and Round Robin scheduling algorithms demonstrate two approaches to allocating shared resources. Priority Scheduling handles urgent flights first, while Round Robin provides fair, cyclic access to taxiway resources.
