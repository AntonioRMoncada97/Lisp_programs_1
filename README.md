(defun fact (n)
  (if (<= n 1)
      1
      (* n (fact (- n 1)))))


$ sbcl --load fact.lisp
* (fact 5)
120



(defun sum-list (lst)
  (if (null lst)
      0
      (+ (car lst) (sum-list (cdr lst)))))

* (sum-list '(1 2 3 4 5))
15



src/            # Lisp source code (.lisp)
docs/           # Assignment PDF/briefs


