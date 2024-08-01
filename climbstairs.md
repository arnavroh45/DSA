Memoization:
int solve(int steps, int n, vector<int> dp)
{   
    if(steps>n)
        return 0;
    if(steps==n)
        return 1;
    if(dp[steps]!=-1)
        return dp[steps];
    int one = solve(steps+1, n, dp);
    int two = solve(steps+2, n, dp);
    return dp[steps] = one + two;
}
int climbStairs(int n) {
    vector<int> dp(n+1, -1);
    return solve(0, n, dp);
}

Tabulation:
int climbStairs(int n) {
    int prev2 = 1;
    int prev1 = 1;
    int answer;
    for(int i = 2;i<=n;i++)
    {
        int answer = prev2 + prev1;
        prev2 = prev1;
        prev1 = answer;
    }
    return prev1;
}