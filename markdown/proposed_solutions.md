# Proposed Solutions

In 1997, the British Standards Institute defined the "Year 2000 Conformity Requirements". These requirements consisted of four rules:
- No valid date will cause any interruption in operations.
- Calculation of durations between, or the sequence of, pairs of dates will be correct whether any dates are in different centuries.
- In all interfaces and in all storage, the century must be unambiguous, either specified or calculable by algorithm.
- Year 2000 must be recognized as a leap year.

These rules gave developers an idea of how to fix their legacy code. The first rule ensured that there would be no errors due to the truncation of years. The second rule ensured that date ranges, such as the age calculation in the previous slide, would function correctly whether or not the dates fell in different centuries. The third rule basically removed the truncation of dates from software systems. Finally, the last rule ensured that the year 2000 would be correctly identified as a leap year, which was previously wrongly identified.

