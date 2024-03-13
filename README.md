# Module 5 | Muhamad Pascal Alfin Pahlevi

## /all-student-name screenshot
<img width="1010" alt="image" src="https://github.com/PascalPahlevi/exercise-profiling/assets/143638456/9d649313-9333-452c-bb7e-bb4b9f3aa5c7">
<img width="1012" alt="image" src="https://github.com/PascalPahlevi/exercise-profiling/assets/143638456/51fcb4f9-a25d-45a6-b7c4-d51b399bea5c">
<img width="1013" alt="image" src="https://github.com/PascalPahlevi/exercise-profiling/assets/143638456/bcf62b63-17cb-4ac0-ae69-ce5c729c42d1">

## student-name CLI results
<img width="900" alt="image" src="https://github.com/PascalPahlevi/exercise-profiling/assets/143638456/db37244d-459b-467d-9592-3ba3007e8193">
<img width="946" alt="image" src="https://github.com/PascalPahlevi/exercise-profiling/assets/143638456/6b673367-571b-4e1b-8ec9-0b9e689f6aac">

## /highest-gpa screenshot
<img width="1010" alt="image" src="https://github.com/PascalPahlevi/exercise-profiling/assets/143638456/91c4211e-7cb8-4e03-842c-62f8c5d580a4">
<img width="1015" alt="image" src="https://github.com/PascalPahlevi/exercise-profiling/assets/143638456/29320a30-7d98-454b-9bd8-956a5752874b">
<img width="1013" alt="image" src="https://github.com/PascalPahlevi/exercise-profiling/assets/143638456/fdb4f1cf-21d7-4061-b804-a14f00383522">

## highest-gpa CLI results
<img width="886" alt="image" src="https://github.com/PascalPahlevi/exercise-profiling/assets/143638456/0b691471-0ffa-42bf-bd5c-59af286cff18">
<img width="949" alt="image" src="https://github.com/PascalPahlevi/exercise-profiling/assets/143638456/119579d3-dce6-4c1a-8729-ec7a9e2decdc">

## Conclusion
Running the tests again using JMeter proved the results to be better after optimization compared to its initial measurements before optimization. Both endpoints managed to complete their respective tasks much faster after the optimization, improving the performance by more than 20%, which in my opinion proved the success of the optimization.

# Reflection
1. What is the difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler in the context of optimizing application performance?

The main difference between both approaches of performance testing is that JMeter relies more real-world simulations while the IntelliJ Profiler focuses more on determining the specific issues within the code that may attribute to the performance. For example, when using JMeter, we get information such as response time and resource usage, among many others, which helps us identify and decided whether the application will perform well enough under different condiitions. On the other hand, with IntelliJ Profiler, we would be able to identify the specific parts of the code that perform with the most load, which in return helps us specifically identify issues with the code. 

2. How does the profiling process help you in identifying and understanding the weak points in your application?

In my opinion, profiling helps me identify and understand weak points in many ways, however I find it to be very helpful when helping me refactor my code. Apart from that it also helps me understand how the process itself works, like reading flame graphs, analyzing thread activity, and identifying bottlenecks in the performance of the application itself.

3. Do you think IntelliJ Profiler is effective in assisting you to analyze and identify bottlenecks in your application code?

Yes, I do find IntelliJ Profiler to be effective in assisting me analyze and identify bottlenecks in my application code because the features it provides help me point out specific sections of the code that may be working twice as long compared to others for example. Given this information, I would then be able to tweak any of the sections, refactoring them, leading to a change in performance. Apart from that, with the flame graph, IntelliJ Profiler is a great way for me to easily visualize the performance load for specific parts of my code, giving me an overall idea on how it works altogether.

4. What are the main challenges you face when conducting performance testing and profiling, and how do you overcome these challenges?

With performance testing and profiling, I would say that since I am still quite inexperienced, initially reading and understanding the results of profiling was quite the challenge for me. Considering that these are features I have only recently came across with, I needed some time to understand what I was analyzing but I believe this could eventually be overcome through repetition. By getting myself used to this process, I will eventually be able to find what I am looking for quickly and analyze the results just as fast. In addition to that, I also found optimizing the code itself to be quite challenging as I sometimes have no clue what I can do to improve the code faster. In order to overcome this, I had to conduct my own research and brainstorm ideas on my own that may contribute to an increase in the code performance..

5. What are the main benefits you gain from using IntelliJ Profiler for profiling your application code?

In terms of benefits to the code itself, the number one thing in my opinion would be performance. By profiling the application code using IntelliJ Profiler, I was able to determing which sections of my code are most inefficient and optimize them, thus increasing the application's overall performance. However, when it comes to benefits for myself, I would say that using IntelliJ Profiler was a good way to practice profiling, identifying performance bottlenecks and fixing them.

6. How do you handle situations where the results from profiling with IntelliJ Profiler are not entirely consistent with findings from performance testing using JMeter?

In the first place, IntelliJ Profiler and JMeter have completely different usages. Due to this, discrepancies could appear between the both of them which should be pretty common considering their differences. However, if such a situation arises, I find the best way to handle them is by simply making changes to their settings to ensure that they are both running with the same or similar environments.

7. What strategies do you implement in optimizing application code after analyzing results from performance testing and profiling? How do you ensure the changes you make do not affect the application's functionality?

When optimizing the code after analysis, I will first try to find sections of the program code with the highest runtime to get a general idea on what is affecting the performance. Afterwards, I would be able to identify the specific method/function that may need some optimizing and make the necessary changes to improve said method. In order to ensure that the changes I make do not affect the application's overall functionality, I would need to constantly monitor the output I get after running the code. Through local host, I would be able to check the output for both before and after optimization. Having both outputs, I would be able to make comparisons and if any differences arise, I would have to fix the code again and if otherwise, I would have an optimized code that did not affect the application's functionality.



