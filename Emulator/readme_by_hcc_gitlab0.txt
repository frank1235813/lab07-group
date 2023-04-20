for lab7-2 testing:
  path: in lab4-group directory
  code: $ make
        $ ./obj/emulator ./lab07_example_code/program.asm

for HW7-2 testing:
  path: in lab4-group directory
    code: $ make
          $ ./obj/emulator ./lab07_example_code/Hw2_inst.asm
          $ diff -s ./lab07_example_code/inst.asm ./lab7_2_golden/Hw2_inst.asm
          $ diff -s ./lab07_example_code/m_code.hex ./lab7_2_golden/Hw2_m_code.hex	