# Recipe Generator Application

This is a **Recipe Generator** application that provides recipes based on the dish name entered by the user. It leverages OpenAI's language model to generate accurate and creative recipes for various dishes. The app is deployed using [Streamlit](https://streamlit.io/), offering a simple and interactive user interface.

![image](https://github.com/user-attachments/assets/d2449a6c-393d-45ff-be55-217b3a1d9db8)

## Features

- **Instant Recipes**: Get a detailed recipe for any dish by just entering its name.
- **Customizable Options**: The application can provide variations based on dietary preferences, regional cuisines, or available ingredients.
- **User-Friendly Interface**: Deployed on Streamlit, making it accessible and easy to use.

## How to Use

1. **Enter a Dish Name**: Simply type the name of the dish you want to cook.
2. **Click 'Generate Recipe'**: Hit the button to fetch a customized recipe for your desired dish.
3. **View and Cook**: Review the recipe and start cooking right away!

## Tech Stack

- **OpenAI API**: Used to generate the recipes based on dish names.
- **Streamlit**: For deploying the web application and providing an interactive UI.

## Installation

To run the application locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/tanushreedour/Recipe-generator.git
    cd Recipe-generator
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Set up the OpenAI API key:
   - Create a `.env` file in the root directory.
   - Add your OpenAI API key:
     ```bash
     AZURE_OAI_ENDPOINT=
     AZURE_OAI_KEY=
     AZURE_OAI_DEPLOYMENT=
     ```

4. Run the application:
    ```bash
    streamlit run test-openai-model.py
    ```

## Deployment

The app is deployed on [Streamlit Sharing](https://share.streamlit.io/). You can access it from any device with an internet connection. Check it out [here](https://recipe-generator-openai.streamlit.app).

## Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License.

## Acknowledgments

- [OpenAI](https://openai.com) for the GPT model.
- [Streamlit](https://streamlit.io/) for the web app framework.

## Contact

For any questions or feedback, please contact tdaur0704@gmail.com.

---

Happy Cooking!
