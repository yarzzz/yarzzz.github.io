# 关于cpp virtual虚函数的使用

如果父类不实现，要加 = 0

'''
virtual int add(int a, int b) = 0;
'''

否则必须实现

'''
virtual int add(int a, int b) { return a + b; }
'''
