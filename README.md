Debounce
========

After a signal flows through the block, filter out following signals for x seconds.

Properties
----------
-   **interval**: Amount of time to wait before allowing another signal in a matching group.
-   **group_by**: The value by which signals are grouped.

Dependencies
------------
None

Commands
--------
None

Input
-----
Any list of signals.

Output
------
The first signal for each group in **group_by**, every **interval**.
