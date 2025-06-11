## My Solutions to Analysis I by Tao

### Section 3.3 Exercises
#### Ex. 3.3.2.
(Direct Proof)
If $f$ and $g$ are both injective (if $f$, $g$ $\colon \hookrightarrow$?) then $x \not= x' \implies f(x) \not= f(x')$ and $f(x) \not= f(x') \implies (g \circ f)(x) \not= (g \circ f)(x')$, from which $x \not= x' \implies (g \circ f)(x)$.

Suppose $f$ and $g$ are both surjective. Then $\forall y \in Y,$ $\exists x$ $f(x) = y,$ and also $\forall z \in Z,$ $\exists y$ $g(y) = z,$ and $|X|\geq|Y|\geq|Z|$. It follows that $\forall z \in Z,$ $\exists x$ $(g \circ f)(x) = z,$ i.e. $g \circ f$ is surjective as well.

\textit{Ex. 3.3.4.} 
(Direct Proof)
This one was trickier than the others, and I kicked myself when I found a simple solution (What made the solution tricky?). 

If $g \circ f = g \circ h$ and $g\colon Y \hookrightarrow Z \implies f = h,$ then $f \not= h \implies \neg(g\colon X \hookrightarrow Y)$ or $g \circ f \not= g \circ h,$ and this contrapositive is easy to show. 
