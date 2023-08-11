Abstract—The significant subject of research with respect to
task scheduling has grown in importance with the widespread
use of real-time operating systems. Major domain of the proposed
work is Real Time Operating Systems and meeting time
constraints using the real core of operating systems, the task
scheduler. The choice of task scheduling algorithm depends on
the ability to fulfill task time restrictions demanded by end
user requirements. The characteristics and limitations of realtime
operating systems are the primary subject of our work.
Using the scheduling mechanism, the real-time operating system
assists real-time applications in achieving their deadline. Any
real-time system’s scheduling approach is its heart; it determines
the sequence in which activities should be completed so that any
form of task overlap may be avoided. The main goal of the
work is to develop a framework that would address the existing
problems in constrained-deadline scenarios. Existing algorithms
like Rate Monotonic Scheduling (RMS), Earliest Deadline First
(EDF), Time Slice (TS), Least Slack Time (LST) have common
shortcomings like not working as desired in an overloading
situation. EDF scheduler, with the problem of Domino effect,
provides a degraded performance in overloaded situations. With
the literature proof, it is analyzed that the deadline missing
in the events happen because of their utilization of bounding
strategy. One more shortcoming with the existing frameworks is
that running tasks are preempted by higher priority new tasks,
the algorithm does not work as desired because running tasks
miss the deadline. The proposed work aims to minimize the
effects of the drawbacks in the existing algorithms by developing
a framework that would permit the global task scheduler to
perform task migration mechanism utilizing queuing theory in
between processors in the system, and the same is proposed
to be compared with various metrics for analysis like Success
Ratio (SR), Scheduling Latency, Average CPU Utilization (ECU),
Failure Ratio (FR), and Maximum Tardiness parameters.
Index Terms—Task Schedulers, Rate Monotonic Scheduling
(RMS), Earliest Deadline First (EDF), Least Slack Time (LST),
Controlled preemptive EDF, Multilevel Feedback Queue, Real
Time OS.
