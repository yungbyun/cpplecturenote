# 대학생 ML 캠프
https://github.com/UniversityMLCampJeju/2019

# 설문조사 (매 시간 끝날 때 쯤)
https://goo.gl/forms/yKEOtNCUae8KCCq43

# 거꾸로 학습 후 이해한 내용과 궁금한 내용 
https://goo.gl/forms/nyKYBxUpWDa1cST23

# 우리는 왜 대학에 가는가? (동영상)
https://www.youtube.com/watch?v=nttlAfVQT6w

class Point : #gildong
    iX = 0
    iY = 0
    def Assign(self, a, b):
        self.iX = a
        self.iY = b

    def Add(self):
        return self.iX + self.iY

class Circle(Point):
	iRadius = 0
	def SetRadius(self, r):
		self.iRadius = r

	def Area(self):
		return 3.14 * self.iRadius * self.iRadius

class 타원(Circle):
    iRadius2 = 0
    def SetRadius2(self, b):
        self.iRadius2 = b
	
    def Area(self):
        return 3.14 * self.iRadius * self.iRadius2

gildong = Point()
youngja = Circle()
cheolsu = 타원()

cheolsu.SetRadius(100)
cheolsu.SetRadius2(1)
a = cheolsu.Area()
print("영자의 면적=", a)




