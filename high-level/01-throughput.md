✅ Throughput

What is it?
→ Number of requests a system can handle per second.

Example:
→ A login system handling 1000 requests/sec = throughput of 1000.

When is it low?
→ When system is slow due to:
   1. High CPU usage
   2. Memory overload
   3. Slow database or file access
   4. Network delays

When is it zero?
1. Server is down
2. App crashes
3. Requests don't reach the app

How to improve?
1. Add more servers (scale out)
2. Use caching (e.g., Redis)
3. Run background jobs
4. Optimize code and database
