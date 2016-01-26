## Is the Web Getting Slower?

I'm not sure if it is, but here's some data to help with the question.

In late November 2015, Firefox 42 was released. It received no code updates over its five-plus week lifetime until December brought on Firefox 43.

This offered an excellent window for studying the Web without the browser changing underneath the analysis.

At https://chutten.github.io/web-slowness/ find a live analysis of data from Firefox 42 from between November 10 and December 16 (a range over which Firefox Telemetry was receiving 2 million samples a day) with linear regression analysis over time.

Is the Web getting slower? How much slower? In what ways?

Page load times seem to have improved, but JavaScript Garbage Collection has gotten worse. As has memory allocation.

There are possible explanations for these:
* browsing sessions tend to get longer the further into a release you get, so maybe longer browser sessions account for the increases.
* users' browsing habits may have changed over the study period. Black Friday and the run up to Christmas might change the browsing habits of users who recognize these events.
* Computers feel slower over time, so maybe this is a measure of the computer slowing browsing down. Disks could be getting fuller, reducing cache hit speed. Computer memory could be getting bogged down with more running processes, causing increased swapping.
* Maybe Firefox users with faster browsing experiences stopped using Firefox gradually over the study period.

Further analysis could torpedo each of those extra possibilities, but I don't have the time to write the analyses and run them.

So I leave you with the question, and some data. Good luck.
