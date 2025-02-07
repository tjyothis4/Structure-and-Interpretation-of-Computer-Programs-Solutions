#lang sicp
(define (f x y z)
  (cond ((and (<= x y) (<= x z)) (+ (* z z) (* y y)))
        ((and (<= y x) (<= y z)) (+ (* x x) (* z z)))
        ((and (<= z x) (<= z y)) (+ (* x x) (* y y)))))
      