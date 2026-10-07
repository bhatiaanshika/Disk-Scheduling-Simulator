# Disk Scheduling Simulator

A web-based simulator for disk scheduling algorithms: **FCFS, SSTF, SCAN, C-SCAN and LOOK**.

## Features
- Enter your own request queue, head position, disk size and direction
- Head movement graph for the selected algorithm
- Step-by-step trace with total and average head movement
- Comparison table of all five algorithms, best one highlighted

## Run locally
Just open `index.html` in any browser. No installation needed.

## Live demo
https://YOUR-USERNAME.github.io/disk-scheduling-simulator/

## Algorithms
| Algorithm | Idea |
|---|---|
| FCFS | Serve requests in arrival order |
| SSTF | Always serve the nearest request |
| SCAN | Move to the disk end, then reverse |
| C-SCAN | Move to the end, jump to the other end, continue same direction |
| LOOK | Like SCAN but reverse at the last request |

Built with HTML, CSS and JavaScript.
