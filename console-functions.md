## JavaScript Console Methods

JavaScript provides a variety of built-in methods for the `console` object, enabling powerful and flexible logging and debugging capabilities. Here is a comprehensive list of these methods:

### Console Methods

1. **Outputting Messages**
   - `console.log()`: Outputs a message to the console.
   - `console.info()`: Outputs an informational message to the console.
   - `console.warn()`: Outputs a warning message to the console.
   - `console.error()`: Outputs an error message to the console.

2. **Formatting Output**
   - `console.dir()`: Displays an interactive list of the properties of the specified JavaScript object.
   - `console.dirxml()`: Displays an XML/HTML element representation of the specified object if possible.
   - `console.table()`: Displays tabular data as a table.

3. **Assertions**
   - `console.assert()`: Writes an error message to the console if the assertion is false.

4. **Counting**
   - `console.count()`: Logs the number of times that this particular call to `count()` has been called.
   - `console.countReset()`: Resets the count for a specific label.

5. **Grouping**
   - `console.group()`: Creates a new inline group, indenting all following output by an additional level.
   - `console.groupCollapsed()`: Creates a new inline group, but starts it in a collapsed state.
   - `console.groupEnd()`: Exits the current inline group.

6. **Timing**
   - `console.time()`: Starts a timer with a specific label.
   - `console.timeLog()`: Logs the current value of a timer that was previously started by calling `console.time()`.
   - `console.timeEnd()`: Stops a timer that was previously started by calling `console.time()` and logs the elapsed time.

7. **Tracing**
   - `console.trace()`: Outputs a stack trace to the console.

8. **Clearing**
   - `console.clear()`: Clears the console.

9. **Other Methods**
   - `console.memory`: Provides information about the memory usage of the JavaScript context (non-standard, Chrome only).
   - `console.profile()`: Starts recording a performance profile (non-standard, Chrome only).
   - `console.profileEnd()`: Stops recording a performance profile (non-standard, Chrome only).

These methods provide robust functionality for logging, grouping, counting, and timing operations in your JavaScript applications, making debugging and performance monitoring easier.
