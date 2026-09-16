# Metric Definitions

## Weekly New-Patient Requests
The number of patients requesting a new-patient appointment during a modeled week.

## New-Patient Capacity
The number of appointment slots specifically available for new patients each week.

## Established-Patient Capacity
Total weekly appointment supply remaining after dedicated new-patient slots are allocated.

## New-Patient Capacity Gap
New-patient capacity minus weekly new-patient demand. A negative value means demand exceeds available new-patient appointment supply.

## Starting New-Patient Backlog
Patients already waiting for a new-patient appointment at the beginning of the model period.

## Projected Backlog
The modeled backlog after 12 weeks based on the weekly difference between new-patient capacity and demand.

## Projected Access Days
Projected backlog divided by average daily new-patient capacity. This approximates how many business days of demand are waiting in the queue.

## Template Utilization
The proportion of available appointment capacity expected to be filled or otherwise utilized.

## No-Show Rate
The percentage of scheduled appointments expected not to result in a completed visit.

## Call Capacity
Scheduling FTE multiplied by the modeled number of calls one FTE can handle per week.

## Call Capacity Gap
Call-handling capacity minus weekly call demand. A negative value indicates administrative access demand exceeds modeled staffing capacity.

## Why the Metrics Are Evaluated Together
Provider capacity, appointment allocation, backlog, and scheduling workload are interdependent. Increasing total provider slots without allocating enough new-patient capacity may not improve new-patient access. Likewise, adding appointment supply without adequate administrative support can leave patients unable to reach or navigate the scheduling system efficiently.
