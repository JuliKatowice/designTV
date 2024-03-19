# This Python code snippet demonstrates a complex scenario involving multiple components, with colors for clarity.

# Import necessary libraries
import numpy as np
import matplotlib.pyplot as plt

# Define parameters
num_points = 100
x = np.linspace(0, 10, num_points)
y1 = np.sin(x)
y2 = np.cos(x)

# Plotting
plt.figure(figsize=(8, 6))

# Plot sin(x) curve in blue color
plt.plot(x, y1, color='blue', label='sin(x)')

# Plot cos(x) curve in red color
plt.plot(x, y2, color='red', label='cos(x)')

# Add labels and legend
plt.xlabel('x')
plt.ylabel('y')
plt.title('Plot of sin(x) and cos(x)')
plt.legend()

# Show plot
plt.grid(True)
plt.show()
