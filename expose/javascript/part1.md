1. values added: 20 
2. final result: 20
3. As var ignores code blocks, they become either function-scoped or global-scoped. And they have hoisting behaivor, meaning they are moved to the top of their scope. These two unusual behaivors can be confusing and and hard to keep track of, for example, causing naming conflicts.  
4. values added: 20
5. "result is not defined" error since 'let' has limited scope and since result was declared inside the if-statement, it cannot be accessed outside of it. 
6. TypeError: Assignment to constant variable. Since result was declared as a const, it cannot be reassigned and therefore the code errors on line 7. 
7. TypeError: Assignment to constant variable. Since result was declared as a const, it cannot be reassigned and therefore the code errors on line 7.
