# Advanced-Physical-Design-Using-Open-Lane-Sky130
# Hitesh Kalavagunta
## DAY 1 INCEPTION OF OPEN SOURCE EDA, OPENLANE AND SKY 130
### Arduino Board :
<img width="248" alt="image" src="https://github.com/user-attachments/assets/97eebb77-bf93-40c9-86df-504f04c92abf" />
<img width="248" alt="image" src="https://github.com/user-attachments/assets/fa5635a2-3b28-4fa7-a092-607a87ad66e1" />

### This is a High Level View which can be represented through a block diagram

<img width="487" alt="image" src="https://github.com/user-attachments/assets/b5daac77-1118-4abf-afe6-cc9a75e36c28" />

### SoC - System on a Chip (Circled Component)

### A chip is inside a package. It is connected to pins or inputs and outputs. It has 3 main components :-
Pads: These are the connection points on a PCB (printed circuit board) where components like resistors, capacitors, or chips are soldered.

Core: This could refer to the central part of a microchip or the magnetic core in a transformer, depending on context. In semiconductors, "core" often refers to the central processing unit or the active part of a chip.

Die: This is the small piece of semiconductor material, often silicon, that contains the integrated circuit (IC). A die is typically the part of a chip that is processed and manufactured to form the final product.

<img width="478" alt="image" src="https://github.com/user-attachments/assets/2c96aad8-df0b-4ddb-94fb-cb22310220c3" />

 This is called a Package technically

 ### Schematic Representation :-
<img width="361" alt="image" src="https://github.com/user-attachments/assets/9189d40e-c2d3-40ac-804c-2b41b33e47ff" />
<img width="402" alt="image" src="https://github.com/user-attachments/assets/fe4b6fda-1a47-4cfc-a5f9-e66cdd52e3e6" />
<img width="374" alt="image" src="https://github.com/user-attachments/assets/e851dcb8-25f0-49af-9003-67b2b2ff43cd" />
<img width="392" alt="image" src="https://github.com/user-attachments/assets/cebac180-c588-4a2b-a763-1e140f5c0cf9" />

### Foundry : A semiconductor foundry is a company that manufactures chips on behalf of other companies, which may design the chips themselves but lack the facilities (fab) to actually produce them. Companies like TSMC (Taiwan Semiconductor Manufacturing Company) and Samsung are prominent foundries. They take in designs (often developed by fabless companies) and fabricate the physical chips.

### IP (Intellectual Property): In the context of semiconductors, IP refers to pre-designed and pre-verified blocks of logic or circuitry that can be used in creating a chip. Examples include processor cores, memory controllers, and various other functional blocks. Companies like ARM or Imagination Technologies provide IP that others integrate into their own custom chip designs.

<img width="473" alt="image" src="https://github.com/user-attachments/assets/a551abc7-a588-456e-a7c5-ec885a33183e" />

### Macros refer to pre-designed, reusable blocks of logic or circuits that perform specific functions. These macros can be components like:

Standard cells: Basic building blocks (such as logic gates, flip-flops, etc.) that are used in chip design.

Memory macros: Pre-designed memory blocks, such as SRAM, ROM, or DRAM, that can be integrated into a design without the need to design the memory from scratch.

Analog macros: Pre-designed analog circuits, like amplifiers or voltage regulators.

<img width="558" alt="image" src="https://github.com/user-attachments/assets/3dfb9b9f-3af4-426c-afe9-488348bbdec9" />

### RISC-V (Reduced Instruction Set Computing - Five) is an open-source instruction set architecture (ISA) based on the principles of RISC. It defines a set of simple, efficient commands that a processor can execute. RISC-V is unique because it's open (publicly available for anyone to use) and modular (allowing customization based on the needs of different applications).

### From Software applications to Hardware

<img width="565" alt="image" src="https://github.com/user-attachments/assets/e3b2644c-529b-4188-9ebf-78adade4ed63" />
<img width="554" alt="image" src="https://github.com/user-attachments/assets/a4f8ada1-63c6-4a5f-bb84-a5929d9c831c" />
<img width="555" alt="image" src="https://github.com/user-attachments/assets/0e5aa646-1f15-4e69-832d-5afe9823cf1b" />
<img width="572" alt="image" src="https://github.com/user-attachments/assets/b5267162-faf4-439b-a2da-d2415bfad905" />

### SoC Design and OpenLane

<img width="507" alt="image" src="https://github.com/user-attachments/assets/15791099-622e-4e32-b4c1-1414cda154f9" />

RTL IPs: Pre-designed blocks of logic (like processors or controllers) described at the register transfer level, using Verilog or VHDL.

EDA Tools: Software tools (like Cadence, Synopsys) used to design, simulate, and verify chips.

PDK Data: A kit containing design rules, models, and simulation data specific to a manufacturing process (e.g., 7nm process) to help create compatible chip designs.

<img width="515" alt="image" src="https://github.com/user-attachments/assets/92edb657-ff30-4a9e-8a87-5046344bde62" />

<img width="518" alt="image" src="https://github.com/user-attachments/assets/10235bac-cbd1-4d77-8942-4d5a7927edc0" />

