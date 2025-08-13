    
  BNum - Signed Logarithmic Big Number Library for Lua      
  ----------------------------------------------------      
      
  Representation:      
    Every number is represented as a table {sign, magnitude}      
    where:      
      - sign is -1, 0, or 1      
      - magnitude is the base-10 logarithmic value.      
      
  Special values:      
    - Zero is represented as {0, -math.huge}      
    - Undefined values use {±1, math.huge}      
      
  This representation allows working with extremely large or small numbers      
  efficiently in logarithmic space, while handling sign properly.      
      
  Features:      
    - Addition, subtraction (with sign and numeric stability)      
    - Multiplication, division      
    - Exponentiation, power, ldexp      
    - Zero and undefined value handling      
    - Floor, ceil, round, mod      
    - log10, ln, log      
      
  Usage:      
    The module returns a table `bnum` with functions to create and manipulate BNums.      
