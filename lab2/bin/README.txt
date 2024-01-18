测试时进行了编号，为x-y-1core模式，x表示预取算法，为result.xlsl中的预取算法顺序，y表示替换算法，为result.xlsl中的替换算法顺序。1core表示单核。
同时test-1core表示新的策略组合。
为了存储空间考虑，现已将各个核心删除，如有需要请运行build_champsim.sh进行编译。


During the test, the number is x-y-1 core mode, where x represents the prefetch algorithm, the prefetch algorithm sequence in result.xlsl, and y represents the replacement algorithm, the replacement algorithm sequence in result.xlsl. 1 core represents a single core.

At the same time, test-1 core represents a new policy combination.
For storage space, all cores have been deleted. If necessary, please run build_ Champsim.sh.