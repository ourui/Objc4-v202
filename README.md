# Objc4-v202

Objc runtime version202 that codes from apple open source

Modify for purpurs that can compile through. It's useful to learn objective-c runtime. Since it's a very 

earily version, source files is much less than the lastest one, it's earsier to read and understand runtime.

Modify:

1: 32-Bit architecture only, and remove some .c .s file from target that will lead to complie error;

2: some extern function declaration that confict. 

3: make __attribute__((objc_root_class)) for Object that make "no base class" error

4: make include headers from '<>' to "" avoiding include headers for system header path, and include headers
   from project it's self; 
