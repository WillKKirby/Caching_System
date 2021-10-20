# Caching_System
This code is from my final year undergraduate project, which was implementing a caching system into a TTA processor. 
The processor in question was a project that was developed by different students every year and more was added on with each project.
The place I started from was that of the processor not having a caching system at all and was loading the instructions from a ROM within the fetch unit and data from a main memory.
My addition to the processor-implemented instruction and data caches.
The IMMU_unit worked as the instruction cache and fetched blocks instructions from the main memory on the system buses to the cache memory on the processor. 
The data_cache worked in the same way with the addition of having block write back and though methods to save data back to the memory. 
The methods I used allowed for temporary block storage and switching to make it more efficient, as well as also adding multiple block placement methods to also increase efficiency.
Due to other students working on this project, I have just added the files of intrest that I contributed to the project. So, the code wont work without the rest of the project. 
