# disasters-model

Disaster Model is a chatbot specifically designed to assist users with disaster-related inquiries. By integrating data about various disaster events and protocols into a large language model (LLM), this chatbot provides insightful information and advice for disaster preparedness, response, and recovery.

Features
- Interactive chatbot interface for disaster-related questions.
- Extensive database of disaster information.
- Personalized advice based on user queries.

Installation
To get started with Disaster Model, follow these steps:

1. Clone the repository:
   git clone https://github.com/samelana/disasters-model.git
   cd DisasterModel

2. Install the Gaia Node by running the command below:
   curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash

3. Run the following command to update your config.json to run with a small language model:
   gaianet init --config https://raw.githubusercontent.com/harishkotra/Gaia-8G/refs/heads/main/config_8g.json

4. Start the node:
   gaianet start

How to Use
- Open your web browser and navigate to the generated link.
- Start interacting with the chatbot by typing your disaster-related questions.

License
This project is licensed under the MIT License. See the LICENSE file for details.
