## Comparison of deep learning methods for image deblurring on light optical materials microscopy data

Please refer to our IEEE Case 2021 paper for details: [TODO]

If you find our work useful in your research or publication, please cite our work:
```
@TODO
```

## Usage
### DeepDeblur
```
|--> models = saved model parameters
|--> optim = saved optimizer parameters
|--> result = generated output image as well as sharp reference + blurred image
|> metric.cvs = obtain PSNR and SSIM scores of the test dataset
```
For the program code, please go to the orignal repository of SeungjunNah [[repository](https://github.com/SeungjunNah/DeepDeblur-PyTorch)]

### DMPHN
```
|--> checkpoints = saved model parameters
|--> test_result --> generated output image as well as sharp reference + blurred image
                 --> metric.cvs = obtain PSNR and SSIM scores of the test dataset
```
For the program code, please go to the orignal repository of HongguangZhang [[repository](https://github.com/HongguangZhang/DMPHN-cvpr19-master)]


## Authors and Affiliation
Patrick Krawczyk Patrick.Krawczyk@hs-aalen.de - Materials Research Institute Aalen, Aalen University

Hermann Baumgartl Hermann.Baumgartl@hs-aalen.de - Machine Learning Research Group Prof. Buettner, Aalen University

Andreas Jansche Andreas.Janschel@hs-aalen.de - Materials Research Institute Aalen, Aalen University

Timo Bernthaler Timo.Bernthaler@hs-aalen.de - Materials Research Institute Aalen, Aalen University

Ricardo Buettner Ricardo.Buettner@hs-aalen.de - Machine Learning Research Group Prof. Buettner, Aalen University

Gerhard Schneider Gerhard.Schneider@hs-aalen.de - Materials Research Institute Aalen, Aalen University



