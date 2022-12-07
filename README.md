# **Create a daily report that tracks the use of machines**

**Scenario:**

As an Python Developer, working in a medium-sized company, your manager wants to ***create a daily report*** that tracks the use of machines. Specifically, He wants to know ***which users are currently connected to which machines***, it's your job to create the report. 

In your company, there's a system that collects every event that happens on the machines on the network. Among the many events collected it records each time a user logs in or out of a computer.

**Problem Statement:** Create a daily report that tracks which users are currently connected to which machines

In our scenario, let's consider the ***system*** that tracks every event that happens on the machines on the network as a **class of Events** or an **Event class**. 

And each event - detailing the `machine`, the `user`, the `date`, and the event `type` - let's consider them as instances of the `Event` class.
