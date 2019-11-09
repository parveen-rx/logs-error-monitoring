# logs-error-monitoring
Logs error watcher which helps in finding the production error in minimum times

# Why this repo
Find the problem root cause before your customers notice

# Benefits
  Application background processing might fails and can cause a good impact on the application usgages.With this error monitoring tool, you’ll have the possibility to fix the bug before your customers notice it.

  If you have a really big application, having multiple integration points or running on multiple different microservices, then finding and looking the error manually is not a cool idea. You must have some tool that help you in finding the RCA.

# Reduce the time to find the RCA and fix:
    Without a monitoring tool, when a bug is reported, your team would probably start looking through logs manually. This significantly extends the fix time. 
    Now, imagine that your team gets a notification right away when the error appears — you can now skip that time-consuming part. How cool is that !!

# Architecture
    The building blocks includes elastic search, kibana, filebeats, logstash, watcher and node module as a complete bundle to setup the error monitoring tool.

# Author
    Parveen Soni (parveen-rx)