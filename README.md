This repository demonstrates a common, yet subtle, bug in COBOL programs: numeric overflow.  The `bug.cob` file contains code that attempts to increment a numeric field beyond its defined limit.  The `bugSolution.cob` file provides a corrected version that handles potential overflow conditions gracefully.