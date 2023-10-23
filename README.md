# Internet Speed Test Project

This is a simple JavaScript project that allows you to test your internet connection speed by measuring the download speed of images from the internet. The project is deployed at [detect-internet-project.netlify.app](https://detect-internet-project.netlify.app).

## How It Works

This internet speed test project works by fetching random images from Unsplash and measuring the time it takes to download these images. It then calculates the download speed in bits per second (bps), kilobits per second (Kbps), and megabits per second (Mbps) based on the image size and download time.

The key components and functionality of this project include:

1. **Test Initialization**: When you open the project, it automatically initiates the test. In this implementation, five tests are run to provide a more accurate average speed measurement.

2. **Image Loading**: The project uses the `Image` object to load random images from Unsplash. Each image's download time is measured.

3. **Speed Calculation**: The download speed is calculated based on the image size and the time taken to download it.

4. **Average Speed**: After all tests are completed, the project calculates and displays the average download speeds in bps, Kbps, and Mbps.

5. **Display Results**: The average download speeds are displayed on the webpage for the user to see.

## How to Use

1. Visit the project's website at [detect-internet-project.netlify.app](https://detect-internet-project.netlify.app).

2. You will see a message indicating that the test is in progress.

3. The project will run a series of tests to measure your internet connection speed.

4. After completing all tests, the project will display the average download speeds in bits per second (bps), kilobits per second (Kbps), and megabits per second (Mbps).

## Technologies Used

- HTML: The structure of the webpage.
- JavaScript: For measuring download speeds and performing calculations.
- Netlify: The project is hosted on Netlify for easy access.

## Author

This project is created and maintained by [Your Name].

## License

This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgments

- Thanks to Unsplash for providing random images for testing.
- Special thanks to the open-source community for various libraries and tools used in this project.
