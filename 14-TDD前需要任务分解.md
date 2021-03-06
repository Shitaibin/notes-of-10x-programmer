14|大师级程序员的工作秘笈

TDD正确实践是由以下循环构成的：
1. 先任务分解（分解到无法再分解）形成微任务
2. 编写1个微任务的测试
3. 实现微任务
4. 重构刚才的实现
5. 选择下一个微任务，继续循环



其他摘录与思考：
1. 任务分解的关键在于：粒度要尽量小，微任务之间保持独立，不相互依赖。
1. 每个微任务都是可以单独提交的。
1. 如果在以上过程中遇到新的问题，先把问题记录到任务列表，继续当前的微任务，完成后微任务后再解决遇到的问题。
1. 如果把在Github上连续1000天持续提交代码作为目标，则你的任务粒度要非常的小，每天都可以做1个微任务。
1. 如果任务不能很好的分解，说明任务还没有想清楚，还需要更多的信息，或者需要更好的解决方案。
1. 如果任务特别小，可以立马修改完，那就可以采用主分支的策略，大家都在主分支上进行开发，而对于大的功能和修改时，才需要拉新的个人分支。
