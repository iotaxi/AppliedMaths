---
layout: post
topic: counting
---
53.2.4 Graphics objects    
<a href="file:///C:/maxima-5.46.0/share/maxima/5.46.0/doc/html/maxima_singlepage.html#Functions-and-Variables-for-draw" target="_blank">file:///C:/maxima-5.46.0/share/maxima/5.46.0/doc/html/maxima_singlepage.html#Functions-and-Variables-for-draw</a>     
Graphic object: bars ([x1,h1,w1], [x2,h2,w2, ...])  
Graphic object: cylindrical (radius, z, minz, maxz, azi, minazi, maxazi)  
Graphic object: elevation_grid (mat,x0,y0,width,height)  
Graphic object: ellipse (xc, yc, a, b, ang1, ang2)  
Graphic object: errors ([x1, x2, …], [y1, y2, …])  
Graphic object: explicit  
    explicit (expr,var,minval,maxval)  
    explicit (fcn,var,minval,maxval)  
    explicit (expr,var1,minval1,maxval1,var2,minval2,maxval2)  
    explicit (fcn,var1,minval1,maxval1,var2,minval2,maxval2)  
Graphic object: image (im,x0,y0,width,height)  
Graphic object: implicit  
    implicit (fcn,x,xmin,xmax,y,ymin,ymax)  
    implicit (fcn,x,xmin,xmax,y,ymin,ymax,z,zmin,zmax)  
Graphic object: label  
    label ([string,x,y],...)  
    label ([string,x,y,z],...)  
Graphic object: mesh (row_1,row_2,...)  
Graphic object: parametric  
    parametric (xfun,yfun,par,parmin,parmax)  
    parametric (xfun,yfun,zfun,par,parmin,parmax)  
Graphic object: parametric_surface (xfun, yfun, zfun, par1, par1min, par1max, par2, par2min, par2max)  
Graphic object: points  
    points ([[x1,y1], [x2,y2],...])  
    points ([x1,x2,...], [y1,y2,...])  
    points ([y1,y2,...])  
    points ([[x1,y1,z1], [x2,y2,z2],...])  
    points ([x1,x2,...], [y1,y2,...], [z1,z2,...])  
    points (matrix)  
    points (1d_y_array)  
    points (1d_x_array, 1d_y_array)  
    points (1d_x_array, 1d_y_array, 1d_z_array)  
    points (2d_xy_array)  
    points (2d_xyz_array)  
Graphic object: polar (radius,ang,minang,maxang)  
Graphic object: polygon  
    polygon ([[x1, y1], [x2, y2], …])  
    polygon ([x1, x2, …], [y1, y2, …])  
Graphic object: quadrilateral (point_1, point_2, point_3, point_4)  
Graphic object: rectangle ([x1,y1], [x2,y2])  
Graphic object: region (expr,var1,minval1,maxval1,var2,minval2,maxval2)  
Graphic object: triangle (point_1, point_2, point_3)  
Graphic object: tube (xfun,yfun,zfun,rfun,p,pmin,pmax)
Graphic object: vector  
    vector ([x,y], [dx,dy])  
    vector ([x,y,z], [dx,dy,dz])  
	
