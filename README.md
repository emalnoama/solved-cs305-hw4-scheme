Download Link: https://assignmentchef.com/product/solved-cs305-hw4-scheme
<br>
In this homework you will evaluate values of some Scheme expressions using MIT Scheme interpreter. It would help you to understand how things work. It would be better for you, if you first try to guess the value of the expressions, and then have it evaluated by the MIT Scheme interpreter.

<h1>1             Expressions</h1>

There are 59 expressions given below. Evaluate all of these expressions, first on paper, and then by using MIT Scheme interpreter.

1

(+ 1 2)

(+ 1 2 3 4 5 6)

(- 5 (+ 1 2))

(+)

(define x 2) x

(define y (* 10 4)) y

(/ y (- 8 1 x))

(define add +)

(add 2 3)

(define + -)

(- (+ 2 3) 1)

(define + add)

(- (+ 2 3) 1)

(if #t “true” “false”)

(if #f “true” “false”)

(if “true” “false” “true”)

(if “false” “false” “true”)

(if 0 ’true ’false)

(if 1 ’true ’false)

(if -1.5 ’true ’false)

(if (&lt; x y) (/ y x) (/ 100 0))

(if (&gt;= x y) (/ y x) (/ x y))

(if (= x 2.0) x y)

(boolean? #t)

(boolean? #f)

(boolean? “true”)

(boolean? “false”)

(boolean? ’true)

(boolean? ’false)

(symbol? “symbol”)

(symbol? ’not-a-symbol)

(eq? ’x ’y)

(eq? ’x x)

(define x ’this-symbol)

(define y (quote this-symbol))

(eq? x y)

(eq? x ’this-symbol)

(list 1 2 3 4 5) (list 1 ’a ’2 x)

’(1 a 2 x)

(list ’(+ 1 2) (+ 1 2))

(list (list (list 1 2) 3 4) (+ 2 3) (- 8 2))

(list)

(list (list ’()))

(cons 1 2)

(cons 1 ’(2))

(cons ’a (list ’b ’c ’d))

(cons ’a ’(b c d))

(list ’a ’(b c d))

(car (list 1 2 3))

(cdr (list 1 2 3))

(car (cons 1 ’(2)))

(cdr (cons 1 ’(2)))

(car (cons 1 2))

(cdr (cons 1 2))

(map apply (list cons list (lambda x (car x))) (list ’(1 2) ’(1 2) ’(1 2)))