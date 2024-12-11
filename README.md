# Java ArrayIndexOutOfBoundsException Bug

This repository demonstrates a common Java bug: an `ArrayIndexOutOfBoundsException` caused by an incorrect loop condition.

The `BuggyLoop.java` file contains the erroneous code.  The `FixedLoop.java` file provides the corrected version.

The bug is triggered by accessing an array element outside of the valid index range (0 to array.length -1).

This is a simple yet critical bug because it can lead to unexpected program crashes and data corruption.  Understanding how to correctly iterate over arrays is essential for writing robust and reliable Java code.