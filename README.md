GarbageCollector

compilations: 


gcc -g -c mld.c -o mld.o
gcc -g -c LinkedList/LinkedListApi.c -o LinkedList/LinkedListApi.o
gcc -g -c app.c -o app.o
gcc -g -o exe app.o LinkedList/LinkedListApi.o mld.o

Run the program as :
./exe

#   G a r b a g e - C o l l e c t o r  
 