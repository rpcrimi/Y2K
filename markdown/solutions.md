# Solutions

![](/images/y2k_solution.jpg?raw=true "New Story")

While the BSI's "Year 2000 Conformity Requirements" layed out a clear idea of what software changes needed to be made in order to safely transition into the new millennium, it did not define how this should be done. In the end, it was up to software developers to choose their method in order to conform to these standards. There were three main approaches developers took in order to adhere to these standards.

## Date Expansion

The "purest" solution to the Y2K problem was to implement Date Expansion. In this method, all two-digit dates would be converted to four digits. This meant that all files, programs, and databases must be updated to this new format. Also, in order to retain the software's functionality, massive test suites needed to be implemented. Because of this, Date Expansion was by far the most costly and time consuming approach. However, once converted to the new four-digit format, these software systems needed little to no maintenance to keep them running.

## Date Re-Partitioning

Most legacy databases were built on the assumption that storage was very expensive. Due to this design decision, most up-and-running databases could not change their size in an economical fashion. These style databases and software systems needed to implement Date Re-Partitioning in order to adhere to adhere to the BSI's conformity requirements. Date Re-Partitioning is the method of maintaining the six-digit date format while being able to differentiate dates in two different centuries. To achieve this, the date standard six-digit date format (MM/DD/YY) was converted to DDD/YYY, where the day fields were numbers between 1-365 and the year field added a leading 1 or 0 to identify the century. For example, the date December 31, 2001 would be changed from 12/31/01 to 365/101. On the other hand, the date December 31, 1901 would be formatted as 365/001. This change allowed these legacy systems to continue to use the same amount of space while adhering to the new guidelines.

## Windowing

The simplest and least costly approach to solve the Y2K problem was Windowing. Windowing is the process of retaining two-digit years and only determining the century value when needed. For example, when a date comparison or range must be calculated, the system would need to determine the centuries of the dates. This technique required small patches of code to be implemented in these software systems, which in turn was simpler to implement and test. While Windowing was the simplest to implement, it was not a permanent solution. However, most developers accepted Windowing as they knew their legacy software would eventually be replaced with newer technology.

Up Next: [Looking Forward](https://github.com/rpcrimi/Y2K/blob/master/markdown/looking_forward.md)