<img width="536" alt="image" src="https://github.com/user-attachments/assets/91d42132-382b-4aa0-9cda-da6e67de31b3" />
<img width="373" alt="image" src="https://github.com/user-attachments/assets/192c6caf-834c-415f-b06a-8016c85a6c29" />
<img width="374" alt="image" src="https://github.com/user-attachments/assets/a85c172f-90e0-4d32-82bf-f5e4a31446f1" />
<img width="347" alt="image" src="https://github.com/user-attachments/assets/be218151-9486-4fcc-8cde-ef0aca5844ed" />
<img width="338" alt="image" src="https://github.com/user-attachments/assets/89eb9515-b22d-4279-8d77-6c09acb9a6f5" />
<img width="361" alt="image" src="https://github.com/user-attachments/assets/8fc773f8-3485-4c25-bd3d-42c3bdb448b2" />
<img width="353" alt="image" src="https://github.com/user-attachments/assets/344f22cc-5a8a-4487-ac88-a3fd6e76d429" />
<img width="370" alt="image" src="https://github.com/user-attachments/assets/4f3337e3-50bb-48e5-9d33-ccb6d021745d" />
<img width="367" alt="image" src="https://github.com/user-attachments/assets/b2e66e54-582c-4eaf-80d9-6328ff594b65" />
<img width="366" alt="image" src="https://github.com/user-attachments/assets/ab6a52f9-a082-4527-9003-a4ebb1b316e1" />
<img width="228" alt="image" src="https://github.com/user-attachments/assets/e9de1f7b-54e3-420d-aead-9fa63dc7ab04" />

Design Rule Check (DRC): This step ensures that the design follows the manufacturing process rules and is suitable for fabrication. DRC checks the layout to find and fix potential issues that could lead to defects during chip production.

Layout vs. Schematic (LVS): In this step, the physical layout of the chip is compared to the original schematic design to make sure they match. LVS tools extract the netlist from both the layout and schematic, looking for any discrepancies before moving on to the next stage of the design process.

Static Timing Analysis (STA): STA checks the timing of the digital circuit to verify that the design meets key requirements like setup and hold times, clock speed, and other timing constraints. This ensures the chip will operate reliably at the intended performance levels.

### OPEN LANE

<img width="527" alt="image" src="https://github.com/user-attachments/assets/aa78f987-751a-4807-9234-f3a99dcad5d0" />

### strive soc family

<img width="517" alt="image" src="https://github.com/user-attachments/assets/ca21a09d-ee6e-4fba-a978-8c22e2fb14c7" />

### Open Lane ASIC Flow

<img width="532" alt="image" src="https://github.com/user-attachments/assets/c0cd1ae5-0916-41b2-b895-6bdaea5992ce" />

The ASIC (Application-Specific Integrated Circuit) design flow is the process used to design a custom chip tailored for a specific application. It involves several steps, from initial concept to the final manufactured chip. Here’s a simplified overview of the typical ASIC design flow:

Specification: Define the chip's functional requirements, performance targets, and other parameters.

RTL Design: Create the design using a hardware description language (HDL) like Verilog or VHDL. This is the logic that dictates how the chip will operate.

Synthesis: Convert the RTL design into gate-level logic (standard cells). This step translates the high-level RTL code into a form that can be implemented physically in silicon.

Placement & Routing: Position the cells on the chip (placement) and connect them (routing) to form the actual layout.

Verification:

Functional Verification: Ensure the design works as expected at the RTL level through simulation.
Physical Verification: Verify that the layout meets design rules and can be manufactured (using tools like DRC - Design Rule Check and LVS - Layout vs. Schematic).
Timing Analysis: Ensure the chip will operate at the desired speed by checking the timing constraints (e.g., setup/hold times).

Tape-out: The final design is sent for fabrication to the foundry, where the chip is manufactured.

Post-Silicon Validation: After fabrication, the chip is tested in real hardware to ensure it works as intended.

### Design for Test

<img width="528" alt="image" src="https://github.com/user-attachments/assets/99b2e59f-726b-42ec-9ff0-c200d334ecfa" />

### PnR

<img width="523" alt="image" src="https://github.com/user-attachments/assets/e4fb10af-5c5b-4795-9947-ca78852e9a81" />

### Antenna Violations

<img width="526" alt="image" src="https://github.com/user-attachments/assets/3be2c7cc-ed0d-4438-a57c-1bca4fb691c8" />

<img width="520" alt="image" src="https://github.com/user-attachments/assets/3c3631ea-db29-47d7-a9ac-9a98aee4d6ce" />
<img width="496" alt="image" src="https://github.com/user-attachments/assets/601d1f6c-444a-4c0a-a5fe-c303461f2038" />

### Open Source Directory

<img width="304" alt="image" src="https://github.com/user-attachments/assets/901c25d4-5740-4477-abf7-380bdb8af40a" />
<img width="379" alt="image" src="https://github.com/user-attachments/assets/afb31705-8117-4831-9952-40926fef5ded" />

### Design Preparation Steps

<img width="599" alt="image" src="https://github.com/user-attachments/assets/613fa1d0-b927-4866-9d0e-5b7e5c65a658" />

<img width="313" alt="image" src="https://github.com/user-attachments/assets/8670feeb-47e5-4c52-aff1-4b293fc55df0" />

<img width="382" alt="image" src="https://github.com/user-attachments/assets/d60eb7cf-2664-4f5b-9123-334363fcf8f3" />

<img width="469" alt="image" src="https://github.com/user-attachments/assets/35c99d46-6f45-4017-a31a-84cf8680a974" />

