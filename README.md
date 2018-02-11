# Computer Design Experiments
After writing a simulator of an Unlimited Register Machine (Shepherdson,
Sturgis 1963) in Python, I thought it might be cool to realize a finite
version of the machine using logic gates. That's what I intend to share
here for now: a simulation of URM in Logisim.

I've tried two architectures: Harvard (separate ROM and RAM) and von Neumann (shared RAM). Pictures of the high-level design (the wires are hidden through ports) follow.

## Harvard Architecture

![Harvard Architecture](images/harvard_arch.png?raw=true "Harvard Architecture")

## Von Neumann Architecture

![Von Neumann Architecture](images/von_neumann_arch.png?raw=true "Von Neumann Architecture")


# Next steps
- share the components and their descriptions
- share the actual logisim files
- realize the machine in an FPGA
- realize the machine using 7400/4000-type logic gates

# Tools
- [Logisim](http://www.cburch.com/logisim)

# References
- Cutland, N.J. (1980) *Computability: An Introduction to Recursive
  Function Theory*.
- Shepherdson, J.C., Sturgis, H.E. (1963) Computability of Recursive Functions
