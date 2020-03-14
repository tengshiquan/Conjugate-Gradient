# An Introduction to the Conjugate Gradient Method Without the Agonizing Pain

原 Repo 复现了论文里的各个章节,包括图形的生成.   正好方便验证一些基础的东西

1.  二次函数的f(x)的图像如果是像椭圆碗一样,  那么对应的A正定,  同时特征向量必定正交.  从等高线的角度看, 椭圆的两个轴必定是垂直的, 不然就不是椭圆了.
2.  二次函数里面, 一次项的影响比较小.   就像一元变量的抛物线, 会影响中轴线以及导数, 但大方向还是二次项系数决定, 开口方向.  常数项影响力更小, 只是影响图像的上下平移. 
3. 所谓大方向, 即 二次型以线性变换为 标准形:  $f = \lambda_1y_1^2 +\lambda_2y_2^2+\dots +\lambda_ny_n^2$ , 所以核心还是特征值把控整体的形状. 
4. 论文里的例子用的f(x)二次型是带一次项的, 所以最小值点不是0点
5. repo里面的有些图也是只是为是实现图, 用的假数据











The Conjugate Gradient Method is the most prominent iterative method for solving sparse systems of linear equations. Unfortunately, many textbook treatments of the topic are written with neither illustrations nor intuition, and their victims can be found to this day babbling senselessly in the corners of dusty libraries. For this reason, a deep, geometric understanding of the method has been reserved for the elite brilliant few who have painstakingly decoded the mumblings of their forebears. Nevertheless, the Conjugate Gradient Method is a composite of simple, elegant ideas that almost anyone can understand. Of course, a reader as intelligent as yourself will learn them almost effortlessly.
The idea of quadratic forms is introduced and used to derive the methods of Steepest Descent, Conjugate Directions, and Conjugate Gradients. Eigenvectors are explained and used to examine the convergence of the Jacobi Method, Steepest Descent, and Conjugate Gradients. Other topics include preconditioning and the nonlinear Conjugate Gradient Method. I have taken pains to make this article easy to read. Sixty-six illustrations are provided. Dense prose is avoided. Concepts are explained in several different ways. Most equations are coupled with an intuitive interpretation.

By: [Jonathan Richard Shewchuk](https://people.eecs.berkeley.edu/~jrs/) August 1994

Converted to a notebook by [André van Schaik](http://westernsydney.edu.au/bens) in June 2017. You can now zoom images and rotate 3D images, and I've added a few interactive figures with sliders to play with. 

Start reading at [CG00.ipynb](https://github.com/vschaik/Conjugate-Gradient/blob/master/CG00.ipynb)