## DAY 2 GOOD FLOORPLAN VS BAD FLOORPLAN AND INTRODUCTION TO LIBRARY CELLS

### Utilization Factor and Aspect ratio

<img width="427" alt="image" src="https://github.com/user-attachments/assets/f8164ec6-26ed-442a-83d4-08ed225cff25" />

<img width="464" alt="image" src="https://github.com/user-attachments/assets/f2d716c7-db02-4b4e-aa29-da6b1199dcb6" />

Converting symbols to physical dimensions

<img width="401" alt="image" src="https://github.com/user-attachments/assets/080036d7-e089-47cc-bc9a-cc131ef30159" />

### Area

<img width="412" alt="image" src="https://github.com/user-attachments/assets/c35eb950-c731-40c4-8a6f-41f920c557cc" />
<img width="583" alt="image" src="https://github.com/user-attachments/assets/2c9204e6-60df-4cea-b238-af9857af265c" />

### Utilization, Aspect Ratio

Utilization refers to the percentage of available area in the chip layout that is actually used by standard cells (or other components). It’s an important metric because:
High Utilization: If utilization is high, it means most of the chip area is being used, potentially leading to more compact designs.
Low Utilization: If utilization is low, there may be wasted space, which can impact power, performance, and area (PPA) goals. It could also lead to inefficiencies in routing and wire congestion.
Goal: Designers aim for a balanced utilization level to optimize space while avoiding excessive congestion or wasted area.

Aspect ratio refers to the ratio of the height to the width of a chip or a specific region within the chip layout.
Aspect Ratio in the Whole Chip: It's important for overall design efficiency and for ensuring that routing resources are used effectively. For example, a square aspect ratio might be preferred because it allows for better routing flexibility.
Aspect Ratio of Cells: It can also refer to the ratio of the height and width of individual cells. A balanced aspect ratio helps maintain good performance and routing during the layout phase.

<img width="242" alt="image" src="https://github.com/user-attachments/assets/c10dd100-50ce-4ca0-8aea-157c7ddcd5fc" />
<img width="142" alt="image" src="https://github.com/user-attachments/assets/eb06faf1-cb18-44f0-9805-fb20de6e4a83" />
<img width="229" alt="image" src="https://github.com/user-attachments/assets/33467e3f-a7e7-4663-a5a7-9608132d3774" />

### Preplaced Cells

Preplaced cells are specific standard cells that are placed in fixed locations during the design process, usually before the rest of the placement happens. This is typically done to optimize certain areas of the design for timing, power, or functionality. For example, critical components like clock trees, power grids, or certain high-performance logic might be preplaced to ensure their proper operation.

<img width="530" alt="image" src="https://github.com/user-attachments/assets/02ea45ea-9faa-46d8-96f9-be68b276c3f9" />
<img width="284" alt="image" src="https://github.com/user-attachments/assets/0b022cba-6d21-4024-b7f0-69f47f497f6b" />
<img width="457" alt="image" src="https://github.com/user-attachments/assets/9b805ee0-5153-40d9-922f-ce51c877aefa" />

<img width="454" alt="image" src="https://github.com/user-attachments/assets/a2a6bf7d-0d0e-4d0a-b233-f63c4c1e9d2a" />
<img width="418" alt="image" src="https://github.com/user-attachments/assets/2f58afce-bd8c-436d-b3ee-6ba509f1ba30" />
<img width="575" alt="image" src="https://github.com/user-attachments/assets/96b033a3-064f-4215-9767-378eabb046f2" />

### Noise Margin

Noise margin refers to the amount of noise a digital signal can tolerate before it causes errors in logic levels (i.e., before it is misinterpreted as a 0 or 1). It essentially measures the "safety buffer" between the valid signal levels and the noise that might interfere with them. Higher noise margins indicate more robust and noise-tolerant circuits.

<img width="487" alt="image" src="https://github.com/user-attachments/assets/a69bd921-3aa7-41a3-8fac-1647f63b8fba" />

### Decoupling capacitors are components used in electronic circuits to help stabilize the power supply and reduce noise. They are typically placed close to power supply pins of integrated circuits (ICs) and other sensitive components.

<img width="573" alt="image" src="https://github.com/user-attachments/assets/e3b246dc-1515-41bb-a43c-9312203cc1bd" />

### Power planning in chip design refers to the process of managing and optimizing the power distribution network (PDN) for an integrated circuit (IC). It ensures that the chip receives the required power to operate efficiently, while minimizing issues like noise, voltage drops, and excessive power consumption.

<img width="416" alt="image" src="https://github.com/user-attachments/assets/493238eb-f169-4279-968b-14baa6e68905" />

<img width="451" alt="image" src="https://github.com/user-attachments/assets/a8f162e7-0a0d-4a96-ad73-b2236c31b948" />

<img width="437" alt="image" src="https://github.com/user-attachments/assets/acefd9a3-8c21-49cd-9cbb-e1c05d35f3f6" />

<img width="515" alt="image" src="https://github.com/user-attachments/assets/392e1db3-0117-4e00-a59d-e7bf46e4d62b" />

### Pin Placement

<img width="467" alt="image" src="https://github.com/user-attachments/assets/a83cbb1c-5747-4634-a467-b8e4cd171702" />
<img width="472" alt="image" src="https://github.com/user-attachments/assets/a6f62787-f20b-4924-a361-b50aae0fc485" />

