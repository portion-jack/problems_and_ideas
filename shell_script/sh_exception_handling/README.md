# Shell script

예외처리
1. try a if can't do b
- do a || b
2. try a if can't pass
- do a || : 
- (: mean true)
3. try a if can't do b (with ignore error message)
- do a 2>dev/null || b

    - /dev/null  == 1>dev/null -> STDOUT(standard output) to null
    - 1>dev/null == /dev/null  -> STDERR(standard error)  to null
    - 2>dev/null -> 
