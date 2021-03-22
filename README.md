## Image Colorization

Training data comes from Places, here: http://places.csail.mit.edu/. The list of train/val images used are in `places_sample_val.txt` and `places_sample_train.txt`.

Training notebooks are `colorization_ae_training.ipynb` and `colorization_vae_training.ipynb` for the AE and VAE models respectively.

Using/testing the models can be done with `testing_colorization_models.ipynb`.

Six sample images are in the folder `sample_images/`.

Results for models 1-4 on the six images are in `ae-non-fusion/`, `ae-fusion/`, `vae-non-fusion/`, and `vae-fusion/`.

Graphs of the loss are created in `analysis/`

Trained models are in the folder `models/`. Note that the final VAE fusion model was accidentally not saved, but a backup model of it was saved.