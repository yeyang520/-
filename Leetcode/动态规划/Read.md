**动规五部曲**
1.确定dp数组及下标的意义

2.确定递推公式

3.dp数组如何初始化

4.确定遍历顺序

5.举例推导dp数组

**目前已经见过的类型**

dp[i] = max(dp[i] , dp[j - weight[i] + value[i])

dp[j] += dp[j - coins[i]]
