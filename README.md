## Task description

- Implement a [GetPositiveOctal](NumeralSystems/Converter.cs#L13) extention method that gets the value of a positive integer to its equivalent string representation in the octal numeral systems.
- Implement a [GetPositiveDecimal](NumeralSystems/Converter.cs#L21) extention method that gets the value of a positive integer to its equivalent string representation in the decimal numeral systems.
- Implement a [GetPositiveHex](NumeralSystems/Converter.cs#L29) extention method that gets the value of a positive integer to its equivalent string representation in the hexadecimal numeral systems.
- Implement a [GetPositiveRadix](NumeralSystems/Converter.cs#L39) extention method that gets the value of a positive integer to its equivalent string representation in a specified radix.
- Implement a [GetRadix](NumeralSystems/Converter.cs#L48) extention method that gets the value of a signed integer to its equivalent string representation in a specified radix.    
The task definition is given in the XML-comments for the methods.     
_Restriction: Don't use Framework's converter classes, use only use only the capabilities of the C# language._     
_Note: For negative integers their string representation is determined by binary representation in the additional code._
_For example:_      
>   Base 16 conversion
>   -2147483648      -->  0x80000000
>   -19327543        -->  0xfed915c9
>   -13621           -->  0xffffcacb
>   -18              -->  0xffffffee
>   12               -->  0xc
>   19142            -->  0x4ac6
>   2147483647       -->  0x7fffffff
>   Base 8 conversion
>   -2147483648      -->  0x20000000000
>   -19327543        -->  0x37666212711
>   -13621           -->  0x37777745313
>   -18              -->  0x37777777756
>   12               -->  0x14
>   19142            -->  0x45306
>   2147483647       -->  0x17777777777    