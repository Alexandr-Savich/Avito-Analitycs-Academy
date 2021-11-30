# Task 1
## python -m doctest -v -o NORMALIZE_WHITESPACE main.py:
Trying:
    encode('SOS')
Expecting:
    '... --- ...'
ok
Trying:
    encode ('MSU')
Expecting:
     '-- ... ..-'
ok
Trying:
    encode ('MIT IS BETTER THAN HSE') # doctest: +ELLIPSIS
Expecting:
    '-- .. - ... .... ... .'
ok
Trying:
    encode('help')
Expecting:
    Traceback (most recent call last):
    ...
    KeyError: 'h'
ok
2 items had no tests:
    main
    main.decode
1 items passed all tests:
   4 tests in main.encode
4 tests in 3 items.
4 passed and 0 failed.
Test passed.