<img width="466" alt="image" src="https://github.com/user-attachments/assets/6fce18a4-aabe-49a3-b076-473707a25faa" />

### Netlist
A netlist is a textual representation of a circuit, listing all the components (e.g., logic gates, transistors, capacitors) and the electrical connections (or "nets") between them. It describes how the components are interconnected in a circuit, without specifying their physical layout. In the context of digital design, a netlist typically includes:

Key Points:
Components: The netlist lists all the elements in the design, such as standard cells (e.g., AND gates, flip-flops), pads, and external pins.

Connections: The netlist specifies how these components are connected by electrical nets, which are essentially the wires or traces between components.

<img width="428" alt="image" src="https://github.com/user-attachments/assets/5b154864-2be3-477f-8048-73d6ab3023b2" />

### Steps to run Floorplan using OpenLane

<img width="227" alt="image" src="https://github.com/user-attachments/assets/87f30301-6e9d-456f-be1b-66a7d1bb7d81" />
<img width="538" alt="image" src="https://github.com/user-attachments/assets/a1ff2fae-601d-4cc4-b0d0-6d8cf2216ac1" />

Running a floorplan in OpenLane involves using the open-source EDA toolchain to set up the basic layout of your chip design, including placing major components (like macros, IOs, power/ground grids), setting power planning, and defining the constraints for the placement and routing stages.

<img width="512" alt="image" src="https://github.com/user-attachments/assets/b792d9e6-ad35-4ddd-9b30-92caed5a9d14" />
<img width="461" alt="image" src="https://github.com/user-attachments/assets/6f718984-195d-4898-90db-ab4360349294" />
<img width="177" alt="image" src="https://github.com/user-attachments/assets/0da9c492-c318-4b3d-b2cc-7766db2f34dd" />
<img width="500" alt="image" src="https://github.com/user-attachments/assets/c45cf781-aa58-4b6a-a1ce-faa35b8be0f8" />

### Reviewing Floorplan Layout in Magic

<img width="355" alt="image" src="https://github.com/user-attachments/assets/8eb518e3-d915-45df-8d2b-a7b8d61efbb9" />

### Library

In the context of ASIC design, a library refers to a collection of pre-designed, standardized building blocks (cells) that can be used to create a digital circuit. These cells implement basic logic functions (AND, OR, NOT gates, flip-flops, etc.) and are designed to be used repeatedly in a chip's design.

There are several types of libraries used in chip design:

1. Standard Cell Library:
A standard cell library contains a collection of basic logic gates (AND, OR, NOT), storage elements (flip-flops, latches), and other circuit elements that can be used to build more complex designs.
Each cell in the library is characterized by its functionality, timing, power consumption, area, and other performance parameters.
Cells are designed for specific technology nodes (e.g., 7nm, 14nm, etc.), and they define how the design will behave when synthesized, placed, and routed.
2. I/O Library:
The I/O library contains cells that manage the input and output interfaces of the chip, such as pad cells (for connecting external pins to the internal circuits) and buffers.
These cells include components like input/output pads, level shifters, and drivers to ensure proper signal communication between the chip and external devices.
3. Memory Libraries:
These libraries include pre-designed memory blocks like SRAM (Static RAM), ROM (Read-Only Memory), and FIFO (First-In, First-Out) buffers.
Memory libraries are often used to save time and effort when incorporating large memory arrays into the chip design.
4. Analog/Custom Libraries:
In analog and mixed-signal designs, libraries may include components such as op-amps, voltage regulators, transistors, and capacitors.
These are used in designs where the logic is not purely digital.
Key Parameters for Cells in a Library:
Area: The physical space a cell occupies on the chip.
Timing: The delay introduced by a cell in the signal path (e.g., setup time, hold time, propagation delay).
Power: The power consumption of a cell, which can be dynamic (related to switching activity) or static (related to leakage currents).
Noise Margin: The tolerance of a cell to noise, ensuring it reliably interprets logic levels.

<img width="580" alt="image" src="https://github.com/user-attachments/assets/4fe0d1f9-fa77-4707-baac-a994c44097d9" />

<img width="598" alt="image" src="https://github.com/user-attachments/assets/afa44723-a67d-4a02-a753-0c717c03bfb2" />

### Setup Timing Analysis

Setting up timing analysis in a digital chip design is essential for verifying that your design will meet its timing constraints and operate at the desired speed. Static Timing Analysis (STA) helps you check whether the signals propagate through the design within the required time limits, ensuring that setup and hold times are met for each flip-flop and that the circuit operates at the intended clock frequency.

<img width="356" alt="image" src="https://github.com/user-attachments/assets/b963e57d-9f21-44b8-864d-c803cc5d1549" />


<img width="563" alt="image" src="https://github.com/user-attachments/assets/5833f943-d8cb-4b82-b619-1467a1c9a21e" />

### Library Characterization

<img width="455" alt="image" src="https://github.com/user-attachments/assets/56914c0d-37f1-4c4d-8eab-274f75ac9cea" />

### General timing Characterization Parameters

<img width="506" alt="image" src="https://github.com/user-attachments/assets/5c4a1d18-d310-4eaa-887a-47dbe6e3ebe5" />

