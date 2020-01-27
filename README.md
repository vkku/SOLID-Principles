# SOLID-Principles
Notes about what I observe and reflect
* Self Explanatory Code : No Comments
* Pull, Clean, Push
* Command / Query Separation : Query module should not effect state of system
* Code Smells (DRY, Long Methods, Big Class, Feature Envy, Useless Comment, Poor naming, Inappropriate Intimacy, Shotgun Surgery, Switchm God class, Primitive obsession, Refused Bequest)
* Code Smells Corrections -> Manage Dependencies, Separate Concerns, Apply SOLID)
//* Liskov Substitution Principle -> Program, Type, Subtype(Substituable to type)
1. Inheritance != IS A
* Open Closed Principle -> open for change, closed for modification, Add new code for new features don't change old (Interfaces can be used). Switch -> OC Principle breached. Very high level truth to low level. Done in reaction to change(Putting Hooks)
* DIP -> Depend on abstract methods, low level to depend on high level policy(Plugins)
* Abstract Classes / Methods, Interfaces for inverting dependencies only
