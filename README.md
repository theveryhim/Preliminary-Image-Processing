# Preliminary Image Processing

Here we prform basic operations on a sample image

## Mirror
<p align="center">
    <img src="Images/1.png" alt="Descriptive Alt Text" class="fit-width-image">
</p>

## Rotation
Rotate, rotate back and compare!

<p align="center">
    <img src="Images/2.png" alt="Descriptive Alt Text" class="fit-width-image">
</p>

```
Mean Squared Error between original & restored: 45.9735107421875
Mean Absolute Error between original & restored: 68.29672813415527
```

## Fourier transform

### Apply non-linear transformation for better visualization of magnitude  
<p align="center">
    <img src="Images/3.png" alt="Descriptive Alt Text" class="fit-width-image">
</p>

### Replace magnitude/phase randomly uniform  
<p align="center">
    <img src="Images/4.png" alt="Descriptive Alt Text" class="fit-width-image">
    <img src="Images/5.png" alt="Descriptive Alt Text" class="fit-width-image">
</p>
phase has it all!

### Filtering  
Applying low-band-high pass filter 
<p align="center">
    <img src="Images/6.png" alt="Descriptive Alt Text" class="fit-width-image">
</p>

## Interpolation

### Zero even rows and columns out
<p align="center">
    <img src="Images/7.png" alt="Descriptive Alt Text" class="fit-width-image">
</p>

### Interpolation: `Bicubic`
<p align="center">
    <img src="Images/8.png" alt="Descriptive Alt Text" class="fit-width-image">
</p>

```
PSNR between original and reconstructed image: 31.61 dB
```