# Computed Properties

# Resources

[uFrame 1.5 - Computed Properties on Youtube](https://www.youtube.com/watch?v=09gPdNbidDs)

# FAQ

#### How to bind Computed Property to a collection change?

there is something like Get<ComputedProperty>Dependants which returns Observables which are used to determinate when to update the computed property

> on your viewmodel, override Get[ComputedName]Dependents()
foreach guys in base.Get[ComputedName]Dependents
2:34
yeild return guys
then yield return viewModel.CollectionProperty 
- sinitreo