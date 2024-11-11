function Employee(name,age,salary){
    let employee = object.create(Employee.prototype);
    employee.name=name;
    employee.age=age;
    employee.salary=salary;
    return employee;
}
Employee.prototype.displayName =  function(){
    return this.name;
};
Employee.prototype.increaseAge = function(){
    return this.age;
};
Employee.prototype.decreaseAge = function(){
    return--this.age;
};
function Manager(name,age,salary,department){
    let manager =Employee(name,age,salary);
    object.setPrototypeof(manager,Manager.prototype);
    manager.department = department;
    return manager;
}
Manager.prototype.displayDepartment = function(){
    return this.department;
}
Manager.prototype.increaseSalary=function(employee,amount){
    employee.salary+=amount;
    return employee.salary;
}
Manager.prototype.decreaseSalary = function(employee,amount){
    employee.salary-= amount;
    return employee.salary;
};
object.setPrototypeOf(Manager.prototype,Employee.prototype);
