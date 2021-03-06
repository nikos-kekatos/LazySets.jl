# Fast 2D LPs

In this section we explain the implementation of the support vector for the case of
convex polygons.

## Introduction

Since vectors in the plane can be ordered by the angle with respect to the positive real axis, we can efficiently evaluate
the support vector of a polygon in constraint representation by comparing normal directions, provided that its edges are ordered. We use the symbol $\preceq$ to compare directions, where the increasing direction is counter-clockwise.


![../assets/intuition2dlp.png](../assets/intuition2dlp.png)

## Algorithm
