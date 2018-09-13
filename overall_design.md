
# 第三章  测试手册

# 1 测试策略
  测试是为了发现程序中的错误而执行程序的过程，好的测试方案是极可能发现迄今为止尚未发现的错误的测试方案。成功的测试是发现了至今为止尚未发现的错误的测试。在测试时要遵循相应的测试准则，比如所有的测试均应该追溯到用户需求，把Pareto原理应用到软件测试中。Pareto原理说明，测试发现的错误中的80％很可能是由程序中20％的模块造成的。当然，问题是怎样找出这些可疑的模块并彻底地测试它们。
  #
 常见的测试方法有两种，黑盒测试和白盒测试。其中黑盒测试是在已知系统应该具有的功能的前提下进行，用于测试每个功能是否能正常使用。白盒测试要求测试者完全知道程序的结构和处理算法，用于检测程序中的主要通路是否能按照预定要求正确工作。 
 #
鉴于本系统的开发环境，所以测试时采用对应的测试环境,即在Windows操作系统下进行测试。
#
![image](https://github.com/dingdi0353151510/lala/blob/master/image/environment.png)
#
在对本系统的功能进行测试时，采用黑盒测试方法。在对每个模块进行测试时，采用白盒测试法。模块测试时，要把测试重点放到以下五个方面：模块接口，局部数据结构，重要的执行通路，出错处理通路，边界条件。 
#
当把模块组装成系统时，需要进行集成测试。本系统采用渐增式测试方法，即把下一个要测试的模块同已经测试好的那些模块结合起来进行测试，测试完后再把下一个应该测试的模块结合进来进行测试。
#
最后，在软件开发完毕后，还要进行确认测试，即验收测试，用来验证软件的有效性。软件的有效性就是指，软件的功能和性能如同用户所期待的那样。
# 2 测试方案和预期的测试结果
测试方案中包括测试时使用的输入数据（测试用例），还包括每组输入数据预定要检验的功能，以及每组输入数据预期应得到的正确输出。
# 2.1
![image](https://github.com/dingdi0353151510/lala/blob/master/image/c1.png)
# 2.2
![image](https://github.com/dingdi0353151510/lala/blob/master/image/c2.png)
# 2.3
![image](https://github.com/dingdi0353151510/lala/blob/master/image/c3.png)
# 2.4
![image](https://github.com/dingdi0353151510/lala/blob/master/image/c4.png)
# 2.5
![image](https://github.com/dingdi0353151510/lala/blob/master/image/c5.png)
# 2.6
![image](https://github.com/dingdi0353151510/lala/blob/master/image/c6.png）

 




# 3 测试进度计划
#
![image](https://github.com/dingdi0353151510/lala/blob/master/image/t1.png）
