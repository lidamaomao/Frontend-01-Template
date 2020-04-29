# 每周总结可以写在这里

## js中特殊的对象

- Function Object

  - [[call]] 
  - [[Construct]] 

- Array Object

  - [[DefineOwnProperty]]

    - Property == length

      newLength > length 多余内容使用空内容填充

      newLength < length 多余内容被舍弃

- String Object

- Arguments Object

  [[callee]] 

- Object

  [[Get]] 

  [[Set]] 

  [[GetPrototypeOf]] 

  [[SetPrototypeOf]] 

  [[GetOwnProperty]] 

  [[HasProperty]] 

  [[IsExtensible]] 

  [[PreventExtensions]] 

  [[DefineOwnProperty]] 

  [[Delete]] 

  [[OwnPropertyKeys]]

  [[Call]] 

- Module Namespece

  [[Module]] 

  [[Exports]] 