# Investingating Dependency Injection

## Applying Inversion of Control and DI
Demo the basic usage of ``Depends``.
Include the function, callable class, nested structucre, pydantic model.

## Exploring ways of injecting dependencies

### Dependency injection on services
Use dependency to create the service and repository.
Decuss about the conflict between relying on ``Depends`` and domain isolation of domain driven design.

### Dependency injection on path operators & Dependency injection on routers
Discuss about the difference DI and middleware. Mostly about the invoked range.
We only have App level middleware while the DI can be router level.

### Dependency injection on main.py
Also compare the app level middleware vs app level DI.

## Organizing a project based on dependencies 
## Using third-party containers
## Scoping of instances