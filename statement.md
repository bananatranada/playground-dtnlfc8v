# Delegates
Delegates are objects that act as methods. These methods can be static, instance, lambda, etc.

```
delegate int Transformer (int x);
```
This delegate takes an int argument and returns an int.

```
static int Square (int x) = x * x;
Transformer t = Square;
```

Because `Square` follows `Transformer`'s signature, we can assign it as a `Transformer` type.