| File                  | Purpose                                                                                                                                                                          |
| --------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `baseline.py`         | Implements the **standard attack**, where \$y\$ is the product of smallest primes in \$(n, n^2)\$ until \$y < 2^n\$. Also includes theoretical and empirical analysis functions. |
| `Alternative.py`      | Implements **two alternative adversarial strategies**:<br>• Strategy A: \$y = q^m\$ (prime-power)<br>• Strategy B: product of **largest primes** under \$2^n\$                   |
| `Simulations.py` | Runs all three strategies across a range of values of \$n\$, printing both **theoretical** and **empirical false-positive rates** side by side.                                  |


Make sure Python 3 and the following libraries are installed:
pip install sympy matplotlib
