# ComputationalGeometry
The first two programs, 'Circle-Segment_Intersection.cpp' and 'Circle-Segment_Intersect.py' calculate the number of points of intersection for a circle and a segment on a plane. It takes an input from file, which consists of 7 real numbers (type double): coordinates of the circle centre (2 numbers), radius of the circle and coordinates of the left and right ends of the segment (2 pairs of numbers, respectively). Python version handles the exceptions with potential overflow and underflow issues.

Mathematica program called 'Desargues_blank.nb' represents a numerical modeling of Desargues's theorem (https://en.wikipedia.org/wiki/Desargues%27s_theorem), a statement in projective (as well as Euclidean) geometry: 'Two triangles are in perspective axially if and only if they are in perspective centrally'. The output is dynamically interactive: user can stir the vertices of both triangles across the pane canvas and also move the centre of perspective by a slider.

'h-p_full_blank.nb' was designed to solve numerically the problem of qualtitative analysis for germs of so-called 'skew' solutions occuring in a system of a two-link mathematical pendulum in a rotating frame of reference. See the paper 'Soyfer_3CoursePaper_Eng.pdf' for clarifications on this question. Apart from the theoretically-mechanical side of it, the program plots a parametric curve (Smale diagram) with an implicit parameter function. It is essentially described in the following question on MathStackExchange: https://math.stackexchange.com/questions/3929241/plotting-parametric-curve-with-implicit-parameter-function
