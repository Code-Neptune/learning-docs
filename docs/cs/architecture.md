# Computer Architecture

Most modern computers are based on the **Von Neumann Architecture**.

## The Von Neumann Model
The key idea: **Data** and **Programs** are stored in the *same* memory.



[Image of Von Neumann Architecture diagram]


### Key Components
1.  **CPU (Central Processing Unit):** The "brain."
    * **ALU (Arithmetic Logic Unit):** Does the math ($+ - * /$) and logic (AND, OR).
    * **CU (Control Unit):** Directs the flow of data.
    * **Registers:** Tiny, super-fast storage inside the CPU (e.g., Accumulator, PC).
2.  **Memory (RAM):** Temporary storage for currently running programs.
3.  **I/O (Input/Output):** Keyboard, Mouse, Screen.

## The F-D-E Cycle
The heartbeat of the computer. It happens billions of times per second.

1.  **Fetch:** The CPU retrieves the next instruction from RAM.
2.  **Decode:** The CU figures out what the instruction means.
3.  **Execute:** The instruction is carried out (e.g., "Add 5 to Register A").