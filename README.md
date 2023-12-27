We did run these two models on our own machine. Actually, we first try to run the VAE model, and the origin code of this essay use the MNIST dataset, so we decided to choose one image from this dataset as the base image of our second hyperprior model.
Our results in the report are truly got by ourselves.
The data of JPEG and WebP we got them from following code, and some other subsequent code.
rec_jpeg, bpp_jpeg = find_closest_bpp(target_bpp, img)
rec_webp, bpp_webp = find_closest_bpp(target_bpp, img, fmt='webp')