<img width="443" alt="image" src="https://github.com/user-attachments/assets/a81c154a-25be-4e08-8a19-33270f2198ed" />

### Cell Design Flow

<img width="542" alt="image" src="https://github.com/user-attachments/assets/1ae4220e-45c8-40c9-b307-379022ddf846" />
<img width="559" alt="image" src="https://github.com/user-attachments/assets/b03d0ad4-939d-4585-86cb-c3ddf46f4af1" />
<img width="542" alt="image" src="https://github.com/user-attachments/assets/7257650e-d3a2-43c8-982e-b78fdbb653c9" />
<img width="564" alt="image" src="https://github.com/user-attachments/assets/0e592c94-552c-4734-b5f1-a89ce26dc9c4" />
<img width="555" alt="image" src="https://github.com/user-attachments/assets/28d04398-2c00-4efd-b141-9f19d96e3e97" />

<img width="539" alt="image" src="https://github.com/user-attachments/assets/fc04943d-a326-4569-a0d0-a1c7bfc4d74d" />

<img width="515" alt="image" src="https://github.com/user-attachments/assets/f9b66b58-0353-4529-9f40-34f455db02c0" />

<img width="190" alt="image" src="https://github.com/user-attachments/assets/1829c682-0b6e-4cb7-81da-5befa445b0d0" />

<img width="521" alt="image" src="https://github.com/user-attachments/assets/4176132a-57d9-4656-b162-046aba03e9bf" />

### Typical Characterization Flow

<img width="520" alt="image" src="https://github.com/user-attachments/assets/2407a681-660a-4226-af6b-515a8f0eaad7" />
<img width="557" alt="image" src="https://github.com/user-attachments/assets/04c5f823-b579-40f0-bf18-0a759098d1b6" />

<img width="545" alt="image" src="https://github.com/user-attachments/assets/0e3723ac-d469-440f-bc25-9b3ed80d8550" />

### Timing Characterization

Timing characterization refers to the process of measuring and documenting the timing behavior of digital cells (gates, flip-flops, etc.) in a standard cell library. The goal is to understand how each cell responds to different conditions, like process variations, voltage changes, and temperature shifts. This data is crucial for performing Static Timing Analysis (STA) and ensuring that the design meets timing requirements.

In simple terms, timing characterization helps provide accurate data that allows tools to predict how the circuit will behave under various conditions and optimally place and route the design.

<img width="549" alt="image" src="https://github.com/user-attachments/assets/4793a447-f5a6-42ac-9004-b3a8c04cec45" />

### Propagation Delay

<img width="542" alt="image" src="https://github.com/user-attachments/assets/02191ac0-6eab-4361-93a0-2ba67852ecb8" />

Propagation delay is the time it takes for a signal to travel from the input to the output of a digital logic gate or cell. It is a key parameter in digital circuit design, as it directly affects the speed and timing of the entire circuit. Propagation delay is typically measured in nanoseconds (ns) and is crucial for Static Timing Analysis (STA) to ensure that a design meets its required timing constraints.

<img width="533" alt="image" src="https://github.com/user-attachments/assets/3a73ba63-6857-48f2-8d62-19d9492b3f4c" />

### Transition Time

<img width="245" alt="image" src="https://github.com/user-attachments/assets/3e9b2cf3-f336-40bf-a065-6f0de24d07da" />

Transition time refers to the time it takes for a signal to change between two logical states (typically from low to high or high to low) in a digital circuit. It’s an important factor in the performance and timing of digital circuits, as the speed of these transitions can impact propagation delays, timing violations, and overall signal integrity.

<img width="542" alt="image" src="https://github.com/user-attachments/assets/d719d590-3480-4c65-ab98-3682dd401529" />

## DAY 3 DESIGN LIBRARY CELL USING MAGIC LAYOUT AND NG SPICE CHARACTERIZATION

<img width="247" alt="image" src="https://github.com/user-attachments/assets/6c62dbc5-9bdb-4c10-9fc6-72470f2cbf0e" />

### SPICE

SPICE (Simulation Program with Integrated Circuit Emphasis) is a widely used simulation tool for analyzing and simulating the behavior of electrical circuits, especially in the realm of analog and mixed-signal designs. It is essential for evaluating the performance of electronic circuits before they are physically built, saving time, cost, and helping to ensure that designs meet functional and timing requirements.

<img width="581" alt="image" src="https://github.com/user-attachments/assets/a8b60ee9-d644-44a0-9fa3-5580679082a3" />

<img width="578" alt="image" src="https://github.com/user-attachments/assets/ff794ba3-9da2-4cbf-81ee-f77d8b7f54bb" />

<img width="575" alt="image" src="https://github.com/user-attachments/assets/e02b5297-a8cb-46bd-bd25-6f0fb28b9845" />

<img width="575" alt="image" src="https://github.com/user-attachments/assets/74937b15-1e4c-4d98-ba54-f0b0f8e2ce2b" />

<img width="556" alt="image" src="https://github.com/user-attachments/assets/71aee4e9-1538-49ba-97df-cda0c7c482d3" />

<img width="538" alt="image" src="https://github.com/user-attachments/assets/60364fc5-74ed-4e72-9490-cbceb91bf1fb" />

<img width="548" alt="image" src="https://github.com/user-attachments/assets/e7eefb57-fb17-4622-8a15-2b6f35185f67" />

