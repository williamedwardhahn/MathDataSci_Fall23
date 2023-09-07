

```python 
import matplotlib.pyplot as plt
import numpy as np
from skimage.io import imread
from skimage.transform import resize
```

```python
url = 'https://upload.wikimedia.org/wikipedia/commons/thumb/d/da/Claude_Monet%2C_Saint-Georges_majeur_au_cr%C3%A9puscule.jpg/800px-Claude_Monet%2C_Saint-Georges_majeur_au_cr%C3%A9puscule.jpg'
im = imread(url)
plt.imshow(im);
im = resize(im,(512,512))
plt.imshow(im);
```
