# Nao Robot Dialogue Application Documentation

## Introduction

This documentation provides an overview of the Nao Robot Dialogue Application developed by Hamza Mohammed during the Robot in Residence program at the Goethe-Institut Accra. The project was funded by the Goethe-Institut and aimed to enhance the interaction between the Nao Robot and users. The application comprises three main files: `hello.dlg`, `hello.enu.top`, and `behaviour.xar`. Developers can program the Nao Robot using Choregraphe or a standard editor with the NAOqi SDK. 

## Project Details

- **Developer:** Hamza Mohammed
- **Manager:** Portia Eyram Meli Mansu, Head of Library and Information Service.
- **Funded By:** Goethe Institut as part of the Robot in Residence program
- **Project Location:** Goethe-Institut Accra
- **Acknowledgment:** Special thanks to the library staff at the Goethe-Institut,


## Files

The project consists of the following files:

1. `hello.dlg`: This file contains the dialogue script for the Nao Robot. It defines the conversation flow, including the robot's responses and actions.

2. `hello.enu.top`: This file serves as a configuration file for the Nao Robot's language settings. It allows for easy localization and customization of the dialogue.

3. `behaviour.xar`: This Choregraphe project file contains the behavior and animations for the Nao Robot. It specifies how the robot should move and interact during the dialogue.

## Usage

Users can run the Nao Robot Dialogue Application in either of the following ways:



### Using a Standard Editor and NAOqi SDK

1. Ensure that you have the NAOqi SDK installed on your computer. It works with python 2.7.

2. Open a standard code editor (e.g., Visual Studio Code).

3. Write a Python script using the NAOqi SDK to load and execute the `behaviour.xar` project file on the Nao Robot. Your script should include any necessary communication with the robot and customizations to the dialogue.

4. Run the Python script to start the dialogue application on the Nao Robot.

### Using Choregraphe

1. Open Choregraphe on a computer connected to the Nao Robot.

2. Load the `behaviour.xar` project file into Choregraphe.

3. Customize the dialogue and behavior as needed within Choregraphe.

4. Execute the application directly from Choregraphe to see the Nao Robot in action.

## Customization

To customize the Nao Robot Dialogue Application for specific use cases or languages, follow these steps:

1. Modify the `hello.dlg` file to update the dialogue script, including the robot's responses and actions.

2. Adjust the language settings in the `hello.enu.top` file to support different languages or dialects.

3. Edit the behaviors and animations in the `behaviour.xar` file to tailor the robot's movements and expressions to your requirements.

## Conclusion

The Nao Robot Dialogue Application can be easily customized and run either through Choregraphe or a standard code editor using the NAOqi SDK. For further inquiries or support, please contact Hamza Mohammed or the Goethe-Institut Accra.

Enjoy engaging conversations with the Nao Robot!