<img width="131" alt="image" src="https://github.com/user-attachments/assets/4d14cdbb-b2eb-4a53-a86e-9104f8aa6f44" />

### Fabrication Process

The inception of layout fabrication refers to the early stages of the semiconductor manufacturing process where the design of an integrated circuit (IC) is translated into a physical layout that can be fabricated on a silicon wafer. The 16-mask process refers to the number of masks used in a specific semiconductor fabrication process, typically in advanced nodes like 16nm or 14nm, which indicates the scale of the process and the complexity of the manufacturing steps involved.

Key Steps in the Layout Fabrication Process (16-mask Process):
Design Entry and Layout Creation:

The IC design starts at the RTL (Register Transfer Level) stage, where the functional logic of the chip is defined. Once the design is complete and verified, it is converted into a physical layout using CAD tools.
This layout represents the physical dimensions of the IC and specifies the position of each component (transistors, resistors, capacitors, etc.) on the silicon wafer.
Mask Design and Photolithography:

The layout is translated into a set of masks used in the photolithography process during fabrication.
A mask is essentially a photographic stencil that defines patterns that will be transferred onto the silicon wafer at different layers. For a 16-mask process, 16 separate masks are used to define all the layers and features needed to manufacture the IC.
Photomask Generation:

Each mask represents a specific layer of the chip, such as the metal layers, diffusion layers, polymer layers, and so on.
The photomask generation process involves turning the layout design into mask files, which are then used to etch the desired patterns on the silicon wafer. This step is extremely critical, as even minor mistakes at the mask stage can lead to defects in the final chip.
Photolithography Process:

Photolithography is used to transfer the design patterns from the masks onto the wafer.
In photolithography, a light-sensitive photoresist is applied to the wafer. A mask is then placed over the wafer, and light is used to expose the photoresist. The exposed regions are developed and etched, leaving behind the desired pattern on the wafer.
This step is repeated for each mask, with each mask defining a different layer of the circuit (such as the gate layer, interconnects, etc.).
Etching and Deposition:

After photolithography, the exposed areas of the wafer are etched to remove unwanted material and create the desired patterns.
In addition to photolithography and etching, other processes such as chemical vapor deposition (CVD), physical vapor deposition (PVD), and dopant implantation are used to deposit thin films, control the conductivity of materials, and define the characteristics of transistors.
Multiple Mask Layers:

For a 16-mask process, each mask defines a different layer in the chip. These layers include:
Active Layers (defining transistors, diffusion regions, etc.)
Interconnect Layers (defining wiring between transistors)
Metal Layers (the final conductive layers that connect different components on the chip)
These layers are stacked on top of one another, and each one is defined by a separate mask.
16-Mask Process Specifics:
In a 16-mask process, the 16 masks correspond to the following typical layers:

Active Layer (Transistor Formation): The region where transistors are created.
Gate Layer (Polymer Layer): The gate material of the transistors is patterned.
Source/Drain Diffusion Layer: Defines the regions where the source and drain of the transistors are formed.
N+ and P+ Doping Layers: These define the regions of n-type and p-type doping in the chip.
Isolation Layers: For defining regions of isolation between different transistors or circuits.
First Metal Layer: Defines the first level of interconnections (usually aluminum or copper) that connect the transistors.
Second Metal Layer: Defines the second level of interconnections, typically for more complex routing between larger regions of the circuit.
Third Metal Layer: More interconnections, typically used for longer-distance connections.
Via Layers: Define the connections between different metal layers.
Contact Layers: Define the locations where the transistors connect to the metal layers.
Bonding Pads: Define the locations where external connections will be made to the chip.
Dielectrics: Layers of insulating material to separate conductive regions and reduce capacitance.
Final Metal Layer: The top layer of metal that completes the chip’s interconnects.
Passivation Layer: A protective layer to prevent contamination and physical damage to the chip.
Etch Stop Layer: Layers used to control etching depth and avoid damage to underlying layers.
Topcoat or Final Coating Layer: This layer ensures the physical protection of the chip’s wiring and can be used for testing and final packaging.
Each mask must be extremely accurate, as any misalignment during the photolithography step can cause major defects. The number of masks used increases with process complexity. In more advanced fabrication processes (e.g., 7nm, 5nm), the number of masks used can be much higher.

Challenges in a 16-Mask Process:
Mask Alignment: As the process nodes shrink, precise alignment of the masks becomes increasingly critical. Even a slight misalignment can lead to short circuits, open circuits, or layout violations.
Resolution and Patterning: With smaller process nodes, the patterns on the masks become finer, which makes them harder to etch onto the wafer. Techniques like extreme ultraviolet (EUV) lithography are sometimes used to achieve higher resolution.
Yield Losses: Manufacturing at advanced nodes can lead to yield losses due to defects at any step of the fabrication process. The more masks there are, the more opportunities for defects to occur.
Cost: The complexity of the 16-mask process requires highly sophisticated equipment and advanced technology, which significantly increases the cost of both masks and wafer processing.
Conclusion:
The 16-mask process is a critical part of modern semiconductor fabrication, especially in advanced nodes like 16nm or 14nm, where it is used to produce the intricate layers and patterns required for high-performance ICs. Each of the 16 masks plays a unique role in defining different layers of the chip, and the precision required in creating these masks and performing photolithography is a key factor in ensuring the quality and functionality of the final product.

