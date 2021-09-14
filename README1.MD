Assembler base :

    - mov = copy of a content
    ex : mov AX, 5 
    AX will take the value of 5

    - cmp = compare 
    cmp AH, BH
    AH and BH will be compared

    - call = procedure call (function)
    call sub_132
    call function sub_132

    - jmp = jump from one instruction to another (without conditions)
    jmp loc_123
    jump to loc_123

    - je = jump if equal, jumps to an instruction if the comparison is equal
    - jne = jump if not equal, jumps to a statement if the comparison is not equal

    - add = add a value
    add AX, 5 (5 and added to AX)

    - sub = subtract a value
    sub AX, 5 (5 will be subtracted from AX)

    - inc = add 1 to register
    - dec = remove 1 from the register

    - ret = call the last instruction of a procedure

    - nop = does nothing, useful to replace some conditions that bother us

    - retn = return (end of function)
    - Sleep = pause the program
    - SUB_ = Subprogram

    - Stack a regsiter on top (variable): push
    - Remove a register from the top (variable): pop

    - thread = 2nd process executed in parallel

Tips for reverse engineering:
- Do not understand everything but look at the functions called with call.
- Look at the name of the functions + search on internet
- In assembler, "21h" => 21 in hexa (do not take the h when converting)

Important : 
- Before executing a function, all the parameters of the function are stored in the execution stack.

Translated with www.DeepL.com/Translator (free version)