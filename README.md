# Fashion MNIST Classification with TensorFlow

A CNN that identifies different types of clothing from images. Trained on the Fashion MNIST dataset with 85% accuracy.

## What it does

Classifies 10 clothing categories from 28x28 grayscale images: t-shirts, trousers, pullovers, dresses, coats, sandals, shirts, sneakers, bags, and ankle boots.

## Results

**Overall accuracy: 84.67%**

Best at recognizing:
- Ankle boots (96.3%)
- Bags (94.3%) 
- Sandals (94.2%)
- Trousers (91.0%)
- Sneakers (90.2%)

Worst at recognizing:
- Shirts (45.1%) - constantly mistakes them for t-shirts, pullovers, and coats

## What I learned

The model has no problem with items that have unique shapes (footwear, bags). But it struggles when clothes look similar like shirts, pullovers, and coats all get mixed up because they are very similar.
