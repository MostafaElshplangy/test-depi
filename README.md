# Server Performance Stats

A Bash script (`server-stats.sh`) that analyses basic server performance stats on any Linux server.

Project URL: https://roadmap.sh/projects/server-stats

## Features

- Total CPU usage
- Total memory usage (used vs free, with percentage)
- Total disk usage (used vs free, with percentage)
- Top 5 processes by CPU usage
- Top 5 processes by memory usage

## Requirements

- Linux
- Bash
- Standard tools: `top`, `free`, `df`, `ps`, `awk`

## Installation

```bash
git clone https://github.com/MostafaElshplangy/test-depi.git
cd test-depi
chmod +x server-stats.sh
```

## Usage

```bash
./server-stats.sh
```

## Example Output

```
===== CPU Usage =====
Total CPU Usage: 12.5%

===== Memory Usage =====
Used: 1.2GB (30%) | Free: 2.8GB (70%)

===== Disk Usage =====
Used: 20GB (40%) | Free: 30GB (60%)

===== Top 5 Processes by CPU =====
...

===== Top 5 Processes by Memory =====
...
```

## Author

Mostafa Elshplangy - [GitHub](https://github.com/MostafaElshplangy)