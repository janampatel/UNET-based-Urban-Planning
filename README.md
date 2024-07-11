# UNet-based Urban Planning

## Dataset

The dataset used in this project is the [Semantic Segmentation of Aerial Imagery](https://www.kaggle.com/datasets/humansintheloop/semantic-segmentation-of-aerial-imagery) dataset available on Kaggle. It includes satellite images and their corresponding segmentation masks.

## Approaches

1. **Resizing Big Images**: In this approach, the large satellite images were resized to a fixed dimension suitable for the UNet model.
2. **Creating Patches Using Patchify**: In this approach, the large images were divided into smaller patches using the patchify library, and these patches were used for training the model.

## Usage
1. Preparing data by resizing the big images.
2. Ppreparing data by creating patches of the images using patchify.
3. Training the UNet-based model on the resized images.
4. Ttraining the UNet-based model on the patched images.
5. Comparing the results of the two approaches.

## Contributing

Contributions are welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
```

Feel free to adjust the content according to your project's specifics and needs.
