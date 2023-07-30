# **UPT- Artist (Professional Logo and Image Generator)**
<img width="654" alt="GUI_and_Image" src="https://github.com/UmairThakur/UPT-Artist/assets/81063457/9c4543bd-e3b5-4a48-898f-f08175beea46">

## **Introduction**
The "Professional Logo Generator" is a Python application that utilizes OpenAI's GPT-3.5 language model to generate logos and images based on user input. It allows users to select the type of logo they want and provide a prompt for the logo/image generation. The application processes the data locally, ensuring data security, and generates a logo/image using the OpenAI API.

<img width="228" alt="GUI_Image" src="https://github.com/UmairThakur/UPT-Artist/assets/81063457/cfe37909-cf65-4a8c-afb6-0eb70cb1a3ac">
<img width="220" alt="logo_ss" src="https://github.com/UmairThakur/UPT-Artist/assets/81063457/b61e9096-be6a-415a-a872-b47307aed632">
<img width="227" alt="image_ss" src="https://github.com/UmairThakur/UPT-Artist/assets/81063457/7fb9436b-f9cf-4263-8c36-098eadfd22ed">

##### Please Note: The better the prompt is, the better the image will be.


## **Features**
1. **Logo Generation:** Users can select the type of logo they want from a dropdown menu.
2. **Prompt Input:** Users can enter a prompt that describes their requirements.
3. **Image Display:** The application will display the generated image in the GUI canvas and directly save it on your Desktop.
4. **Variations:** Multiple variations can be generated for the same prompt just by re-clicking the `Submit` button each time.
5. **Data Security:** The application ensures data security by processing data locally and only sharing metadata with the OpenAI API.

## **Requirements**
To run this project, ensure you have the following:
1. Python 3
2. `pip` package manager
3. An OpenAI API key stored as an environment variable `OPENAI_API_KEY`.

## **Environment Variable**
- To run this project, you will need to add the following environment variable having the OpenAI API key stored. **`OPENAI_API_KEY`**

To set your OpenAI API key as an environment variable, you can follow these general steps:

1. **Locate your API Key**: If you already have an OpenAI API key, make sure you have it ready. If you don't have one, you'll need to sign up for an API key from the OpenAI website.

2. **Set the Environment Variable**: The specific method for setting environment variables varies depending on your operating system.

   - **For Windows**:
     - Open the Start menu and search for "Environment Variables."
     - Click on "Edit the system environment variables."
     - In the System Properties window, click the "Environment Variables" button.
     - In the Environment Variables window, under "System Variables," click "New."
     - Enter `OPENAI_API_KEY` as the variable name and paste your API key as the variable value.
     - Click "OK" to save the changes.

   - **For macOS and Linux**:
     - Open a terminal window.
     - Edit your shell profile file (`.bashrc`, `.bash_profile`, `.zshrc`, etc.) using a text editor such as `nano` or `vim`.
     - Add the following line at the end of the file:
       ```
       export OPENAI_API_KEY=your_api_key_here
       ```
     - Save the file and exit the text editor.
     - Run `source ~/.bashrc` (or `source ~/.bash_profile`, `source ~/.zshrc`, etc.) to apply the changes in your current terminal session. Alternatively, you can close and reopen the terminal.

3. **Verify the Environment Variable**:
   To verify that the environment variable is set correctly, you can open a new terminal or command prompt and type the following command (depending on your OS):

   - **For Windows**:
     ```
     echo %OPENAI_API_KEY%
     ```

   - **For macOS and Linux**:
     ```
     echo $OPENAI_API_KEY
     ```

   If everything is set up correctly, the command should output your API key.

Please note that you should treat your API key as sensitive information and avoid sharing it publicly or committing it to version control systems. If you're working on a shared system, it's better to use a more secure method for storing your API key, such as using a secrets manager or configuration file with restricted permissions.

## **Usage**
1. After setting up the OpenAI API Key, just download and run the UPT - Artist.exe file from above.
2. The application window will open, showing a dropdown to select the type of logo and an input field to enter the prompt. 
4. Select the type of logo you want from the dropdown. If you just want to generate an image you can skip this part and directly enter the prompt.
5. Enter a prompt that describes your logo/image requirements in the input field.
6. Click the "Submit" button to generate the logo/image.
7. The generated logo/image will be displayed in the application window and saved as a `{current_timestamp}.png` on your Desktop.

## **Limitations**
1. The logo/image generation heavily depends on OpenAI's GPT-3.5 language model, and the accuracy of the generated logo/image may vary.
2. Complex or highly specific image requirements may not be handled effectively by the language model.

## **Reporting Bugs or Issues**
If you encounter any bugs or issues with the application, or have suggestions for improvements, please contact the author via email at 'umairthakursocial@gmail.com'. Your feedback is valuable and will help enhance the tool's performance and user experience.

## **License**
- You may use this application for personal, educational, or non-commercial purposes only.
- You may not use this application for any commercial purposes or distribute it for commercial gain.
- Attribution to the original author (Umair Thakur) is required when sharing or modifying the application.

**Note**: "UPT-Artist" application relies on external libraries, and their licenses and usage terms should be adhered to separately.
