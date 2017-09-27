Name: `Jake Halloran` Class start time: `M/W 3-4:15`

1. Does every software system have an architecture?  Why or why not?

```
Yes every sysyem has an architecture. Even if not formally defined, the system still exists and has specific
structures and external interactions that represent its architecture.
```

2. You are designing a climate control system, which accepts inputs from a variety of distributed sensors (e.g., thermometers, smoke sensors, barometers, etc.), and normalizes environmental conditions based on this input.  For example, if average temperature is below a threshold, the heater will be turned on.  Occasional input needs to be responded to immediately; for example, a smoke sensor detecting particulate matter may set off a fire alarm immediately.

Of the architectural styles listed in Tsui _et al_, which one would be best for this kind of system?  Why?

```
The best architectual style for this system would be event-driven. This is because the system
largely exists to respond to external stimulus rather than generate the stimulus itself. Other
implementations all less meet the distributed, immediate response needs of this system.
```

3. You are designing a system to store classes so that students can view information on the classes available for the next semester.  There is little to no business logic associated with this system.  The focus is just on storing and viewing (and for administrators, occasionally adding) data to the system.

Of the architectural styles listed in Tsui _et al_, which one would be best for this kind of system?  Why?

```
The best architectual style for this system is Model View Controller. As there is little logic
that needs performed compared to the bulk of the work being just viewing (and adding) data
the best possible architecture is one that is similarly focused on data display.

```

4. After reviewing your system design, your co-worker notes that you have two classes with content coupling.  Why is this problematic?

```
This is problemeatic as content coupling means that your two classes aer codependant on each
others data. This means that not only do both classes rely on the functionality of the other
at their core level, but also that any change to one therefore requires both changes to the
other and likely bug fixing as well.
```

5. You have written a class whose methods are all related in terms of some control sequence.  What level of cohesion is this?

```
This is procedural cohesion.

```
