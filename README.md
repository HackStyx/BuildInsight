# BuildInsight: Construction Progress Monitoring Platform

BuildInsight is a web-based application designed to monitor the physical progress of building construction projects. Leveraging AI and machine learning, the platform allows urban local bodies (ULBs) and state agencies to assess construction status remotely, reducing the need for frequent field visits.

## Features

- **Image Upload & Construction Stage Identification**: Upload images of the construction site, and the platform automatically identifies the current stage of construction.
- **Progress Tracking Over Time**: Compare current site images with previous ones to monitor changes and assess construction progress.
- **AI-Powered Analysis**: The platform adapts its analysis based on the type of construction activity, using machine learning models for accurate insights.
- **Error Detection and Alerts**: The software raises alerts if the uploaded image or details don’t match the selected construction stage.
- **Custom Construction Reports**: Generate tailored reports detailing construction progress and potential delays.

## Technologies Used

- **Backend**: Flask
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Image Processing**: OpenCV, NumPy
- **Machine Learning**: Scikit-image for SSIM
- **APIs**: Placeholder for LLaVA model integration

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/hackstyx/buildinsight.git
   cd buildinsight
   ```

2. **Set up a virtual environment**:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**:
   ```bash
   python app.py
   ```

5. **Access the application**:
   Open your web browser and go to `http://127.0.0.1:5000`.

## Usage

1. **Upload Images**: Navigate to the homepage and upload two images of the construction site.
2. **View Results**: The application will process the images and display the construction progress, change percentage, and other insights.
3. **Download Reports**: Generate and download custom reports for further analysis.

## Project Structure

- **app.py**: The main Flask application file handling routes and image processing.
- **templates/index.html**: The main HTML file for the web interface.
- **static/**: Contains static files like CSS, JavaScript, and images.
- **uploads/**: Directory for storing uploaded images.
- **results/**: Directory for storing processed results.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or support, please contact [me](mailto:contact@Innov8Infinity.com).

