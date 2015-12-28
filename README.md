# Orions_Gaze
Instrumentation lib and monitor

The goal of this project is to generate a instrumentation framework that can be included within any project and will communicate with a secondary process running on the computer to view and store the data.

The goals of the project are:
- Memory management
- Memory leaks
- Thread safe
- Function monitoring
	- Number of times called
	- Who called the function
	- Time spent in the function
	- Parameters
	- Return value
- Any extra debug information desired (printf)
- Save recorded data to file for later viewing

Bonus tasks:
- Add filtering capabilities to the viewer
	- Filter by thread
	- Filter by function name
	- Filter by class
- Add memory viewer
