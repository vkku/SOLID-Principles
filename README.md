# SOLID-Principles
![image](https://user-images.githubusercontent.com/12431831/75377267-6f8e8900-58f7-11ea-967e-6728bb4fc573.png)

Notes about what I observe and reflect
* Self Explanatory Code : No Comments
* Pull, Clean, Push
* Command / Query Separation : Query module should not effect state of system
* Code Smells (DRY, Long Methods, Big Class, Feature Envy, Useless Comment, Poor naming, Inappropriate Intimacy, Shotgun Surgery, Switchm God class, Primitive obsession, Refused Bequest)
* Code Smells Corrections -> Manage Dependencies, Separate Concerns, Apply SOLID)
* Liskov Substitution Principle -> Program, Type, Subtype(Substitutable to type)
1. Inheritance != IS A
2. Can be thought as HAS-A
3. (General) Use compositions over inheritance whenever fitting enough
* Open Closed Principle -> open for change, closed for modification, Add new code for new features don't change old (Interfaces can be used). Switch -> OC Principle breached. Very high level truth to low level. Done in reaction to change(Putting Hooks)
* DIP -> Depend on abstract methods, low level to depend on high level policy(Plugins)
* Abstract Classes / Methods, Interfaces for inverting dependencies only
* Aspect Oriented Programming -> Single Responsibility Principle
