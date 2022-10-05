# Subjects


- Arrays
- Sets
- Tuples
- Dictionaries
- Dictionary default values
- Creating empty collections
- Enumarations
- Enum associated values
- Enum raw values


1. Swift arrays start with 0 index.
2. We can initialize our array with [1, 2, 3] syntax.
3. We also can initialize our array with Array<Type>() syntax. This will be created empty collection. 
    <pre><code>
        [String: String]() // for dict
        [Int]() // for array
        Set<String>() // for set
    </code></pre>
      
1. We can use for reach any element we want to we have to use subscript syntax ([]).
2. Swift crashes if we use non-exist index of array.
3. If you use type annotations you can write like this : [String] or Array<String>.
4. Sets items are not ordered.
5. No item can appear twice in the set.
6. All items must be unique.
7. We can initialize set with array. (Set([1, 2, 3])
8. You can not add or remove items from tuple. They're fixed size.
9. You can't change a type of items in a tuple.
10. You can access items in a tuple using numerical positions or you can give them names
11. You can create a tuple with "( )"  delimiters. 
12. Numerical positions starts with zero.
13. Sets are extremely quickly.
14. Dictionaries have key-value match.
15. Swift dictionaries keys have to be conform to hashable protocol.
16. We can reach data in the dictionaries we have to use keys in the [].
17. Subscript operator return the optional type of the value type.
18. When using type annotations in dictionaries we have to use [String: Double] or Dictionary<String, Double>.
19. If we used to non-existing key swift will return to us "nil".
20. We can provide a default value if data is missing. The syntax is "dict["no-key", default = "unknown"]
21. Enumerations defines a related groups of values.
22. In programming "stringly typed" values not preferred. Instead of we must use enums. 
    <pre><code>
        let f1 = "failure"  
        enum Result {
            case failure
            case success
        }
        let f2 = Result.failure
    </code></pre>
        
    This makes sure we don't misspell the string.
    
23. We can pass argument to enum cases. That's called enum associated values.
        enum Activity {
            case bored
            case running(destination: String)
            case talking(topic: String)
            case singing(volume: Int)
        }
        
        let singing = Activity.singing(volume: 10)
24. We can use enum raw values if we write after enum names  this ": Int". Swift automatically counts from zero for our case.
    <pre><code>
        enum Planet: Int {
            case mercury
            case venus
            case earth
            case mars
        }
        
        let earth = Planet(rawValue: 2)
    </code></pre>
        
        
25. If we init some case to some integer value. Swift will automatically count rest of cases.
    

    





