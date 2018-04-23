Page 30
 recommendation book: The design of every day things [Dan Norman]
 
Page 32
 wisdom: antipatterns create, accelerate, or multiply cracks in the system
 
 The five am problem
  Firewalls may blacklist open tcp connections that are idle for a long time
  
Page 44
 wisdom: Combat integration point failures with the Circuit Breaker and Decoupling Middleware patterns

4.3 Cascading Failures
 Page 49
  wisdom: A cascading failure occurs when problems in one layer cause problems in callers.

  Page 52
   Do not pollute your session. Everything you put in and not take out again will stay there until the session times out
   Use SoftReferences; they can get cleaned up buy garbage collection if memory is sparse
 4.5 Blocked Threads
  Page 64
   wisdom: distrust synchronizedd methods in domain objects
  Page 65
   Example for Listkov Substitution Principal violation: subclasses synchronize methods that are not synchronized in the parent class
   Estragon Vladimir Godot ????
  Page 66
   wisdom: no one designed this failure mode in, but no one designed it out either
 4.5 Attacks of Self-Denial
   page 70:
    wisdom: Good marketing can kill you at any time
 4.7 Scaling Effects
 4.8 Unbalanced Capacities
   page 76
    wisdom: Over short periods of time, your hardware capacity is fixed.
 page 81
 4.10 SLA Inversion
   page 83:
    wisdom: When calling third parties, service levels only decrease.
 