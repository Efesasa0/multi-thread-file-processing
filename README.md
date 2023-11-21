# Multi-Threaded File Reading and Processing

- **Summary**: This project, part of CMSPC 473 at Penn State University, was focused on developing a multi-threaded application in C for reading and processing data from files using FIFO (first in first out) linkled-list data structure and threading concepts like mutex locks. The project aimed to utilize threading for efficient data handling and processing.

- **Tools Used**: The application was developed in C, employing multi-threading concepts and utilizing custom data structures for handling buffered data.

## File Descriptions

1. **`buffer.c`** and **`buffer.h`**: Implementation and header files for the buffer management used in the application. These files contain the logic for storing and managing data read from the files.

2. **`driver.c`**: The main driver program that initializes the application, sets up threading, and handles the execution flow.

3. **`helper.c`** and **`helper.h`**: Helper functions used throughout the application, including utility functions for threading and data manipulation.

4. **`que.c`** and **`queue.h`**: These files implement a custom queue data structure, essential for managing data between multiple threads.

5. **`Makefile`**: Contains the set of directives used by the make build automation tool to build the application.

6. **`results.md`**: A Markdown file documenting the outcomes and results of the application, including performance metrics and observations.

- **Project Insights**: The project effectively demonstrates the use of multi-threading in C for reading and processing data from files. It highlights the importance of thread synchronization, efficient data structures, and the challenges of managing concurrent operations in a multi-threaded environment.

_This project showcases practical skills in system programming, emphasizing thread management, data structure implementation, and synchronization mechanisms in a multi-threaded application._
