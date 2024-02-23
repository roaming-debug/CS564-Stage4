# Heap File Manager

This project outlines the construction of a Heap File Manager as part of the underlying infrastructure for a simplified relational database management system (DBMS), Minirel. It presents an opportunity to deepen one's understanding of relational database implementation and engage with crucial database concepts.

## Features

1. File Management and Scanning: Implemented key classes such as FileHdrPage, HeapFile, and HeapFileScan to support file creation, deletion, and efficient scanning of heap files.
2. Customizable Filtering: Built a scanning mechanism that leverages filtering predicates, enabling users to search for records within a heap file effectively.
3. Flexible Data Handling: Supported different data types including STRING, INTEGER, and FLOAT. Also ensured support for comparison operations in accordance with standard SQL protocols.
4. Record Insertion: Added an InsertFileScan Class, enabling record insertion into the file and returning the record identifier (RID).
5. Robust Error Handling: Included detailed error codes and handling procedures to ensure the robustness and reliability of the DBMS structure.
6. Multithreading and Concurrency: Allowed for multiple instances of a file to be opened and closed simultaneously, thereby increasing concurrency and overall DBMS efficiency.
