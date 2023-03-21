# assembly-Hello-World-
assembly实现一个裸机（X86）Hello world!

学习操作系统 第一天


nasm -f bin assembly_hello_world.S -o setup.bin ；编译 
qemu-system-x86_64 setup.bin  ；使用qemu虚拟机运行
