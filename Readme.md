#Repository for testing jshell
3 : int n = 68;
n ==> 68

4 : byte b = 127;
b ==> 127

5 : char c = 'B';
c ==> 'B'

###After errors fixed
3 : int n = 68;
n ==> 68

4 : byte b = 127;
b ==> 127

5 : char c = 'B';
c ==> 'B'

6 : b = (byte)n;
b ==> 68

7 : c = (char)n;
c ==> 'D'
