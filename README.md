#include <iostream>
#include <ctime>
using namespace std;

/************************************************************************************
 ****************************** STAIR PROBLEM ***************************************
 * You are an avid stair climber.  To make it more interesting, you sometimes
 * take 1 step, you sometimes jump 2 steps, and you sometimes jump 3 steps.
 *
 * You want to determine how many possible ways you can climb any size stair
 * case with any number of steps. Since you are a programmer, you decide to
 * code up an algorithm to figure this out for you.
 *
 * Example:
 *  There are 7 possible ways to climb up a 4 step stair case
 *  (1, 1, 1, 1), (2, 1, 1), (1, 2, 1), (1, 1, 2), (2, 2), (3, 1), (1, 3)
 *
 *  There are 13 possible ways to climb up a 5 step stair case
 *  (1, 1, 1, 1, 1), (2, 1, 1, 1), (1, 2, 1, 1), (1, 1, 2, 1), (1, 1, 1, 2),
 *  (1, 2, 2), (2, 1, 2), (2, 2, 1), (3, 1, 1), (1, 3, 1), (1, 1, 3), (2, 3), (3, 2)
 *
 *
 *  Conditions:
 *      0 <= n <= 40
 *************************************************************************************/
unsigned int countWays(int n);

int main()
{
    int n;
    unsigned int ans;
    double time;
    clock_t startTime;
    
    cout << "Enter number of stairs: ";
    cin >> n;
    
    startTime = clock();
    ans = countWays(n);
    time = (clock() - startTime) / CLOCKS_PER_SEC;
    
    cout << "\nThere are " << ans << " ways to climb " << n << " stairs\nIt took " << time << " seconds to calculate this.\n";
    
    return 0;
}

unsigned int countWays(int n)
{
    
    
    return 0;
}
