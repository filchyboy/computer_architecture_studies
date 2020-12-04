# Computer Architecture

## Project

* [Implement the LS-8 Emulator](ls8/)

## Task List: add this to the first comment of your Pull Request

### Day 1: Get `print8.ls8` running

- [X] Inventory what is here
  * cpu.py - CPU class
  * ls8.py - loads and runs CPU
  * examples / 
    * call.ls8 - calls multiple subroutines
    * interrupts.ls8 - watches for interrupts
    * keyboard.ls8 - watches for keyboard commands
    * mult.ls8 - multiplies two numbers
    * print8.ls8 - prints number 8
    * printstr.ls8 - prints" Hello, World!"
    * sctest.ls8 - performs multiple tests
    * stack.ls8 - add and removes instructions from stack
    * stackoverflow.ls8 - simulates stackoverflow error


- [X] Implement the `CPU` constructor
- [X] Add RAM functions `ram_read()` and `ram_write()`
- [X] Implement the core of `run()`
- [ ] Implement the `HLT` instruction handler
- [ ] Add the `LDI` instruction
- [ ] Add the `PRN` instruction

### Day 2: Add the ability to load files dynamically, get `mult.ls8` running

- [ ] Un-hardcode the machine code
- [ ] Implement the `load()` function to load an `.ls8` file given the filename
      passed in as an argument
- [ ] Implement a Multiply instruction (run `mult.ls8`)

### Day 3: Stack

- [ ] Implement the System Stack and be able to run the `stack.ls8` program

### Day 4: Get `call.ls8` running

- [ ] Implement the CALL and RET instructions
- [ ] Implement Subroutine Calls and be able to run the `call.ls8` program

### Stretch

- [ ] Add the timer interrupt to the LS-8 emulator
- [ ] Add the keyboard interrupt to the LS-8 emulator
- [ ] Write an LS-8 assembly program to draw a curved histogram on the screen
