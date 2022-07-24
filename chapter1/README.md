Three concerns that are important in most software systems:
1. Reliability
    - > The system should continue to work correctly (performing the correct function at the desired
level of performance) even in the face of adversity (hardware or software faults, and even human error). Martin Kleppmann

2. Scalability
    - > As the system grows (in data volume, traffic volume, or complexity), there should be reasonable ways of dealing with that growth. Martin Kleppmann
3. Maintainability
    - > Over time, many different people will work on the system (engineering and operations, both maintaining current behavior and adapting the system to new use cases), and they should all be able to work on it productively. Martin Kleppmann

## Reliability
typical expectations include:
- The application performs the function that the user expected.
- It can tolerate the user making mistakes or using the software in unexpected ways.
- Its performance is good enough for the required use case, under the expected load and data volume.
- The system prevents any unauthorized access and abuse.

## Scalability
Some systems are elastic, meaning that they can automatically add computing resources when they detect a load increase, whereas other systems are scaled manually (a human analyzes the capacity and decides to add more machines to the system).

## Maintainability
Three design principles for software systems:
1. Operability
    -  Make it easy for operations teams to keep the system running smoothly.
        - Monitoring the health of the system and quickly restoring service if it goes into a bad state
        - Tracking down the cause of problems, such as system failures or degraded performance
        - Keeping software and platforms up to date, including security patches
        - Keeping tabs on how different systems affect each other, so that a problematic change can be avoided before it causes damage
        - Anticipating future problems and solving them before they occur (e.g., capacity planning)
        - Establishing good practices and tools for deployment, configuration management, and more
        - Performing complex maintenance tasks, such as moving an application from one platform to another
        - Maintaining the security of the system as configuration changes are made
        - Defining processes that make operations predictable and help keep the production environment stable
        - Preserving the organization’s knowledge about the system, even as individual people come and go
2. Simplicity
    - Make it easy for new engineers to understand the system, by removing as much complexity as possible from the system. (Note this is not the same as simplicity of the user interface.)
3. Evolvability
    - Make it easy for engineers to make changes to the system in the future, adapting it for unanticipated use cases as requirements change. Also known as extensibility, modifiability, or plasticity.