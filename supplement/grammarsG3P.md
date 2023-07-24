# Instructions used for PushGP Experiments

*Table of Contents*
1. [Count Odds](#count-odds)
2. [Find Pair](#find-pair)
3. [Fizz Buzz](#fizz-buzz)
4. [Fuel Cost](#fuel-cost)
5. [GCD](#gcd)
6. [Grade](#grade)
7. [Scrabble Score](#scrabble-score)
8. [Small Or Large](#small-or-large)

## Count Odds

```
<predefined> ::= 'b0 = bool(); b1 = bool(); b2 = bool()'
'i0 = int(); i1 = int(); i2 = int()'
'li0 = []; li1 = []; li2 = []'
'res0 = int()'
<code>
<code> ::= <code><statement>'\n'|<statement>'\n'
<statement> ::= <simple_stmt>|<compound_stmt>
<simple_stmt> ::= <call>|<assign>
<compound_stmt> ::= 'for '<int_var>' in '<list_int>':{:\n'<code>'\n:}'|'if '<bool>':{:\n'<code>':}'|'if '<bool>':{:\n'<code>':}else:{:\n'<code>':}'
<call> ::= <list_int_var>'.append('<int>')'|<list_int_var>'.insert('<int>','<int>')'|'deleteListItem('<list_int>', '<int>')'|'setListIndexTo('<list_int>', '<int>', '<int>')'
<assign> ::= <bool_var>' = '<bool>|<int_assign>|<list_int_var>' = '<list_int>
<number> ::= <number><num>|<num>
<num> ::= '0'|'1'|'2'|'3'|'4'|'5'|'6'|'7'|'8'|'9'
<comp_op> ::= '<'|'>'|'=='|'>='|'<='|'!='
<in_list_comp_op> ::= 'in'|'not in'
<list_comp_op> ::= '=='|'!='
<bool_var> ::= 'b0'|'b1'|'b2'
<bool> ::= <bool_var>|<bool_const>|'not '<bool>|'( '<bool>' '<bool_op>' '<bool>' )'|<int>' '<comp_op>' '<int>|<int>' '<in_list_comp_op>' '<list_int>|<list_int>' '<list_comp_op>' '<list_int>
<bool_op> ::= 'and'|'or'
<bool_const> ::= 'True'|'False'
<int_var> ::= 'i0'|'i1'|'i2'|'res0'
<int_assign> ::= <int_var>' = '<int>|<int_var>' '<arith_ops>'= '<int>
<int> ::= <int_var>|'int('<number>'.0)'|<arith_prefix><int>|'( '<int>' '<arith_ops>' '<int>' )'|<int_arith_ops_protected>'('<int>','<int>')'|'min('<int>', '<int>')'|'max('<int>', '<int>')'|'abs('<int>')'|'getIndexIntList('<list_int>', '<int>')'|'len('<list_int>')'|'sum('<list_int>')'
<arith_ops> ::= '+'|'-'|'*'
<int_arith_ops_protected> ::= 'divInt'|'mod'
<arith_prefix> ::= '+'|'-'
<list_int_var> ::= 'li0'|'li1'|'li2'|'in0'
<list_int> ::= <list_int_var>|<list_int_slice>|'list(map(lambda x: '<list_int_map>', '<list_int>'))'
<list_int_map> ::= '( x '<arith_ops>' '<int>' )'|<int_arith_ops_protected>'(x,'<int>')'
<list_int_slice> ::= <list_int>'['<int>':'<int>']'|<list_int>'[:'<int>']'|<list_int>'['<int>':]'
```

## Find Pair
```
<predefined> ::= 'b0 = bool(); b1 = bool(); b2 = bool()'
'i0 = int(); i1 = int(); i2 = int()'
'li0 = []; li1 = []; li2 = []'
'res0 = int(); res1 = int()'
<code>
<code> ::= <code><statement>'\n'|<statement>'\n'
<statement> ::= <simple_stmt>|<compound_stmt>
<simple_stmt> ::= <call>|<assign>
<compound_stmt> ::= 'for '<int_var>' in '<list_int>':{:\n'<code>'\n:}'|'if '<bool>':{:\n'<code>':}'|'if '<bool>':{:\n'<code>':}else:{:\n'<code>':}'
<call> ::= <list_int_var>'.append('<int>')'|<list_int_var>'.insert('<int>','<int>')'|'deleteListItem('<list_int>', '<int>')'|'setListIndexTo('<list_int>', '<int>', '<int>')'
<assign> ::= <bool_var>' = '<bool>|<int_assign>|<list_int_var>' = '<list_int>
<number> ::= <number><num>|<num>
<num> ::= '0'|'1'|'2'|'3'|'4'|'5'|'6'|'7'|'8'|'9'
<comp_op> ::= '<'|'>'|'=='|'>='|'<='|'!='
<in_list_comp_op> ::= 'in'|'not in'
<list_comp_op> ::= '=='|'!='
<bool_var> ::= 'b0'|'b1'|'b2'
<bool> ::= <bool_var>|<bool_const>|'not '<bool>|'( '<bool>' '<bool_op>' '<bool>' )'|<int>' '<comp_op>' '<int>|<int>' '<in_list_comp_op>' '<list_int>|<list_int>' '<list_comp_op>' '<list_int>
<bool_op> ::= 'and'|'or'
<bool_const> ::= 'True'|'False'
<int_var> ::= 'i0'|'i1'|'i2'|'in1'|'res0'|'res1'
<int_assign> ::= <int_var>' = '<int>|<int_var>' '<arith_ops>'= '<int>
<int> ::= <int_var>|'int('<number>'.0)'|<arith_prefix><int>|'( '<int>' '<arith_ops>' '<int>' )'|<int_arith_ops_protected>'('<int>','<int>')'|'min('<int>', '<int>')'|'max('<int>', '<int>')'|'abs('<int>')'|'getIndexIntList('<list_int>', '<int>')'|'len('<list_int>')'
<arith_ops> ::= '+'|'-'|'*'
<int_arith_ops_protected> ::= 'divInt'|'mod'
<arith_prefix> ::= '+'|'-'
<list_int_var> ::= 'li0'|'li1'|'li2'|'in0'
<list_int> ::= <list_int_var>|<list_int_slice>
<list_int_slice> ::= <list_int>'['<int>':'<int>']'|<list_int>'[:'<int>']'|<list_int>'['<int>':]'
```

## Fizz Buzz
```
<predefined> ::= 'i0 = int(); i1 = int(); i2 = int()'
'b0 = bool(); b1 = bool(); b2 = bool()'
's0 = str(); s1 = str(); s2 = str()'
'res0 = str()'
<code>
<code> ::= <code><statement>'\n'|<statement>'\n'
<statement> ::= <assign>|<if>
<assign> ::= <bool_var>' = '<bool>|<int_assign>|<string_var>' = '<string> | <string_var>' = str('<int_var>')'
<number> ::= <number><num>|<num>
<num> ::= '0'|'3'|'5'
<comp_op> ::= '<'|'>'|'=='|'>='|'<='|'!='
<bool_var> ::= 'b0'|'b1'|'b2'
<bool> ::= <bool_var>|<bool_const>|'not '<bool>|'( '<bool>' '<bool_op>' '<bool>' )'|<int>' '<comp_op>' '<int>|<string>' in '<string>|<string>' not in '<string>|<string>' == '<string>|<string>' != '<string>|<string>'.startswith('<string>')'|<string>'.endswith('<string>')'
<bool_op> ::= 'and'|'or'
<bool_const> ::= 'True'|'False'
<if> ::= 'if '<bool>':{:\n'<code>':}'|'if '<bool>':{:\n'<code>':}else:{:\n'<code>':}'
<int_var> ::= 'i0'|'i1'|'i2'|'in0'
<int_assign> ::= <int_var>' = '<int>|<int_var>' '<arith_ops>'= '<int>
<int> ::= <int_var>|'int('<number>'.0)'|<arith_prefix><int>|'( '<int>' '<arith_ops>' '<int>' )'|<int_arith_ops_protected>'('<int>','<int>')'|'min('<int>', '<int>')'|'max('<int>', '<int>')'|'abs('<int>')'|'len('<string>')'|'saveOrd('<string>')'
<arith_ops> ::= '+'|'-'|'*'
<int_arith_ops_protected> ::= 'divInt'|'mod'
<arith_prefix> ::= '+'|'-'
<string_var> ::= 's0'|'s1'|'s2'|'res0'
<string> ::= <string_var>|<string_const>|<string_slice>|'getCharFromString('<string>', '<int>')'|'saveChr('<int>')'|'('<string>' + '<string>')'|<string>'.lstrip()'|<string>'.rstrip()'|<string>'.strip()'|<string>'.lstrip('<string>')'|<string>'.rstrip('<string>')'|<string>'.strip('<string>')'|<string>'.capitalize()'
<string_slice> ::= <string>'['<int>':'<int>']'|<string>'[:'<int>']'|<string>'['<int>':]'
<string_const> ::= "'Fizz'"|"'Buzz'"|"'FizzBuzz'"
```

## Fuel Cost
```
<predefined> ::= 'b0 = bool(); b1 = bool(); b2 = bool()'
'i0 = int(); i1 = int(); i2 = int()'
'li0 = []; li1 = []; li2 = []'
'res0 = int()'
<code>
<code> ::= <code><statement>'\n'|<statement>'\n'
<statement> ::= <simple_stmt>|<compound_stmt>
<simple_stmt> ::= <call>|<assign>
<compound_stmt> ::= 'for '<int_var>' in '<list_int>':{:\n'<code>'\n:}'|'if '<bool>':{:\n'<code>':}'|'if '<bool>':{:\n'<code>':}else:{:\n'<code>':}'
<call> ::= <list_int_var>'.append('<int>')'|<list_int_var>'.insert('<int>','<int>')'|'deleteListItem('<list_int>', '<int>')'|'setListIndexTo('<list_int>', '<int>', '<int>')'
<assign> ::= <bool_var>' = '<bool>|<int_assign>|<list_int_var>' = '<list_int>
<number> ::= <number><num>|<num>
<num> ::= '0'|'1'|'2'|'3'
<comp_op> ::= '<'|'>'|'=='|'>='|'<='|'!='
<in_list_comp_op> ::= 'in'|'not in'
<list_comp_op> ::= '=='|'!='
<bool_var> ::= 'b0'|'b1'|'b2'
<bool> ::= <bool_var>|<bool_const>|'not '<bool>|'( '<bool>' '<bool_op>' '<bool>' )'|<int>' '<comp_op>' '<int>|<int>' '<in_list_comp_op>' '<list_int>|<list_int>' '<list_comp_op>' '<list_int>
<bool_op> ::= 'and'|'or'
<bool_const> ::= 'True'|'False'
<int_var> ::= 'i0'|'i1'|'i2'|'res0'
<int_assign> ::= <int_var>' = '<int>|<int_var>' '<arith_ops>'= '<int>
<int> ::= <int_var>|'int('<number>'.0)'|<arith_prefix><int>|'( '<int>' '<arith_ops>' '<int>' )'|<int_arith_ops_protected>'('<int>','<int>')'|'min('<int>', '<int>')'|'max('<int>', '<int>')'|'abs('<int>')'|'getIndexIntList('<list_int>', '<int>')'|'len('<list_int>')'|'sum('<list_int>')'
<arith_ops> ::= '+'|'-'|'*'
<int_arith_ops_protected> ::= 'divInt'|'mod'
<arith_prefix> ::= '+'|'-'
<list_int_var> ::= 'li0'|'li1'|'li2'|'in0'
<list_int> ::= <list_int_var>|<list_int_slice>|'list(map(lambda x: '<list_int_map>', '<list_int>'))'
<list_int_map> ::= '( x '<arith_ops>' '<int>' )'|<int_arith_ops_protected>'(x,'<int>')'
<list_int_slice> ::= <list_int>'['<int>':'<int>']'|<list_int>'[:'<int>']'|<list_int>'['<int>':]'
```


## GCD

```
<predefined> ::= 'b0 = bool(); b1 = bool(); b2 = bool()'
'i0 = int(); i1 = int(); i2 = int()'
'res0 = int()'
'whileLoopBreakCounter = int()'
<code>
<code> ::= <code><statement>'\n'|<statement>'\n'
<statement> ::= <simple_stmt>|<compound_stmt>
<simple_stmt> ::= <assign>
<compound_stmt> ::= 'while '<bool>' and whileLoopBreakCounter < 1000:{:\nwhileLoopBreakCounter += 1\n'<code>'\n:}'|'if '<bool>':{:\n'<code>':}'|'if '<bool>':{:\n'<code>':}else:{:\n'<code>':}'
<assign> ::= <bool_var>' = '<bool>|<int_assign>
<number> ::= <number><num>|<num>
<num> ::= '0'|'1'|'2'|'3'
<comp_op> ::= '<'|'>'|'=='|'>='|'<='|'!='
<bool_var> ::= 'b0'|'b1'|'b2'
<bool> ::= <bool_var>|<bool_const>|'not '<bool>|'( '<bool>' '<bool_op>' '<bool>' )'|<int>' '<comp_op>' '<int>
<bool_op> ::= 'and'|'or'
<bool_const> ::= 'True'|'False'
<int_var> ::= 'i0'|'i1'|'i2'|'in0'|'in1'|'res0'
<int_assign> ::= <int_var>' = '<int>|<int_var>' '<arith_ops>'= '<int>|'('<int_var>','<int_var>') = ('<int>','<int>')'
<int> ::= <int_var>|'int('<number>'.0)'|<arith_prefix><int>|'( '<int>' '<arith_ops>' '<int>' )'|<int_arith_ops_protected>'('<int>','<int>')'|'min('<int>', '<int>')'|'max('<int>', '<int>')'|'abs('<int>')'
<arith_ops> ::= '+'|'-'|'*'
<int_arith_ops_protected> ::= 'divInt'|'mod'
<arith_prefix> ::= '+'|'-'
```

## Grade

```
<predefined> ::= 'i0 = int(); i1 = int(); i2 = int()'
'b0 = bool(); b1 = bool(); b2 = bool()'
's0 = str(); s1 = str(); s2 = str()'
'res0 = str()'
<code>
<code> ::= <code><statement>'\n'|<statement>'\n'
<statement> ::= <assign>|<if>
<assign> ::= <bool_var>' = '<bool>|<int_assign>|<string_var>' = '<string>
<number> ::= <number><num>|<num>
<num> ::= '0'|'1'|'2'|'3'|'4'|'5'|'6'|'7'|'8'|'9'
<comp_op> ::= '<'|'>'|'=='|'>='|'<='|'!='
<string_literal> ::= 'A'|'B'|'C'|'D'|'F'
<bool_var> ::= 'b0'|'b1'|'b2'
<bool> ::= <bool_var>|<bool_const>|'not '<bool>|'( '<bool>' '<bool_op>' '<bool>' )'|<int>' '<comp_op>' '<int>|<string>' in '<string>|<string>' not in '<string>|<string>' == '<string>|<string>' != '<string>|<string>'.startswith('<string>')'|<string>'.endswith('<string>')'
<bool_op> ::= 'and'|'or'
<bool_const> ::= 'True'|'False'
<if> ::= 'if '<bool>':{:\n'<code>':}'|'if '<bool>':{:\n'<code>':}else:{:\n'<code>':}'
<int_var> ::= 'i0'|'i1'|'i2'|'in0'|'in1'|'in2'|'in3'|'in4'
<int_assign> ::= <int_var>' = '<int>|<int_var>' '<arith_ops>'= '<int>
<int> ::= <int_var>|'int('<number>'.0)'|<arith_prefix><int>|'( '<int>' '<arith_ops>' '<int>' )'|<int_arith_ops_protected>'('<int>','<int>')'|'min('<int>', '<int>')'|'max('<int>', '<int>')'|'abs('<int>')'|'len('<string>')'|'saveOrd('<string>')'
<arith_ops> ::= '+'|'-'|'*'
<int_arith_ops_protected> ::= 'divInt'|'mod'
<arith_prefix> ::= '+'|'-'
<string_var> ::= 's0'|'s1'|'s2'|'res0'
<string> ::= <string_var>|"'"<string_literal>"'"|<string_slice>|'getCharFromString('<string>', '<int>')'|'saveChr('<int>')'|'('<string>' + '<string>')'|<string>'.lstrip()'|<string>'.rstrip()'|<string>'.strip()'|<string>'.lstrip('<string>')'|<string>'.rstrip('<string>')'|<string>'.strip('<string>')'|<string>'.capitalize()'
<string_slice> ::= <string>'['<int>':'<int>']'|<string>'[:'<int>']'|<string>'['<int>':]'
```

##  Scrabble Score
```
<predefined> ::= 'i0 = int(); i1 = int(); i2 = int()'
'b0 = bool(); b1 = bool(); b2 = bool()'
's0 = str(); s1 = str(); s2 = str()'
'li0 = []; li1 = []; li2 = []'
'res0 = int()'
<code>
<code> ::= <code><statement>'\n'|<statement>'\n'
<statement> ::= <simple_stmt>|<compound_stmt>
<simple_stmt> ::= <call>|<assign>
<compound_stmt> ::= 'for '<int_var>' in '<list_int>':{:\n'<code>'\n:}'|'for '<string_var>' in '<string_var>':{:\n'<code>'\n:}'|'if '<bool>':{:\n'<code>':}'|'if '<bool>':{:\n'<code>':}else:{:\n'<code>':}'
<call> ::= <list_int_var>'.append('<int>')'|<list_int_var>'.insert('<int>','<int>')'|'deleteListItem('<list_int>', '<int>')'|'setListIndexTo('<list_int>', '<int>', '<int>')'
<assign> ::= <bool_var>' = '<bool>|<int_assign>|<string_var>' = '<string>|<list_int_var>' = '<list_int>
<number> ::= <number><num>|<num>
<num> ::= '0'|'1'|'2'|'3'|'4'|'5'|'6'|'7'|'8'|'9'
<comp_op> ::= '<'|'>'|'=='|'>='|'<='|'!='
<in_list_comp_op> ::= 'in'|'not in'
<list_comp_op> ::= '=='|'!='
<bool_var> ::= 'b0'|'b1'|'b2'
<bool> ::= <bool_var>|<bool_const>|'not '<bool>|'( '<bool>' '<bool_op>' '<bool>' )'|<int>' '<comp_op>' '<int>|<string>' in '<string>|<string>' not in '<string>|<string>' == '<string>|<string>' != '<string>|<string>'.startswith('<string>')'|<string>'.endswith('<string>')'|<int>' '<in_list_comp_op>' '<list_int>|<list_int>' '<list_comp_op>' '<list_int>
<bool_op> ::= 'and'|'or'
<bool_const> ::= 'True'|'False'
<int_var> ::= 'i0'|'i1'|'i2'|'res0'
<int_assign> ::= <int_var>' = '<int>|<int_var>' '<arith_ops>'= '<int>
<int> ::= <int_var>|'int('<number>'.0)'|<arith_prefix><int>|'( '<int>' '<arith_ops>' '<int>' )'|<int_arith_ops_protected>'('<int>','<int>')'|'min('<int>', '<int>')'|'max('<int>', '<int>')'|'abs('<int>')'|'getIndexIntList('<list_int>', '<int>')'|'len('<list_int>')'|'sum('<list_int>')'|<int_str_ops>'('<string>')'
<arith_ops> ::= '+'|'-'|'*'
<int_arith_ops_protected> ::= 'divInt'|'mod'
<int_str_ops> ::= 'len'|'saveOrd'
<arith_prefix> ::= '+'|'-'
<string_var> ::= 's0'|'s1'|'s2'|'in0'
<string> ::= <string_var>|<string_slice>|'getCharFromString('<string>', '<int>')'|'saveChr('<int>')'|'('<string>' + '<string>')'|<string>'.lstrip()'|<string>'.rstrip()'|<string>'.strip()'|<string>'.lstrip('<string>')'|<string>'.rstrip('<string>')'|<string>'.strip('<string>')'|<string>'.capitalize()'|<string>'.lower()'|<string>'.upper()'
<string_slice> ::= <string>'['<int>':'<int>']'|<string>'[:'<int>']'|<string>'['<int>':]'
<list_int_var> ::= 'li0'|'li1'|'li2'|'scrabblescore'
<list_int> ::= <list_int_var>|<list_int_slice>|'list(map(lambda x: '<list_int_map>', '<list_int>'))'|'list(map(lambda x: '<list_str_map>', '<string>'))'
<list_int_map> ::= '( x '<arith_ops>' '<int>' )'|<int_arith_ops_protected>'(x,'<int>')'
<list_str_map> ::= <int_str_ops>'(x)'
<list_int_slice> ::= <list_int>'['<int>':'<int>']'|<list_int>'[:'<int>']'|<list_int>'['<int>':]'
```
## Small Or Large

```
<predefined> ::= 'i0 = int(); i1 = int(); i2 = int()'
'b0 = bool(); b1 = bool(); b2 = bool()'
's0 = str(); s1 = str(); s2 = str()'
'res0 = str()'
<code>
<code> ::= <code><statement>'\n'|<statement>'\n'
<statement> ::= <assign>|<if>
<assign> ::= <bool_var>' = '<bool>|<int_assign>|<string_var>' = '<string>
<number> ::= <number><num>|<num>
<num> ::= '0'|'1'|'2'|'3'|'4'|'5'|'6'|'7'|'8'|'9'
<comp_op> ::= '<'|'>'|'=='|'>='|'<='|'!='
<string_const_part> ::= <string_const_part><string_literal>|<string_literal>
<bool_var> ::= 'b0'|'b1'|'b2'
<bool> ::= <bool_var>|<bool_const>|'not '<bool>|'( '<bool>' '<bool_op>' '<bool>' )'|<int>' '<comp_op>' '<int>|<string>' in '<string>|<string>' not in '<string>|<string>' == '<string>|<string>' != '<string>|<string>'.startswith('<string>')'|<string>'.endswith('<string>')'
<bool_op> ::= 'and'|'or'
<bool_const> ::= 'True'|'False'
<if> ::= 'if '<bool>':{:\n'<code>':}'|'if '<bool>':{:\n'<code>':}else:{:\n'<code>':}'
<int_var> ::= 'i0'|'i1'|'i2'|'in0'
<int_assign> ::= <int_var>' = '<int>|<int_var>' '<arith_ops>'= '<int>
<int> ::= <int_var>|'int('<number>'.0)'|<arith_prefix><int>|'( '<int>' '<arith_ops>' '<int>' )'|<int_arith_ops_protected>'('<int>','<int>')'|'min('<int>', '<int>')'|'max('<int>', '<int>')'|'abs('<int>')'|'len('<string>')'|'saveOrd('<string>')'
<arith_ops> ::= '+'|'-'|'*'
<int_arith_ops_protected> ::= 'divInt'|'mod'
<arith_prefix> ::= '+'|'-'
<string_var> ::= 's0'|'s1'|'s2'|'res0'
<string> ::= <string_var>|<string_const>|<string_slice>|'getCharFromString('<string>', '<int>')'|'saveChr('<int>')'|'('<string>' + '<string>')'|<string>'.lstrip()'|<string>'.rstrip()'|<string>'.strip()'|<string>'.lstrip('<string>')'|<string>'.rstrip('<string>')'|<string>'.strip('<string>')'|<string>'.capitalize()'
<string_slice> ::= <string>'['<int>':'<int>']'|<string>'[:'<int>']'|<string>'['<int>':]'
<string_const> ::= "'"<string_const_part>"'"|"'small'"|"'large'"
<string_literal> ::= ''|'\\\n'|'\\\t'|' '|'!'|'"'|'#'|'$'|'%'|'&'|"\\'"|'('|')'|'*'|'+'|','|'-'|'.'|'/'|'0'|'1'|'2'|'3'|'4'|'5'|'6'|'7'|'8'|'9'|':'|';'|'<'|'='|'>'|'?'|'@'|'A'|'B'|'C'|'D'|'E'|'F'|'G'|'H'|'I'|'J'|'K'|'L'|'M'|'N'|'O'|'P'|'Q'|'R'|'S'|'T'|'U'|'V'|'W'|'X'|'Y'|'Z'|'['|'\\\\'|']'|'^'|'_'|'`'|'a'|'b'|'c'|'d'|'e'|'f'|'g'|'h'|'i'|'j'|'k'|'l'|'m'|'n'|'o'|'p'|'q'|'r'|'s'|'t'|'u'|'v'|'w'|'x'|'y'|'z'|'{'|'|'|'}'
```