# Math formulas
## Area
- Circle: S = πR²
- Rectangle: S = ab
- Square: S = a²

## Perimeter
- Circle: P = 2πR
- Rectangle: P = 2a + 2b
- Square: P = 4a



# Функции с примерами вызова

## Окружнсть

***def area(r):***
    '''
Возвращает площадь окружности

	Параметры:
		r(int) : радиус окружности

	Возвращаемое значение:
		S(int): площадь окружности
'''
	return math.pi * r * r

***def perimeter(r):***
'''
Возвращает периметр окружности
	
	Параметры:
		r(int) : радиус окружности

	Возвращаемое значение:
		P(int): периметр окружности
'''
	return 2 * math.pi * r


## Прямоугольнк

***def area(a, b):***
'''
Возвращает площадь прямоугольника
	
	Параметры:
		a(int) : сторона прямоугольника
		b(int) : сторона, перпендикулярная стороне a

	Возвращаемое значение:
		S(int): площадь прямоугольнка
'''
    return a * b

***def perimeter(a, b):***
    '''
Возвращает периметр прямоугольника
	
	Параметры:
		a(int) : сторона прямоугольника
		b(int) : сторона, перпендикулярная стороне a

	Возвращаемое значение:
		P(int): периметр прямоугольнка
'''
    
    return (a+b)*2


## Квадрат
***def area(a):***
    '''
Возвращает площадь квадрата
	
	Параметры:
		a(int) : сторона квадрата
		
	Возвращаемое значение:
		S(int):  площадь квадрата
'''

    return a * a

***def perimeter(a):***
    '''
Возвращает периметр квадрата
	
	Параметры:
		a(int) : сторона квадрата
		
	Возвращаемое значение:
		P(int):  периметр квадрата
'''

    return 4 * a


## Треугольник

***def area(a, h):***
'''
Возвращает площадь треугольника
	
	Параметры:
		a(int) : сторона треугольника
		h(int) : высота треугольника, проведенная к стороне a
		
	Возвращаемое значение:
		S(int):  площадь треугольника
'''

    return a * h / 2
    
***def perimeter(a, b, c):***

'''
Возвращает периметр треугольника
	
	Параметры:
		a(int) : сторона треугольника1
		b(int) : сторона треугольника2
		c(int) : сторона треугольника3
		
	Возвращаемое значение:
		P(int):  периметр треугольника
'''

    return a + b + c
