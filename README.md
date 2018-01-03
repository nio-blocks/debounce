Debounce
========
The Debounce block will filter out signals for [interval] seconds after a signal flows through the block.

Properties
----------
- **group_by**: Signal attribute to define groupings of incoming signals.
- **interval**: Amount of time to wait before allowing another signal in a matching group.

Inputs
------
- **default**: Any list of signals.

Outputs
-------
- **default**: The first signal for each group, every interval.

Commands
--------
- **groups**: Display the existing groups.

Dependencies
------------
None

