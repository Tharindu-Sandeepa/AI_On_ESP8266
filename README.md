# AI on ESP8266 Using Gemini AI API

Welcome to the **AI on ESP8266** project! This repository demonstrates how to integrate **Google's Gemini AI** with the **ESP8266** microcontroller using the Gemini API. By following the steps in this repository, you can ask AI-powered questions and get real-time responses directly from the ESP8266 module.

## 🚀 Overview

The combination of **AI** and **IoT** opens up exciting possibilities, and this project showcases how to bring AI into a small and powerful IoT device like the ESP8266. By using the **Gemini API**, we can make ESP8266 more intelligent and capable of providing AI-driven answers.

## 📝 Prerequisites

- **Arduino IDE** with ESP8266 board installed
- **ESP8266** microcontroller (Nodemcu)
- Wi-Fi connection
- **Gemini API Key** (Get your API key from [Gemini API Documentation](https://ai.google.dev/gemini-api/docs/api-key))

## 🔧 Setup Instructions

Follow the steps below to get started:

### 1. Install ESP8266 Board in Arduino IDE

Make sure you have the **ESP8266** board installed in Arduino IDE. You can follow this guide to install it:

- Go to **File > Preferences** in the Arduino IDE.
- In the **Additional Boards Manager URLs** field, add the following URL:http://arduino.esp8266.com/stable/package_esp8266com_index.json
- Then go to **Tools > Board > Boards Manager**, search for **ESP8266**, and install the latest version.

##const char* Gemini_Token = "your_gemini_api_key"; // Replace with your Gemini API key

4. Upload the Code

	1.	Open the Arduino IDE and paste the above code into a new sketch.
	2.	Replace the placeholders with your Wi-Fi credentials and Gemini API key.
	3.	Select your ESP8266 board in Tools > Board and the correct COM Port.
	4.	Click Upload to upload the code to your ESP8266.

5. Ask Questions to Gemini AI

After the upload is complete and your ESP8266 is connected to Wi-Fi, you can use the Serial Monitor to interact with the AI:

	•	Open the Serial Monitor (Ctrl + Shift + M).
	•	Set the baud rate to 115200.
	•	Type your question and press Enter to see the AI-powered response.
