# OCR

Simple OCR (optical character recognition) based on Discrete Fourier Transform, DFT. It works pretty good on screenshots of serif (Times New Roman) and sans-serif (Arial) fonts.

## Results:

### Arial
![image](https://github.com/wkazmierczak/OCR/assets/119811949/06f4c100-bf39-4562-bd44-189fc3dfe87a)

### Result for Arial text
> a quick brown fox jumps over the lazy dog while zealous cats quietly observe perhaps meditating with a hint of joy ul exuberance kindly
> leaping amidst nocturnal breezes grace ul y humming in jubilant whispers venturing with zeal across distant landscapes exploring forests
> rich with vibrant fol age

Correctness: 41/44, 93%

### Times New Roman
![image](https://github.com/wkazmierczak/OCR/assets/119811949/ab4fdba3-737b-407b-925f-145d24467a73)

### Result for Times New Roman text
> a quick brown fox jumps over the lazy dog while zealous cats quietly observe perhaps meditating with a hint o f joyful exuberance kindly
> leaping amidst nocturnal breezes grace fully humming in jubilant whispers venturing with zeal across distant landscapes exploring forests
> rich with vibrant foliage

Correctness: 42/44, 95%

## Future improvement plans

Implementing a more sophisticated algorithm like Bayesian Logistic Regression (or other) can indeed enhance the flexibility and accuracy of an OCR system, making it more adaptable to different fonts and varying image qualities.
