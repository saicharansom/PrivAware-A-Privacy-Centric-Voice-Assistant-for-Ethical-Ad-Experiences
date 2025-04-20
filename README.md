# PrivAware: A Privacy-Centric Voice Assistant for Ethical Ad Experiences

PrivAware is an innovative voice assistant architecture designed to provide personalized ad experiences while prioritizing user privacy. This project demonstrates how voice assistants can operate in an economically sustainable manner without compromising on user data protection.

## Installation

To get started with PrivAware, ensure you have Docker installed on your system. The project comes packaged with a Dockerfile for easy setup and a `requirements.txt` file for managing Python dependencies.

### Steps

1. Clone the repository:
   ```
   git clone [https://github.com/](https://github.com/saicharansom/PrivAware-A-Privacy-Centric-Voice-Assistant-for-Ethical-Ad-Experiences.git)
   ```
2. Navigate to the project directory:
   ```
   cd PrivAware-A-Privacy-Centric-Voice-Assistant-for-Ethical-Ad-Experiences
   ```
3. Build the Docker image:
   ```
   docker build -t privaware
   ```
4. Run the Docker container:
   `docker run -p 8501:8501 privaware
   After running the container, PrivAware will be accessible at http://localhost:8501 in your browser.

## Usage

PrivAware integrates a voice assistant capable of understanding and responding to user queries in a privacy-preserving manner. All data processing and ad personalization logic are encapsulated within `Similator.py`.

- **Voice Assistant Interaction**: Use the provided interface to interact with the voice assistant.
- **Personalized Ads**: Experience personalized ad suggestions based on anonymized user data.
- **Privacy Settings**: Adjust your privacy settings and ad preferences via the user interface.

## Data

All user interaction data and preferences are stored in the `data` folder. This includes CSV files that are dynamically updated based on user interactions and settings.

## Contribution

Contributions to PrivAware are welcome. Whether you're interested in enhancing the voice recognition capabilities, improving the privacy features, or expanding the ad personalization algorithms, your input is valuable.