As semiconductor technology advances, the number of masks and the complexity of the manufacturing process continue to increase, requiring even more advanced tools and techniques for precision and accuracy.

### Substrate

In semiconductor manufacturing, a substrate is the base material on which an integrated circuit (IC) is built. The substrate serves as the foundation for the entire fabrication process and plays a key role in the performance, electrical characteristics, and mechanical stability of the final chip.

<img width="451" alt="image" src="https://github.com/user-attachments/assets/4f38fdff-e47a-4390-8621-71815ef5e720" />

<img width="208" alt="image" src="https://github.com/user-attachments/assets/f93433ef-e8df-48f6-a8d8-b3062c645c2e" />

<img width="194" alt="image" src="https://github.com/user-attachments/assets/81bb07fb-9fa0-4466-b6aa-dff4e605bf4f" />

<img width="554" alt="image" src="https://github.com/user-attachments/assets/decc58f7-ff91-43d9-9dff-ae69c9a708ba" />

<img width="234" alt="image" src="https://github.com/user-attachments/assets/8f1a454b-3c43-4c0f-91cb-7d6e3fa51382" />

<img width="197" alt="image" src="https://github.com/user-attachments/assets/c8ea0ed5-6f6f-481f-8dd7-d913eb1780ff" />

## DAY 4 PRE LAYOUT TIMING ANALYSIS AND IMPORTANCE OF GOOD CLOCK TREE


<img width="209" alt="image" src="https://github.com/user-attachments/assets/4e044036-57bf-4540-9f85-1e9748145f11" />

### Delay Table

A delay table is often used in the context of timing analysis in digital circuits, particularly in ASIC and FPGA designs. It provides the delay values associated with various components (gates, wires, etc.) of the circuit, which helps in determining the timing behavior of a design. The delay table can be used for both static timing analysis (STA) and in the characterization of cells in a library to estimate the propagation delay and other timing characteristics.

<img width="347" alt="image" src="https://github.com/user-attachments/assets/c0240294-9ef6-4dcc-be77-cb010a5cae16" />

<img width="583" alt="image" src="https://github.com/user-attachments/assets/43557175-40d0-4ffd-a4e8-918227efb8ac" />

<img width="569" alt="image" src="https://github.com/user-attachments/assets/4e9ea62c-55e4-4923-982d-e2450b080df7" />

<img width="559" alt="image" src="https://github.com/user-attachments/assets/abfa9539-604e-4b7f-8492-56ad43b3cbfb" />

<img width="561" alt="image" src="https://github.com/user-attachments/assets/2c1e27cc-d745-46a0-b130-ec8fe5e8f142" />

<img width="236" alt="image" src="https://github.com/user-attachments/assets/789981b1-9222-457b-bfb6-176fc3a860df" />

<img width="266" alt="image" src="https://github.com/user-attachments/assets/b67f7202-da39-4337-8231-edef22ea0348" />

<img width="428" alt="image" src="https://github.com/user-attachments/assets/bcc3fe7b-8d12-4828-8e29-17c8a823cc38" />

### Setup Timing Analysis

<img width="559" alt="image" src="https://github.com/user-attachments/assets/75cc3064-0ffd-4439-8508-197c20968421" />

<img width="541" alt="image" src="https://github.com/user-attachments/assets/29653092-af4b-4c4b-964a-f37c9581e670" />

<img width="565" alt="image" src="https://github.com/user-attachments/assets/e0821e8d-2840-4c08-82af-a460bde22e12" />

### Clock Jitter

Clock jitter refers to small, rapid variations in the timing of a clock signal, often in terms of period or phase. It occurs when there are discrepancies in the expected arrival times of clock pulses, causing the clock edges (rising or falling) to shift slightly from their intended positions.

In digital circuits, the clock signal is critical for synchronizing operations. Jitter can cause problems, especially in high-speed designs, because it can lead to timing errors, setup violations, hold violations, and signal integrity issues.

<img width="469" alt="image" src="https://github.com/user-attachments/assets/334a686c-a857-4195-831a-a1485022e28b" />

<img width="313" alt="{534E354E-46A0-43D7-91FA-7E4B22154CC6}" src="https://github.com/user-attachments/assets/707960b9-b95b-4b60-aa08-610a618cd8b7" />

<img width="375" alt="image" src="https://github.com/user-attachments/assets/194d418e-34b5-4d4a-8161-1fcaac437b6b" />

<img width="224" alt="image" src="https://github.com/user-attachments/assets/9076f868-ffbe-45ac-9445-1f6ea47f637d" />

### Slack

Slack refers to the difference between the required time (the time a signal must arrive) and the actual time (the time a signal actually arrives). Essentially, slack measures whether the timing requirement of a signal is met or violated. It's used to assess whether a circuit operates within its specified timing constraints.

### Slew

Slew refers to the rate of change in the signal's voltage, i.e., how quickly the signal transitions between logic levels. Slew is typically measured as the rise time (the time it takes for a signal to go from low to high) or the fall time (the time it takes for the signal to go from high to low). In high-speed designs, controlling the slew rate is critical for reducing signal integrity issues.

### H Tree Algorithm

The H-tree algorithm is a method used to distribute the clock signal efficiently across the chip, typically in the context of clock tree synthesis (CTS) during ASIC or FPGA design. The H-tree is a hierarchical, balanced tree structure that helps to minimize clock skew (the variation in clock arrival times) and improve signal integrity.

