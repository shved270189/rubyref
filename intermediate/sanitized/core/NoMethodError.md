# NoMethodError

Raised when a method is called on a receiver which doesn't have it defined and
also fails to respond with `method_missing`.

    "hello".to_ary

*raises the exception:*

    NoMethodError: undefined method `to_ary` for "hello":String