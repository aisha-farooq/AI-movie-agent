# AI Movie Production Agent 🎬

## Overview

The **AI Movie Production Agent** is a Streamlit-based application designed to help users develop movie concepts with the assistance of AI agents. It integrates **Claude Sonnet 3.5** from Anthropic for screenplay writing, **SerpAPI** for real-time actor search and availability, and a custom **Movie Producer** agent to oversee the script and casting process.

This tool is designed to automate the process of generating a movie script outline, casting suggestions, and a concise movie concept overview. Whether you are an aspiring filmmaker, a movie enthusiast, or someone who loves creative storytelling, this app can help bring your movie ideas to life.

---

## Features

- **Script Writing**: The ScriptWriter assistant generates a compelling movie script outline with character descriptions, key plot points, and a three-act structure.
  
- **Casting Suggestions**: The CastingDirector assistant suggests 2-3 actors for each main role based on past performances and current availability, using real-time data from SerpAPI.
  
- **Movie Concept Overview**: The MovieProducer assistant orchestrates the workflow by coordinating between the ScriptWriter and CastingDirector, summarizing both the script and casting suggestions into a movie concept overview.

- **Customizable Inputs**: Users can input their movie idea, select the genre, target audience, and estimated runtime, and receive a detailed movie concept.

---

## Installation

To get started with this project locally, follow these steps:

### Prerequisites

Ensure you have the following:

- Python 3.8+
- Streamlit
- Phi library (for Assistant tools)
- Anthropic API key (for Claude model)
- SerpAPI key (for actor search functionality)

### Steps

1. **Clone the repository**:

    ```bash
    git clone https://github.com/aisha-farooq/AI-movie-agent.git
    cd AI-movie-agent
    ```

2. **Create a virtual environment** (optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. **Install the dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

4. **Set up your API keys**:
   - Sign up for an Anthropic API key and a SerpAPI key.
   - Add them to the Streamlit app using the UI or configure them in the script directly (preferably securely).

---

## Usage

1. **Run the Streamlit app**:

    ```bash
    streamlit run app.py
    ```

2. **Enter your movie idea**: Once the app is running, you can interact with the UI by entering your movie idea, selecting the genre, target audience, and estimated runtime.

3. **Generate your movie concept**: Click on the **"Develop Movie Concept"** button to get a detailed response with a script outline and casting suggestions.

---

## Key Components

- **ScriptWriter**: Uses the Claude model (Anthropic) to generate a screenplay outline, character descriptions, and plot twists.
  
- **CastingDirector**: Leverages SerpAPI to search for suitable actors for the main roles based on the script's character descriptions.
  
- **MovieProducer**: Coordinates between the ScriptWriter and CastingDirector, providing a cohesive movie concept summary.

---

## Contributing

Contributions are welcome! If you’d like to contribute to this project, feel free to fork the repository and submit pull requests. Here are some ways you can contribute:
- Bug fixes
- Feature additions or improvements
- UI/UX enhancements
- Documentation updates

---


## Acknowledgments

- **Claude Sonnet 3.5** by Anthropic for natural language processing capabilities.
- **SerpAPI** for real-time actor search and availability data.

---

## Contact

For any questions or inquiries, feel free to reach out to me via my GitHub profile or email.