The H-tree is a specific type of clock distribution network that gets its name because of its resemblance to the letter "H" when drawn. It provides a highly symmetric and balanced layout, which makes it particularly useful for global clock distribution, especially in designs that require precise timing and low skew.

<img width="599" alt="image" src="https://github.com/user-attachments/assets/8dfd04f1-2589-48a0-9c6e-56c96f96c47c" />

### Clock Tree Shielding

Clock Net Shielding is a technique used in digital circuit design to reduce electromagnetic interference (EMI) and crosstalk on the clock signal as it propagates through the chip. This is especially important in high-speed circuits where timing is critical, and signal integrity must be maintained to ensure reliable operation. Shielding the clock net helps protect the clock signal from noise generated by other signals on the chip and minimizes noise that might radiate from the clock itself.

<img width="597" alt="image" src="https://github.com/user-attachments/assets/da19215b-caff-4608-9c14-b4a313bfa023" />

<img width="581" alt="image" src="https://github.com/user-attachments/assets/b5d3fa2f-949b-44c2-a36d-d4827dab2f89" />

<img width="246" alt="image" src="https://github.com/user-attachments/assets/5acb9cc9-7614-44b3-927f-a4ef2cd2c2bd" />

<img width="590" alt="image" src="https://github.com/user-attachments/assets/500e9bf4-2214-4427-bd71-379a294ef994" />

### Hold Analysis

Hold Analysis is a critical part of Static Timing Analysis (STA) in digital circuit design. It is used to ensure that data signals are held stable long enough to be correctly sampled by the flip-flops or latches at the clock edge. Hold time violations can lead to incorrect data capture, causing timing errors and malfunctioning of the circuit.

<img width="551" alt="image" src="https://github.com/user-attachments/assets/6ab7dcff-d94f-4992-91a3-bdcc9a4b79ba" />

<img width="560" alt="image" src="https://github.com/user-attachments/assets/08d9d417-d0a1-4c0a-935c-cac422e4af6e" />

<img width="263" alt="image" src="https://github.com/user-attachments/assets/b5440aab-fe13-42ea-9912-aa9827b9d8f9" />

## DAY 5 FINAL STEPS FOR RTL2GDS USING TRITON ROUTE AND OPEN STA

### Maze Routing Algorithm

A maze routing algorithm is a classic method used in electronic design automation (EDA) for routing the connections between components on a chip, such as in ASICs, FPGAs, and PCB designs. The term "maze" refers to the grid-like layout of the design, where the routing algorithm must navigate from one point to another while avoiding obstacles, such as other routing traces or existing components.

In the context of routing, a maze is a network of grid cells (like squares in a maze), where the algorithm must find a path that connects the source (e.g., a pin or a component) to the destination (e.g., another pin or component), following the design constraints.

The maze routing algorithm is typically employed in global routing and detailed routing phases to find the most optimal path that adheres to design rules and constraints, such as width, spacing, and clearance.

<img width="331" alt="image" src="https://github.com/user-attachments/assets/8f3809ee-2845-4733-adc6-517690c2dd5c" />

<img width="331" alt="image" src="https://github.com/user-attachments/assets/6567e854-cc2f-4579-95eb-0bd4e08fc5c7" />

### DESIGN RULE CHECK DRC

Design Rule Check (DRC) is a crucial step in the digital and physical design process of integrated circuits (ICs). It involves verifying that the physical layout of a chip adheres to the manufacturing constraints and rules established by the foundry (fabrication process). DRC ensures that the layout can be fabricated correctly without errors that could lead to defects or failure in the final chip.

WIRE WIDTH
WIRE PITCH
WIRE SPACING

<img width="584" alt="image" src="https://github.com/user-attachments/assets/2de5e970-2960-4bbe-a910-a2182526cef9" />

<img width="338" alt="image" src="https://github.com/user-attachments/assets/0904092f-e168-4b9b-8d9f-45358f448aa6" />

### ROUTING

<img width="550" alt="image" src="https://github.com/user-attachments/assets/7fb7b25a-a9ee-4f05-bc86-d4a0997f6ef6" />

### TRITON ROUTE

<img width="491" alt="image" src="https://github.com/user-attachments/assets/c77e3e89-0e93-4336-8e60-24e544a64e7a" />

<img width="458" alt="image" src="https://github.com/user-attachments/assets/d4fd8b09-4cd2-4954-b784-9166ebf81025" />

<img width="452" alt="image" src="https://github.com/user-attachments/assets/382cd19b-6fde-4184-98d2-5b3cfaf5347f" />

<img width="455" alt="image" src="https://github.com/user-attachments/assets/8055a443-3adc-4805-a15b-e143d4bb9b01" />

<img width="547" alt="image" src="https://github.com/user-attachments/assets/45270e59-a82b-42d1-b863-d251eed05f7a" />

### Algorithm

<img width="389" alt="image" src="https://github.com/user-attachments/assets/3a12b360-e08c-49cf-9354-681fb300b5c1" />

<img width="491" alt="image" src="https://github.com/user-attachments/assets/94cb5e74-34ab-4735-b9e9-7f5ded73043a" />

# CREDITS

### Lecturers
### Some Images taken from Lectures
### Author
