# Travel Itinerary Planner

## Overview
The **Travel Itinerary Planner** is a Gradio-based application that generates a personalized day trip itinerary based on the user's city and interests. The application leverages the **LangChain** framework and **Groq's LLaMA 3-70B model** to create customized travel plans.

## Features
- **User Input:** Enter the city and a list of interests.
- **AI-Powered Itinerary Generation:** Utilizes LLaMA 3-70B to generate a personalized itinerary.
- **Interactive UI:** Built using Gradio for easy interaction.
- **Customizable Theme:** Uses a unique UI theme (`Yntec/HaleyCH_Theme_Orange_Green`).

## Technologies Used
- **Python**
- **Gradio** (for the user interface)
- **LangChain** (for AI message handling)
- **LangGraph** (for state management)
- **LangChain Groq** (to interact with LLaMA 3-70B)
- **Dotenv** (to manage API keys securely)

## Installation
Ensure you have Python installed, then install the required dependencies:

```sh
pip install gradio langchain langgraph langchain_groq python-dotenv
```

## Environment Setup
Create a `.env` file in the project directory and add the following:

```sh
GROQ_API_KEY=your_groq_api_key_here
```

## Usage
Run the application with:

```sh
python travel_planner.py
```

Once the application is running, open the provided local Gradio link and enter your trip details to generate an itinerary.

## Project Structure
```
travel_itinerary_planner/
│── main_gradio.py    # Main application script
│── .env                 # Environment variables
│── requirements.txt      # Required dependencies
│── README.md            # Project documentation
```

## Results
![image](https://github.com/user-attachments/assets/76e1cadb-8d0e-4bd4-9460-f56a8b57b07c)


## Future Improvements
- Add multi-day itinerary support
- Integrate real-time weather updates
- Include restaurant and accommodation suggestions

## License
This project is licensed under the MIT License.

