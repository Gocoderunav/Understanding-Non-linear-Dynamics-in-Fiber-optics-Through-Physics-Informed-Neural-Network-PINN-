![image](https://github.com/Gocoderunav/Understanding-Non-linear-Dynamics-in-Fiber-optics-Through-Physics-Informed-Neural-Network-PINN-/assets/120463239/083b884a-fb84-4ba8-972e-88a81df937e6)

# Solving-Non-Linear-Schrodinger-Equation-Using-PINN-s

As we know, when light travels through nonlinear media, phenomena such as the Kerr effect alter the pulse evolution. To understand how light pulse propagation changes, we use the famous equation known as the Non-Linear Schrödinger Equation (NLSE). The NLSE is a nonlinear partial differential equation with no analytical solution. Solving it requires an advanced understanding of mathematics and computational techniques. One common method to solve the NLSE is the Split-Step Fourier Method (SSFM). In this study, I have attempted to solve the NLSE using Physics-Informed Neural Networks (PINNs) in optical fiber.

Physics-Informed Neural Networks (PINNs) require less data compared to traditional neural networks. In our approach, we use the initial pulse as a constraint and ensure that the initial and boundary conditions of the wave are satisfied by the predicted neural network. The loss function of a PINN is designed to minimize both the governing equations of physics and the boundary conditions. This way, the PINN effectively integrates physical laws into the learning process, leading to accurate predictions with fewer data requirements.

when training a PINN, it's like teaching a student to solve a physics problem. You give the student some data to work with, like measurements from an experiment. But you also remind them of the rules of physics, like equations and constraints, that they must follow. So, as the student tries to find a solution, they not only have to match the data they've been given but also make sure their answer fits with the laws of physics. In the end, the student learns to solve the problem in a way that satisfies both the data they've seen and the physics they've been taught.

The governing equation is given by:
$$
\frac{\partial u}{\partial \xi} + \frac{i \\text{sgn}(\beta_2)}{2} \frac{\partial^2 u}{\partial \tau^2} - i N^2 |u|^2 u = 0
$$
The above NLSE is normalised. here the all the coefficients $$ \beta_2$$ and $$\gamma $$ are equal to one.






















