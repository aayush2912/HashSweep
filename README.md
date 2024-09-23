# HashSweep

The majority of parallel algorithms use the Parallel Random-Access Machine, or PRAM, concept. It facilitates the writing of a precursor parallel algorithm free from architecture restrictions and grants parallel-algorithm authors the luxury of treating processing capacity as limitless. It disregards how intricate inter-process communication is. A Cuckoo hash is constructed in shared memory, a tiny but incredibly quick memory, by the parallel building process. First, a first-level hash is used to randomly distribute the keys into buckets of equal size. A construction failure is triggered by an overflowing bucket. This restricts the maximum load factor that can be used; larger load factors result in an excessively high failure rate during this crucial distribution phase. Subsequently, Cuckoo hashing is
paralleled with independent bucket hashing

Aim: Take the path of the input folder from which we need to remove duplicates. Once the program runs successfully, the output will be the same input folder without duplicates.

Approach:
1. Calculate the hash value for all files
2. Identify the unique files using the hash values.
3. Delete the duplicate files.

Conclusion:
1. Parallel hashing can significantly reduce the time required to hash large amounts of data by processing multiple chunks simultaneously. This is particularly advantageous when dealing with large datasets or when performing hash computations in real-time applications.
2. Utilizing multiple processing units, or cores, allows for better resource utilization.
3. As the volume of data increases, parallel hashing provides a scalable solution by distributing the workload across multiple processors.
4. Parallel hashing can be implemented with load-balancing mechanisms to ensure that the workload is evenly distributed among processing units.


Skills: Parallel Processing · Hashing · Python (Programming Language) · File Management · Cuckoo Hashing
