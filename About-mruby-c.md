# About mruby/c

mruby was developed to run Ruby programs in a small memory environment.
mruby compiler converts a Ruby program into binary data called "bytecode", and mruby VM(virtual machine) executes this bytecode.
In general, on the execution time, the VM saves memory compared to interpreter-based execution.

mruby/c is another implementation of mruby VM that requires less memory than conventional mruby.
