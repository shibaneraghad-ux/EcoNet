 # EcoNet

A simple Python script that reads network device data from a JSON file, finds idle devices, and calculates their daily and total wasted costs.

What it does:
- Parses device status and power/cost data from JSON.
- Filters out active devices to focus only on idle ones.
- Calculates exact daily and total financial waste using Python's `decimal` module to avoid floating-point error
Built with:
- Python 3 (OOP & TDD)
- JSON
- `decimal` module

Usage:
```bash
git clone https://github.com
cd EcoNet
python main.py
```

Sample Output:
```text
Idle Devices Found: 2
- Switch-01: \$12.50/day
- Router-02: \$18.75/day

Total Daily Waste: \$31.25
```
