# IdleTimeSwing
URCap sample that mainly demonstrates the principle of ProgramNodeVisitor and WaitNodeConfig

Idle Time Swing demonstrates how to work with the ProgramNodeVisitor to traverse all program nodes in a sub-tree. In this example, all Wait nodes will be visited. If a Wait node is configured to wait for an amount of time, that amount of idle time (in seconds) will accumulate in the selected variable.

Information:
* Available from:
  * URCap API version 1.3.0.
  * PolyScope version 3.6.0/5.0.4.

Main API interfaces: ProgramNodeVisitor, WaitNodeConfig
