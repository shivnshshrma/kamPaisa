# kamPaisa
This project is based on the take home assignment received from Atlan for Platform Engineer Intern Role.



# This is my raw thoughts
# Problem
So, I have to minimize the cost of the cloud

## Description  
Team have noticed that their montly cloud costs is been increasing.

### Whats the main issue?
* Cost increases but isnt noticed by the team until its too late or maybe its noticed after they sees the bills.

* No if they came to knew that okay the cost/expenditure of the resources are increased, yet they are strugging to find what were the cause.
Maybe looking at every components might solve the issue. But time is money and we are already wasting so much.

* Im not clear what the third points is saying 
but reading it again and again what i understood that cost optimization is not easy(cant compromise the performance). So the task is to find just the top contributors to the cost.


well if the time permites we can also minimize the cost with little to no affect on the performance.



### What Can be the possible solution?
Well first of all, im unclear that if we have to make an unified system for the cloud system(i.e. for AWS, Azure, GCP) or specifically for a particular cloud provider.
But, a unified system will be the best solution as we dont have to spend more time figuring about GCP and Azure if we have done things only for AWS.

Now coming to the possible solution (001)
- [ ] **We have to measure the cost in real time.**
Like if not in real time then either on a particular interval like an hour or 3 or 6.
I hvae to give more thoughts on this that how will i going to measure this in real time and also give alerts that *Ohh!! looks like we have a hole in out pocket, we are loosing money*

- [ ] **Identification of the mole in our system**
After knowing we have a mole who is sitting idle and eating resources and time we need to catch him. Well in cloud computing we know that we pay for what we use. So there must be some mole who just doing nothing and but have alot of resources or important(expensive) resources or maybe both. 
How can we catch them though?
Well the initial thought is analuzing the resources logs. And on the basis of the first task which is finding where our money is going we can figure out, who is the money eater.

- [ ] ***More then one mole!!!***
Looks like we have more than one culprit to catch!! So whats we have to do this find out the culprits and stand them in a line in decending order(The more money you have eaten and the more less important you are, stand first. )



[^1]: More thoughts to be given to find the best, simple and optimal solution.
