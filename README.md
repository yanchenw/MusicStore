# Docker Perf Investigation

Compare the performance of local debugging with Docker debugging scenario.

Steps:
1. Clone this repo
2. Open the repo root with VS Code
3. Restore the packages
4. F5
5. Find out the total time spend on the build t1 from OUTPUT window
6. When page stop rendering, go to DEBUG OUTPUT window and find out the last message time tag which is the debug time t2
7. Adds t1 and t2 will be the total E2E time