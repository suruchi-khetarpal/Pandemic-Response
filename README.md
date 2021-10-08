# Pandemic-Response
A new virus has broken out in a city and has an incubation period of  𝑑=5  days. Starting from  𝑎=2  days after infection to the last day of the incubation period, each infected patient has close contact with  𝑛=4  uninfected people, and infects each of them with probability  𝑝=0.2  independently from others. At the end of the last day of incubation, each infected person reports to the hospital and enters isolation, which means that they stop infecting others.

Suppose that there is exactly 1 infected person on Day 0, create a function that simulates the number of patients who report to the hospital at the end of Day 1 through Day  𝑚 . The function should be called simulateNewCases and has the following arguments:

m: the number of days to simulate.
a (default value 2): the first day after infection when a patient becomes contagious.
d (default value 5): the last day after infection when a patient may infect others (not in isolation).
n (default value 4): the number of uninfected individuals a person contacts each day.
p (default value 0.2): the probability of infecting a close contact each day.
The function should return a list of  𝑚  integers, representing the number of infected individuals who exit incubation and report to the hospital at the end of Day 1 through Day  𝑚 .

To illustrate the timeline. Suppose that a person is infected on Day 5, then the person becomes contagious on Day  5+𝑎=7  and starting on that day, has the capacity to infect up to  𝑛  people per day. At the end Day  5+𝑑=10 , after possibly infecting new people on that day, the patient reports to the hospital and enters into isolation.
