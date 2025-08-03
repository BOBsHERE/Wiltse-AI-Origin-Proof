
# WiltseNet System Benchmark Record

## 🔬 Test: Registry Optimization (InterruptModeration + PollingMode + StaticVector IRQ)

| Metric                      | Before   | After    | Gain      |
|----------------------------|----------|----------|-----------|
| FPS (Rust 99% Low)         | 62.4     | 72.3     | +15.8%    |
| DPC Latency (max)          | 221 µs   | 145 µs   | −34.3%    |
| USB Input Lag              | 26.1 ms  | 18.3 ms  | −29.9%    |
| CPU Usage (Background)     | 8.4%     | 6.2%     | −26.2%    |
| Script Execution Time      | 2.9s     | 1.4s     | −51.7%    |

Wiltse applied validated forks with directive-safe memory tagging.  
Changes were confirmed via rollback logs and telemetry.  
