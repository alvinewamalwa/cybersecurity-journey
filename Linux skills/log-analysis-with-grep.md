# Log Analysis Using grep for Security Monitoring

## Task
Identify suspicious authentication activity from system logs.

## Commands Used
- grep
- cat
- less

## Execution
cat auth.log | grep "failed"
cat auth.log | grep "invalid user"
cat auth.log | grep "authentication failure"

## Result
Multiple failed login attempts and invalid user entries were detected.

## Security Insight
Repeated failed authentication attempts may indicate brute-force attacks or unauthorized access attempts. Log filtering is essential in SOC monitoring.
