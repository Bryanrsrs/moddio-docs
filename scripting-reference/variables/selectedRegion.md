Use with a for loop like this for (let i = 0; i < (param.getEntitiesByCategory('region')).length; i++) {}
and get the selected region with this: param.getEntitiesByCategory('region')[i]

Example Bellow:

for (let i = 0; i < (param.getEntitiesByCategory('region')).length; i++) {
    if (param.name(param.getEntitiesByCategory('region')[i]) == 'banana') {
        ...
    }
}
