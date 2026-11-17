# markdown-practice
## A topic about my favorite game:
### osu lazer
**is a rhythm game**, *also an open-source built on the C#*
***Core Components***
- Multi-threaded input polling for sub-millisecond latency.
- Standardized scoring algorithms normalizing mod multipliers.
- Built-in replay telemetry for frame-by-frame error analysis.
***Execution Pipeline***
1. Poll raw cursor coordinates via RawInput.
2. Render beatmap audio-visual cues at uncapped frame rates.
3. Evaluate hit accuracy against strict timing windows.
[osu!'s youtube channle](https://www.youtube.com/@osugame/search?query=tutorial)

| Statistic| Number of account|
| :--- | :--- | :--- | :--- |
| **Total Accounts Created** | ~ 30+ million accounts |
| **Active Accounts (Monthly)** | ~ 1.5 - 2 million active |
| **Concurrent Online Players** | Usually peaks at ~25,000 - 45,000+ users |

```# List of click time offsets in milliseconds (ms)
offsets = [15, 65, 110, 180]
for ms in offsets:
    if ms <= 50:
        print(f"Offset {ms}ms -> 300 (Perfect)")
    elif ms <= 100:
        print(f"Offset {ms}ms -> 100")
    elif ms <= 150:
        print(f"Offset {ms}ms -> 50")
    else:
        print(f"Offset {ms}ms -> Miss")
