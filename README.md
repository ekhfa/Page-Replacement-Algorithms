# A project for operating system course (CSE323)
Page replacement algorithms specify the memory pages to page out, also called swap out, or write to disk, in a computer operating system that uses paging for virtual memory management, when a memory page has to be reserved. Page substitution occurs where a requested page is not in memory (page fault) because it is not possible to use a free page to meet the allocation, either because there is none, or because the number of free pages is smaller than a certain threshold. 
Different types of algorithm is needed to decide which page needs to be replaced when new page will be required to execute. There comes forward the idea of ‘page fault’. In our project we will implement different page replacement algorithms like First in First out (FIFO), Optimal Page Replacement, and Least Recently Used etc. and after calculating the page fault our program will decide, which algorithm is best for a certain input.
