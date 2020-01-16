# PythonABC
#### map()
map()是 Python 内置的高阶函数，它接收一个函数 f 和一个 list，并通过
把函数 f 依次作用在 list 的每个元素上，得到一个新的 list 并返回。

#### reduce()
reduce()函数也是Python内置的一个高阶函数。reduce()函数接收的参数和
map()类似，一个函数 f，一个list，但行为和 map()不同，reduce()传入
的函数 f 必须接收两个参数，reduce()对list的每个元素反复调用函数f，
并返回最终结果值。
reduce()还可以接收第3个可选参数，作为计算的初始值。

#### sorted()
sorted()也是一个高阶函数，它可以接收一个比较函数来实现自定义排序，
比较函数的定义是，传入两个待比较的元素 x, y，如果 x 应该排在 y 的
前面，返回 -1，如果 x 应该排在 y 的后面，返回 1。如果 x 和 y 相等，
返回 0。

#### filter()
filter()函数是 Python 内置的另一个有用的高阶函数，filter()函数接收
一个函数 f 和一个list，这个函数 f 的作用是对每个元素进行判断，返回
True或 False，filter()根据判断结果自动过滤掉不符合条件的元素，返回
由符合条件元素组成的新list。
 