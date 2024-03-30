![All Student Result Table](https://github.com/austinsusanto/exercise-profiling/raw/main/images/all-student%20result%20table.png)
![All Student Name Result Table](https://github.com/austinsusanto/exercise-profiling/raw/main/images/all-student-name%20result%20table.png)
![Highest GPA Result Table](https://github.com/austinsusanto/exercise-profiling/raw/main/images/highest-gpa%20result%20table.png)

![All Student Log](https://github.com/austinsusanto/exercise-profiling/raw/main/images/all-student%20log.png)
![All Student Log](https://github.com/austinsusanto/exercise-profiling/raw/main/images/all-student-name%20log.png)
![Highest GPA Log](https://github.com/austinsusanto/exercise-profiling/raw/main/images/highest-gpa%20log.png)

# Reflection
1. The approach of performance testing using the JMeter gives us the performance data of the application. This includes the load test, stress test, and performance testing. The profiling technique done with the intelliJ Profiler optimizes the application through detection of bottlenecks and uneffective algorithms.
2. The profiling process helps us identify the weak points of the application through recording every data like total time and load allocated by certain methods so that we know which method are optimizable.
3. Yes, the intelliJ profiler comes with a lot of functionality like flame graph, method list, timeline, etc which helps us to analize and identify the methods that should be optimized.
4. In performance testing, the usual problem is setting realistic and relevant scenarios which are used to test. We often use too demanding scenarios and setting unreal standarts for our application eventhough our application is small scaled. In profiling, the problem comes in identifying which part causes the bottleneck in our application.
5. The intelliJ profiler gives easy access to the profiler for developer due to its integrated nature. It is easy to use and provides accurate and relevant data from the recording proccess.
6. When the test results from JMeter isnt consistent and are not reflective to the profiler results. This means that there are inconsistency within the hardware and load. We should do performance test relatively to the hardware performance and not overdo it.
7. After analyzing the results, we can see which part of the program use the most amount of resources. Then we can try to optimize the methods one-by-one from the largest resource user to the smallest. To ensure that the optimization doesnt change the functionality of the code, we must always run the test again before commiting the canges.
