# Mantissa-Exponent
This is java code that converts the manissa exponent format used in floating point binary storage

toMantissaExponent(double val, int m, int e) 
>val is the input binary number  
>m is the desired mantissa length  
>e is the desired exponent length  
>Outputs a mantissa phrase and an exponent separated by a space (ex. "011101 001000")  
  
toDouble(String str)
>str is a floating point binary input formatted as two binary phrases separated by a space (ex. "011101 001000"). The first phrase is the mantissa, and the second phrase is the exponent. Both are inputted in two's complement. So "011101 001000" would convert to a decimal value of 232 (0.011101 * 10^(001000) = 11101000 = 232).  
>Outputs the decimal conversion as a double.

toDecimalBinary(String num)
>Converts an input decimal "num" into a binary number  
>Outputs a string representing a binary number
