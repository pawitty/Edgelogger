# EdgePulse: ESP32 Edge Logger

Overview:
EdgePulse logs high-resolution timestamps of rising and falling edges from an RC differentiator circuit using ESP32. Includes software debounce to prevent false triggers.

Features:
- Detects edges on GPIO with micro seconds timestamp resolution
- Software debounce configurable (currently 500 µs)
- ISR-driven, non-blocking design
- Logs time to Serial Monitor

Hardware Setup:
- ESP32
- RC differentiator circuit connected to GPIO 4

Usage:
1. Connect RC output to GPIO 4
2. Upload the sketch
3. Open Serial Monitor at 115200 baud
4. Observe timestamps for each edge
