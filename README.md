# Oxido_Recruitment_tast

### Installation and Setup

1. **Clone the repository**

    ```bash
    git clone https://github.com/NatanielChmielarz/Oxido_Recruitment_tast.git
    cd Oxido_Recruitment_tast
    ```

2. **Setup Virtual Environment**

    - Create a virtual environment and activate it

      ```bash
      python3 -m venv venv
      source venv/bin/activate  # On Windows use `venv\Scripts\activate`
      ```

3. **Install Required Packages**

    - Install the required packages using `requirements.txt`

      ```bash
      pip install -r requirements.txt
      ```

4. **Create .env File**

    - Create a `.env` file in the root directory of your project and add your `OPENAI_API_KEY`:

      ```bash
      OPENAI_API_KEY=your-api-key-here
      ```

    - Replace `your-api-key-here` with the actual OpenAI API key.

5. **Run the Application**

    - Run the `main.py` script to execute the application:

      ```bash
      python main.py
      ```

