# Debugging Stored Procedures in SQL

Let's go step by step for a better understanding of the debugging process.

1) Select Debug-> Start or Alt+F5 to start the debugging process. *Note:* After we start debugging a yellow cursor at the start of the query will be displayed.
2) Stepping through the script is the next action, it can be done in 3 ways: <br>

   <sup> a) Step over(F10): It moves to the next line of the script<br>
   b) Step into(F11): This command allows you to break into the stored procedure from the script that calls the stored procedure.<br>
   c) Step out(Shift + F11): It's vise versa of step into. If you are inside a stored procedure and you want to go back to the script that calls the stored procedure this command can be used.</sup>
3) We can track the values that are passed in the script via the *Local window*.
4) We can track the values using *watch window* also but the only difference is we can add/remove variables from the watch window when we are working with a large number of variables.
5) Pressing F9 will add a breakpoint, this breakpoint specifies where the debugger wants to stop executing the code and it also allows skipping the unnecessary lines of code.
   
