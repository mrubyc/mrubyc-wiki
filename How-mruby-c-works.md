# How mruby/c works

mruby compiler(command `mrbc`) converts a Ruby program into mruby bytecode, which is called `mrb file` because its file extension is `.mrb` by default.

mruby bytecode contains the following descriptions:

- header, which shows bytecode version
- ireps, which is series of instructions generated from mruby source code
- pools, which is a set of literals
- and some debug information

(fig)

## header

## irep

## pool
