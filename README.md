# Deforest-Detection-Analyser
This Streamlit app is designed to detect deforestation in images using K-means clustering. It takes an image as input and segments it into regions of potential afforestation and deforestation.

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/your_username/deforestation-detection.git
    ```

2. Navigate to the project directory:

    ```bash
    cd deforestation-detection
    ```

3. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

4. Run the Streamlit app:

    ```bash
    streamlit run app.py
    ```

5. Upload an image using the file uploader and observe the segmentation of the image into afforestation and deforestation regions.

## Requirements

- Python 3.6+
- OpenCV
- NumPy
- Streamlit
- Matplotlib

## File Structure

- `app.py`: The main Streamlit application code.
- `requirements.txt`: Contains the list of required Python packages and their versions.
- `assets/`: Directory to store static assets like images, CSS, or JavaScript files.

## Acknowledgements

This project is based on the concept of K-means clustering for image segmentation and utilizes Streamlit for building the interactive web application.

## License

This project is licensed under the [MIT License](LICENSE).
