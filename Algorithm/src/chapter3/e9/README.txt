任何一个正整数都可以用2的幂次方表示。
例如：137=2^7+2^3+2^0，同时约定几次方用括号来表示，即a^b可表示为a(b)，由此可知，137可表示为：2(7)+2(3)+2(0)，进一步：7=2^2+2+2^0(2^1用2表示)3=2+2^0。所以最后137可表示为：2(2(2+2(0))+2)+2(2(2+2(0)))+2(2(2)+2(0))+2+2(0)。
输入：正整数(n<=20 000)。
输出：符合约定的n的0,2表示（在表示中不能有空格）。
