# Interprocess Communication

Interprocess communication (IPC) refers specifically to the mechanisms an operating system provides to allow the processes to manage shared data.It is a set of programming interface which allow a programmer to coordinate activities among various program processes which can run concurrently in an operating system. This allows a specific program to handle many user requests at the same time.

Since every single user request may result in multiple processes running in the operating system, the process may require to communicate with each other. Each IPC protocol approach has its own advantage and limitation, so it is not unusual for a single program to use all of the IPC methods.
Approaches for Inter-Process Communication:
Pipes:
Pipe is widely used for communication between two related processes. This is a half-duplex method, so the first process communicates with the second process. However, in order to achieve a full-duplex, another pipe is needed.

Message Passing:
It is a mechanism for a process to communicate and synchronize. Using message passing, the process communicates with each other without resorting to shared variables.

IPC mechanism provides two operations:

Send (message)- message size fixed or variable
Received (message)
Message Queues:
A message queue is a linked list of messages stored within the kernel. It is identified by a message queue identifier. This method offers communication between single or multiple processes with full-duplex capacity.

Direct Communication:
In this type of inter-process communication process, should name each other explicitly. In this method, a link is established between one pair of communicating processes, and between each pair, only one link exists.

Indirect Communication:
Indirect communication establishes like only when processes share a common mailbox each pair of processes sharing several communication links. A link can communicate with many processes. The link may be bi-directional or unidirectional.

Shared Memory:
Shared memory is a memory shared between two or more processes that are established using shared memory between all the processes. This type of memory requires to protected from each other by synchronizing access across all the processes.



<BadgeLink badgeText='Read' colorScheme="yellow" href='https://www.geeksforgeeks.org/inter-process-communication-ipc/'>Interprocess Communication</BadgeLink>
<BadgeLink badgeText='Watch' href='https://www.youtube.com/watch?v=dJuYKfR8vec'>Interprocess Communication - Neso Academy</BadgeLink>
