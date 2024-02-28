[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/sh5wcqPS)
# Homework 2: MeshEdit

You can view the spec for this project at [Assignment 2: MeshEdit](https://cs184.eecs.berkeley.edu/sp24/docs/hw2-spec).

### Part 1
- De CasteLjau's algorithm is a recursive method for evaluating Bezier curves. It is based on the principle of linear interpolation and can be used to find any point along a Bezier curve. The algorithm works by repeatedly subdividing the control points until only one point remains, which is the point on the curve corresponding to the given parameter value.
<br>
The way I implemented is following the procedure above, find the total n-1 intermediate points, then return them.
- 
