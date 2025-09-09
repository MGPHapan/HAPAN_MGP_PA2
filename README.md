## HAPAN_MGP_PA2

### Normalization Problem - basic preprocessing step in data analytics where values are centered by subtracting the mean and scaled by dividing by the standard deviation.

// Create a random 5 by 5 array

    import numpy as np
    p = np.random.rand(5, 5)

// Compute for mean and standard deviation

    m = p.mean()
    s = p.std()

// For normalization

    n = (p-m)/s

// Print for output

    print("Normalized:", n)

### Divisible by 3 Problem - involves creating a 10×10 array of squared numbers from 1 to 100 and identifying which elements are divisible by 3.

// Create a 10 by 10 array with squared numbers from 1 to 100

    d = np.arange(1, 101) ** 2

    d = d.reshape(10, 10)

// For all the elements divisible by 3

    s = d[d % 3 == 0]

// Print for output

    print("Array of Squares: ", d)

    print("All Elements that are divisible by 3: ", s)
