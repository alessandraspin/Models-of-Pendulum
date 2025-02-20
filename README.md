# NetLogo Models of Pendulum
NetLogo simulations of different physical pendulums.

| Pendulum               | Simulation            |
|:------------------------:|-----------------------|
| **Double Pendulum** <br> <img src="double-pendulum.png" width="400"/> <br> $$\large \ddot{\theta}_1 = \frac{-g(2m_1 + m_2)\sin(\theta_1) - m_2g\sin(\theta_1 - 2\theta_2) - 2\sin(\theta_1-\theta_2)m_2(\dot{\theta}_2^2 l_2 + \dot{\theta}_1^2 l_1\cos(\theta_1 - \theta_2))}{l_1(2m_1+m_2-m_2\cos(2\theta_1-2\theta_2))}$$ <br> <br> $$\large \ddot{\theta}_2 = \frac{2\sin(\theta_1-\theta_2)(\dot{\theta}_1^2 l_1 (m_1 + m_2) + g(m_1 + m_2)\cos(\theta_1) + \dot{\theta}_2^2 l_2 m_2\cos(\theta_1-\theta_2))}{l_2(2m_1+m_2-m_2\cos(2\theta_1-2\theta_2))}$$ | <img src="double-simulation.gif" width="400"/> |
| **Driven Pendulum** <br> <img src="damped-driven-pendulum.png" width="400"/> <br> $$\Large \ddot{\theta} + \omega^2\theta = \frac{A}{ml}\cos(\Omega t)$$ <br> <br> $$\large \bullet$$ $$F_{ext} = A\cos(\Omega t)$$ <br> $$\large \bullet$$ ignoring damping $$F_a = -\gamma l \dot{\theta}$$ <br> $$\large \bullet$$ small-angle approximation $$\sin\theta \approx \theta$$ | <img src="driven-simulation.gif" width="400"/> |
| **Damped Driven Pendulum** <br> <img src="damped-driven-pendulum.png" width="400"/> <br> $$\Large \ddot{\theta} = - \frac{g}{l}\sin\theta + \frac{-\gamma \dot{\theta} + A\cos(\Omega t)}{ml^2}$$ | <img src="chaotic-simulation.gif" width="400"/> |
