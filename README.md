SlackSim
========
Simulating future many core processors with a reasonable execution speed and accuracy is a challenge. 
Simulating all interactions between all cores sequentially is very inefficient and not scalable.
Parallelizing this taking all these interactions into account has huge synchronization overhead. Imagine
a 1000 core system where each core is run as separate theread and synchronizes with others for every 100-500
insturctions when running billions of instructions.
Simulations are done to trade off different architectural design choices. So here relative comparison of
simulation metrics are very important compared to that of absolute numbers. This gives a intuitive hint that
accuracy in these simulations can be relaxed to the level that relative comparison of simulations still makes sense.

Reference papers can be found here.
[1] CHEN”, J. 2009. Parallel simulations of chip multiprocessors. Ph.D. thesis,  University of Southern 
California, Los Angeles, CA, USA. 

[2] CHEN, J., ANNAVARAM, M., AND DUBOIS, M. 2008. Slacksim: A platform for  parallel simulations of 
cmps on  cmps. Tech. Rep. 6, Department of Computer Science, University of Southern California, Los 
Angeles, CA. 

[3] CHEN, J., ANNAVARAM, M., AND DUBOIS, M. 2009a. Exploiting simulation slack to improve parallel 
simulation speed. In Proceedings of the 2009 International Conference on Parallel Processing. ICPP ’09. 
371–378. 

[4] CHEN, J., ANNAVARAM, M., AND DUBOIS, M. 2009b. Slacksim: a platform for parallel simulations of 
cmps on cmps. SIGARCH Comput. Archit. News 37, 20–29. 

[5] CHEN, J., DABBIRU, L. K., WONG, D., ANNAVARAM, M., AND DUBOIS, M.  2010. Adaptive and 
speculative  slack simulations of cmps on cmps. In Proceedings of the 2010 43rd Annual IEEE/ACM 
International Symposium on Microarchitecture. MICRO ’43. 523–534. 

CopyRight
Prof. Michel Dubois @ USC, Prof. Murali Annavaram @ USC, Jianwei Chen @ Oracle and Lakshmi Kumar Dabbiru @ Google.