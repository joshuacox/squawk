# Squawk

This function simplifies error reporting and verbosity
and it always prints its message along with anything in $error_report_log
call it by preceding your message with a verbosity level


e.g. `squawk 3 "This is a squawk"`

if the current verbosity level is greater than or equal to
the number given then this function will echo out your message
and pad it with # to let you now how verbose that message was
