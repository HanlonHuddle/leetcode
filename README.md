# leetcode
This repository is created in the process of finishing leetcode questions, with detailed explanation

# 692 Useage of c++ priority queue

332 to solve
https://leetcode.com/problems/reconstruct-itinerary/description/
toplogical sort

78 677

215 there is better soluation

What happens after you press power button till linux login screen promots?
https://discuss.leetcode.com/topic/92910/what-happens-in-the-background-from-the-time-you-press-the-power-button-until-the-linux-login-prompt-appears/2


self define priority_queue comparison class
```
bool compare(int a, int b)
{
   return (a<b);
}
priority_queue<int, decltype(&compare)> pq(&compare);
```
https://stackoverflow.com/questions/20826078/priority-queue-comparison

