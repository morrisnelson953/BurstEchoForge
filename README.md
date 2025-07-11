# BurstEchoForge

BurstEchoForge simulates burst traffic and high concurrency patterns to test the scalability and resilience of APIs under sudden load.

## Features
- Threaded HTTP burst engine.
- Customizable concurrency, rate, and duration.
- Response time and error tracking.
- Ideal for pre-launch load testing.

## Usage
```bash
git clone https://github.com/your-org/BurstEchoForge.git
cd BurstEchoForge
python burstecho/attack_runner.py --url https://api.example.com/ping --concurrency 50 --duration 10
