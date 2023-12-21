Subflow that will take two numbers and output each number in sequence between them using the requested step count over the number of seconds.

For example:

    {
        start: 0,
        end: 20,
        step: 2,
        duration: 5
    }

Will output separate payload messages of:

    0, 2, 4, 6, 8, ..., 16, 18, 20

and will take 5 seconds to do it.

Useful for a various options, including slowly turning a light on that does not support a builtin interval option
