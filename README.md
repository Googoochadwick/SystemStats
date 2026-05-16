# System Stats Monitor — Release v0.1.0 Alpha
 
A lightweight Python-based **system monitoring and reporting utility** designed for real-time terminal visualization and automated performance report generation.

This release introduces:

* Live terminal monitoring
* System resource tracking
* PDF analytics reporting
* Cross-platform compatibility

---

# Release Highlights

## Real-Time Monitoring

Monitor system activity directly from the terminal with live updating graphs for:

* CPU Usage
* Memory Usage
* Network Sent
* Network Received


---

## PDF Report Generation

Generate detailed usage reports containing:

* System information
* Performance graphs
* Network statistics

Reports are automatically exported as:

```text
usage_report.pdf
```

---

# Features

* Live system statistics dashboard
* CPU and memory monitoring
* Network traffic tracking
* Automated PDF report generation
* Graph plotting using `matplotlib`
* Cross-platform terminal support
* Simple CLI-based interface

---


# Menu Options

## 1 — Live Stats

Displays a continuously updating terminal dashboard with:

* CPU usage graph
* Memory usage graph
* Network sent graph
* Network received graph

---

## 2 — PDF Report

Background monitoring for a specified duration.

Example:

```text
Enter duration in min:
```

After completion, the application generates:

```text
usage_report.pdf
```

---

# Generated Report Contents

The generated PDF includes:

1. System Information
2. CPU Usage Over Time
3. Memory Usage Over Time
4. Network Sent Over Time
5. Network Received Over Time

---

# Example System Information Output

```text
=== SYSTEM INFO ===
         System: Windows
         Release: 11
         Version: 10.0.22631
    Architecture: 64bit
       Processor: Intel64 Family
```

---


# Known Limitations

* No GPU monitoring in current release
* Network statistics are cumulative
* Terminal rendering quality depends on terminal compatibility

---

# Planned Features

Upcoming improvements may include:

* GPU monitoring
* Disk usage analytics
* CSV export support
* Alert system for high resource usage
* Multi-threaded monitoring
* Enhanced dashboard UI
* Historical session storage

---

# Release Information

**Version:** v0.1.0
**Status:** Alpha
**Platform Support:** Linux

---

