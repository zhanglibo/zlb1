# -*- coding: UTF-8 -*-

class siz:
    _di=5.0
    _gao=6.0
    _cbz=3.0
    _dbz=5.0
    _bj=6.0
class graph(siz):
    def rectangle(self):
        self.s1= self._di*self._gao
        print "矩形面积：%f." %  self.s1
        return self.s1
    def square(self):
        self.s2= self._di*self._gao
        print "正方形面积：%f." %  self.s2
        return self.s2
    def parallelogram(self):
        self.s3= self._di*self._gao
        print "平行四边形面积：%f." %  self.s3
        return self.s3
    def rt(self):
        self.s4= 0.5*self._di*self._gao
        print "直角三角形面积：%f." %  self.s4
        return self.s4
    def et(self):
        self.s5= 0.5*self._di*self._gao
        print "等边三角形面积：%f." %  self.s5
        return self.s5
    def triangle(self):
        self.s6= 0.5*self._di*self._gao
        print "三角形面积：%f." %  self.s6
        return self.s6
    def circle(self):
        self.s7= (3.14*(self._bj*self._bj))
        print "圆形面积：%f." %  self.s7
        return self.s7
    def ellipse(self):
        self.s8= (3.14*(self._dbz*self._cbz))
        print "椭圆形面积：%f." %  self.s8
        return self.s8

    
a=graph()
hs=[a.rectangle(),a.square(),a.parallelogram(),a.rt(),a.et(),a.triangle(),a.circle(),a.ellipse()]
s=0
for i in range(0,8):
    s=s+hs[i]
print "面积总和为：%f."% s
v=s/8
print "面积平均值为：%f."% v
        
