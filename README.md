# Spirals Dataset Generator
Generate spiral dataset up to 4 spirals. The dataset is generated based on Matt White's algorithm.

# Usage
Download the source code and import it.

```python
import spiralsdataset.py
```

The generator returns x and y coordinates and classes. The generator accepts two parameters: density and maximum point on x coordinate.

The more density is, the more points are there within maximum point on x coordinate. As default, density = 1 and maximum point is 6.5.

```python
generate_two_spirals_dataset();   // Generate two spirals dataset
generate_three_spirals_dataset(); // Generate three spirals dataset
generate_four_spirals_dataset();  // Generate four spirals dataset
```
