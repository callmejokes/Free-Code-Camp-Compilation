EDIT!!!! guide codes

~~ kitty_ipsum_1.txt info ~~

#cat kitty_ipsum_1.txt | wc -l >> kitty_info.txt
Number of lines:
27

#cat kitty_ipsum_1.txt | wc -w >> kitty_info.txt
Number of words:
332

#wc < kitty_ipsum_1.txt -m >> kitty_info.txt
#wc < -m kitty_ipsum_1.txt >> kitty_info.txt
Number of characters:
1738

#grep 'meow' kitty_ipsum_1.txt
#man grep
#grep 'meow' kitty_ipsum_1.txt --color
#grep 'meow' kitty_ipsum_1.txt -n --color
#grep 'meow[a-z]*' kitty_ipsum_1.txt --color -n
#grep 'meow[a-z]*' kitty_ipsum_1.txt -c -n
#grep 'meow[a-z]*' kitty_ipsum_1.txt -o -n
#grep 'meow[a-z]*' kitty_ipsum_1.txt -o | wc -l
#grep 'meow[a-z]*' kitty_ipsum_1.txt -o | wc -l >> kitty_info.txt
Number of times meow or meowzer appears:
7

#grep 'meow[a-z]*' kitty_ipsum_1.txt -n | sed 's/([0-9]+).*/\1/' -E >> kitty_info.txt
Lines that they appear on:
1
4
10
22
23

#grep 'cat[a-z]*' kitty_ipsum_1.txt -o | wc -l >> kitty_info.txt
Number of times cat, cats, or catnip appears:
7

#grep 'cat[a-z]*' kitty_ipsum_1.txt -n | sed 's/([0-9]+).*/\1/' -E >> kitty_info.txt
Lines that they appear on:
1
3
7
17
21
22
26


~~ kitty_ipsum_2.txt info ~~

Number of lines:
28

Number of words:
307

Number of characters:
1678

Number of times meow or meowzer appears:
9

Lines that they appear on:
4
8
12
20
24
25
28

Number of times cat, cats, or catnip appears:
8

Lines that they appear on:
10
14
19
20
25
26
28
