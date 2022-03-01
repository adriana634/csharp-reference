# Built-in types

### Value types

#### Integral numeric types

The integral numeric types represent integer numbers. All integral numeric types are value types. They are also simple types and can be initialized with literals. All integral numeric types support arithmetic, bitwise logical, comparison, and equality operators.

| C# type/keyword | Range | Size | .NET type |
| --- | --- | --- | --- |
| sbyte | -128 to 127 | Signed 8-bit integer | System.SByte |
| byte | 0 to 255 | Unsigned 8-bit integer | System.Byte |
| sbyte | -128 to 127 | Signed 8-bit integer |	System.SByte |
| short | -32,768 to 32,767 | Signed 16-bit integer | System.Int16 |
| ushort | 0 to 65,535 | Unsigned 16-bit integer |	System.UInt16 |
| int | -2,147,483,648 to 2,147,483,647 | Signed 32-bit integer | System.Int32 |
| uint | 0 to 4,294,967,295 | Unsigned 32-bit integer |	System.UInt32 |
| long | -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807 | Signed 64-bit integer | System.Int64 |
| ulong | 0 to 18,446,744,073,709,551,615 | Unsigned 64-bit integer | System.UInt64 |
| nint | Depends on platform | Signed 32-bit or 64-bit integer | System.IntPtr |
| nuint | Depends on platform | Unsigned 32-bit or 64-bit integer | System.UIntPtr |

### Reference types

There are two kinds of types in C#: reference types and value types. Variables of reference types store references to their data (objects), while variables of value types directly contain their data. With reference types, two variables can reference the same object; therefore, operations on one variable can affect the object referenced by the other variable.

The following keywords are used to declare reference types:
* class
* interface
* delegate
* record

C# also provides the following built-in reference types:
* dynamic
* object
* string

## Resources
* https://www.netmentor.es/entrada/variables-y-operadores
* https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types
* https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/integral-numeric-types
* https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/reference-types

