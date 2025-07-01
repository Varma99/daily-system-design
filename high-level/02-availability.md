✅ Availability

What is it?
→ Percentage of time the system is up and responding correctly.

Example:
→ System is up 23.5 hours a day → availability ≈ 98%.

When is it low?
→ Frequent errors (5xx)
→ App keeps crashing
→ Dependency (like DB or auth) is down

When is it zero?
→ Entire system is down
→ All responses fail

How to improve?
→ Use multiple servers
→ Restart failed services automatically
→ Use health checks
→ Handle failures gracefully
