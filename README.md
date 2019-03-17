# e535-rigid-registration
Assignment 5
Part A

Find the centers of mass of the static and moving zebrafish.

Static Image_20449.tif

Moving Image_20450.tif

Align the centers of mass.

Start rotating around the center of mass of the static and measuring SSD (theta).

After you find the angle where SSD is minimized start translating (t_x and ty).

Plot SSD for theta, tx and ty.

You can use scipy.ndimage (affine_transform or rotate/shift functions).

Part B

Connect an optimizer (Powell's or L-BFGS-B) to the 2D zebrafish registration method that you created in the previous assignment. Both optimizers are available in scipy. See documentation and tutorials here 

 https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.minimize.htmlLinks to an external site.

https://docs.scipy.org/doc/scipy/reference/tutorial/optimize.htmlLinks to an external site.

Now you shouldn't need the for loops any more. The optimizer should be able to figure our the 3 parameters LaTeX: \theta,\:t_x,\:t_y θ , t x , t y .
