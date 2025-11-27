In file bekus_1 you can see a very interesting task which was given by my teacher. <s> ::= x | y | <s>x | x<s>y

This rule defines that <s> can be:
1. "x"
2. "y"
3. <s> followed by "x" (e.g., "xx", "yx")
4. "x" followed by <s> and then "y" (e.g., "xxy", "xyy")

Examples of valid strings:
- "x"
- "y"
- "xx" (from <s>x where <s> is "x")
- "yx" (from <s>x where <s> is "y")
- "xxy" (from x<s>y where <s> is "x")
- "xyy" (from x<s>y where <s> is "y")

