# Training DNNs on CIFAR-10
Practicing model building and training in Keras on the CIFAR-10 dataset.

## Models
| Model                                  	| Validation Accuracy 	|
|----------------------------------------	|---------------------	|
| 20 dense layers (ELU)                  	| 44.3%               	|
| 20 dense layers + batch norm           	| 50.8%               	|
| 20 dense layers (SELU)                 	| 46.6%               	|
| 20 dense layers (SELU) + alpha dropout 	| 48.5%               	|
| 1 VGG Block                               | 67.0%                 |
| 2 VGG Blocks                              | 70.8%                 |
| 3 VGG Blocks                              | 73.4%                 |
| 3 BGG Blocks + dropout                    | 83.1%                 |